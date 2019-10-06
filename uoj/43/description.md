# 题目描述

<p>在进行 Web 后端开发时，很重要的一个组件是 router。通常来说，后端的代码由许多 action 组成，router 的作用就是将发来的请求按照 URL 对应到相应的 action 上。</p>
<p>请求到达后端 Web 服务器时，已经不需要考虑域名和端口了，因此一个请求有如下形式：</p>
<p>“<samp>/{something_1}/{something_2}/.../{something_k}</samp>” 或 “<samp>/{something_1}/{something_2}/.../{something_k}?{parameter_list}</samp>”</p>
<p>其中 parameter_list 的组成为：“<samp>{name_1}={value_1}&amp;{name_2}={value_2}&amp;...&amp;{name_n}={value_n}</samp>”。（第一种情况中的 parameter_list 为空）</p>
<p>例如 “<samp>/user/list/show?gender=male&amp;birthyear=1990</samp>” 就是一个合法的请求，其中包含了两个参数 gender 和 birthyear，对应的 value 分别是 male 和 1990。</p>
<p>router 由许多条 path 组成，每一个 path 会对应到一个 action 上。router 在匹配 URL 到 path 时只看 parameter_list 之前的部分，例如之前的请求就只看 “<samp>/user/list/show</samp>” 这部分。parameter_list 内的参数会被直接送到 action 中。因此一个 path 总是具有如下形式：</p>
<p>“<samp>/{something_1}/{something_2}/.../{something_k}</samp>”</p>
<p>为了使得 router 更灵活，每一段中的 something 除了可以用具体的字符串外，还可以用一个正则表达式去匹配，并且提取出这部分的内容作为参数送到 action 去。这种情况下，something 的内容为“<samp>:{regexp_name}</samp>”，其中 regexp_name 对应一个正则表达式，会在后面给出具体的表达式。例如 router 中的一个 path 为 “<samp>/user/:handle/show</samp>”，其中“<samp>:handle</samp>” 对应了一个正则表达式，假设它可以匹配所有由小写英文字母组成的非空串。此时请求 “<samp>/user/testuser/show</samp>” 就能匹配这个 path，并且送往 action 多了一个 name 为 handle、value 为 testuser 的参数。再例如请求为 “<samp>/user/testuser/show?avatar=true&amp;message=hello</samp>” 的话，不仅能匹配之前的 path，送到 action 的参数就会有三个：handle、avatar、message，对应的 value 分别为 testuser、true 和 hello。</p>
<p>但是使用带正则表达式的 path 时也受到一些限制。具体来说，如果有 router 中有两个 path，他们前面 $i$ 个 something 段的内容完全相同（这 $i$ 段里面可以含正则表达式项，此时就要求是名称相同的正则表达式），然后第 $i+1$ 个 something 段的内容不同。下面分两种情况：</p>
<ol><li>一个 path 这一段的内容是普通字符串，另一个 path 这一段的内容对应了正则表达式，那么这个正则表达式一定无法匹配前一个 path 第 $i+1$ 段的字符串。例如一个 path 是 “<samp>/foo/:tmp/bar/pop</samp>”，另一个 path 是 “<samp>/foo/:tmp/:exp/push</samp>”，那么 exp 对应的正则表达式一定不会匹配 bar。</li>
<li>两个 path 这一段的内容都是正则表达式，那么这两个正则表达式匹配的字符串一定没有交集。例如一个 path 是 “<samp>/foo/:tmp/:aaa/push</samp>”，另一个 path 是 “<samp>/foo/:tmp/:bbb/pop</samp>”，那么不存在一个字符串能同时被 aaa 对应的正则表达式和 bbb 对应的正则表达式匹配。</li>
</ol><p>最后介绍正则表达式。为了让情况简单一些，本题中的正则表达式规则相比于实际使用的有所简化。正则表达式的文法中有 Atom、Quantifier、Term、Alternative 这几个概念。用 Regexp 表示正则表达式，则每种概念具体为：</p>
<ol><li>Regexp 可以由单个 Alternative 组成，或者由一个 Alternative 和一个 Regexp 组成，中间用字符 “<samp>|</samp>” 连接。对于前一种情况，该正则表达式匹配所有 Alternative 能匹配的东西。对于后一种情况，一个字符串要能被该正则表达式匹配，要么能被 “<samp>|</samp>” 前面的 Alternative 能匹配，要么能被 “<samp>|</samp>” 后面的 Regexp所匹配。</li>
<li>Alternative 由单个 Term 或多个 Term 连接组成，它能匹配这些 Term 所匹配的字符串的连接。换言之，一个字符串要被这个 Alternative 匹配，这个字符串能够拆成若干段（段数和 Alternative 的 Term 个数一样多），每段依次被 Alternative 的每个 Term 匹配。</li>
<li>Term 由一个 Atom 或一个 Atom 附带一个 Quantifier 组成。后面会了解到，Quantifier 对应了允许重复次数的区间。若 Term 由单个 Atom 组成，则 Term 能匹配的内容与 Atom 相同。如果 Atom 后带了 Quantifier，则如果一个字符串能划分为若干段（划分的段数在 Quantifier 指定的区间内），使得每段都能被 Atom 匹配，那么这个字符串就能被这个 Term 匹配。</li>
<li>Quantifier 的形式为 “<samp>{lower_bound,upper_bound}</samp>”，其中 lower_bound 和 upper_bound 各对应一个不超过 $20$ 的非负整数，并且 $\text{upper_bound} \geq \text{lower_bound}$，Quantifier 对应的区间为闭区间 $[\text{lower_bound}, \text{upper_bound}]$。注意 upper_bound 可以为空（此时中间的逗号还是有的），upper_bound 为空表示上界为无穷大。<samp>{1,3}</samp>, <samp>{0,1}</samp>, <samp>{2,2}</samp>, <samp>{3,}</samp> 均为合法的 Quantifier，但 <samp>{3,2}</samp>, <samp>{,1}</samp> 就不合法。</li>
<li>Atom 有三种形式：第一种为单个字符，这里字符约定只能是英文字符（包括大写和小写）和数字，这种形式下的 Atom 所能匹配的内容就是该字符。第二种形式为字符区间，具体形式为 “<samp>[lower-upper]</samp>”，这里 lower 和 upper 各为单个字符，满足要么同时为小写英文字母、要么同时为大写字母、要么同时为数字，并且 lower 的ASCII码不小于 upper 的ASCII码，这种情况下的 Atom 所能匹配的内容就是这个区间内的字符（包括 lower 和 upper）。第三种形式是 “<samp>(Regexp)</samp>”，即一个合法的正则表达式套上一对括号，这种情况下该 Atom 能匹配的内容和括号内的正则表达式相同。</li>
</ol><p>根据以上文法，“<samp>[0-9]{1,3}</samp>” 为合法的正则表达式，它能匹配长度为 $1 \sim 3$ 且由数字组成的字符串。“<samp>([a-z]|[0-9]){3,10}</samp>” 也为合法的正则表达式，它能匹配长度为 $3 \sim 10$ 且由小写英文字母和数字组成的字符串。更复杂的一个例子为 “<samp>01[0-1]{0,}|10[0-1]{0,}</samp>”，它能匹配所有 <samp>01</samp> 或 <samp>10</samp> 开头的 <samp>01</samp> 字符串。</p>

# 输入格式


<p>第一个一个正整数 $T$，表示数据的组数。下面依次给出每组数据。</p>
<p>每组数据的第一行包含一个正整数 $N$，表示 router 中有 $N$ 个 path。下面 $2N$ 行，每两行描述一个 path，第一行为 path 匹配的 URL，形式为</p>
<p>“<samp>/{something_1}/{something_2}/.../{something_k}</samp>”</p>
<p>每段 something 要么为具体的字符串（由大写英文字母、小写英文字母和数字组成且长度在 $[1,50]$ 内），要么为 “<samp>:{regexp_name}</samp>”，其中 regexp_name 由大写和小写英文字母组成且长度不超过 $30$。具体的正则表达式会在之后的输入中给出。描述该 path 的第二行为对应的 action 名称（由大写和小写英文字母组成，长度在 $[1,30]$ 内）。</p>
<p>下面若干行描述前面 path 中出现的所有正则表达式，每行描述一个正则表达式，每行内包含两个非空字符串（由一个空格隔开），前面的字符串表示 regexp_name，后面的字符串表示对应正则表达式（长度不超过 $50$）。注意同一个 regexp_name 可能在前面给出的 path 中出现多次（一个 path 中出现多次或在不同 path 中出现），这种情况下他们对应的正则表达式是相同的，并且输入中只会描述一次。数据同时保证这里给出的 regexp_name 都至少在一个 path 中出现过。</p>
<p>下面一行包含一个正整数 $M$，表示有 $M$ 个请求发了过来。下面 $M$ 行，每行描述一个请求的 URL。URL 为 “<samp>/{something_1}/{something_2}/.../{something_k}</samp>” 或 “<samp>/{something_1}/{something_2}/.../{something_k}?{name_1}={value_1}&amp;{name_2}={value_2}&amp;...&amp;{name_n}={value_n}</samp>” 的形式，其中所有 something 和 value 都由大写英文字母、小写英文字母和数字组成且长度在 $[1,50]$ 内，所有 name 都由大写和小写英文字母组成且长度在 $[1,30]$ 内。</p>

# 输出格式


<p>对于每组数据，先单独一行输出 “<samp>Case #{case_no}:</samp>”（不含引号），其中 case_no 表示当前是第几组数据（从 $1$ 开始编号）。</p>
<p>每行输出依次对应每个请求。如果没有 path 能够匹配该请求的 URL，输出 “<samp>404 Not Found</samp>”。</p>
<p>如果有 path 能够匹配改请求，输出 “<samp>Request matches action &#34;{action_name}&#34; with parameters {parameter_list}</samp>”，其中 action_name 为匹配 path 对应 action 的名称，parameter_list 为所有的参数。</p>
<ul><li>其中 parameter_list 用一个字典的方式输出。例如有三个参数，他们的 name 为 avatar、message 和 page，对应的 value 分别为 true、hello 和 2，那么输出的 parameter_list 为 “<samp>{&#34;avatar&#34;:&#34;true&#34;,&#34;message&#34;:&#34;hello&#34;,&#34;page&#34;:&#34;2&#34;}</samp>”（所有参数按照 name 的字典序排列）。</li>
<li>注意一个请求中，拥有相同 name 的参数可能出现多次，例如请求的 URL 为 “<samp>/user/me/show?name=you&amp;name=he</samp>”，匹配的 path 为 “<samp>/user/:name/show</samp>”，此时的 parameter_list 为 “<samp>{&#34;name&#34;:[&#34;me&#34;,&#34;you&#34;,&#34;he&#34;]}</samp>”。方括号里面按照参数在请求 URL 中出现的次序给出。</li>
<li>更多具体的例子请参考样例。数据能够保证一个请求不会被多个 path 匹配。</li>
</ul>
# 样例一


<h4>input</h4>
<pre>3
3
/user/:id/show
userShow
/message/list
messageList
/message/:id/show
messageShow
id [0-9]{2,4}
3
/message/list
/user/123/show?avatar=true
/message/5312/show?page=1
1
/foo/:id/:bar/:bar
fun
id [0-9]{2,4}
bar [a-z]{1,3}
1
/foo/777/az/bc?bar=xyz&amp;bar=zzz
2
/user/:handle/show
userShow
/user/:id/show
userShow
id [0-9]{2,4}
handle ([a-z]|[A-Z])([a-z]|[A-Z]|[0-9]){4,10}
4
/user/259/show
/user/wjmzbmr/show?like=true
/user/0xxx/show
/user/WJMZBMR/show?love=true

</pre>

<h4>output</h4>
<pre>Case #1:
Request matches action &#34;messageList&#34; with parameters {}
Request matches action &#34;userShow&#34; with parameters {&#34;avatar&#34;:&#34;true&#34;,&#34;id&#34;:&#34;123&#34;}
Request matches action &#34;messageShow&#34; with parameters {&#34;id&#34;:&#34;5312&#34;,&#34;page&#34;:&#34;1&#34;}
Case #2:
Request matches action &#34;fun&#34; with parameters {&#34;bar&#34;:[&#34;az&#34;,&#34;bc&#34;,&#34;xyz&#34;,&#34;zzz&#34;],&#34;id&#34;:&#34;777&#34;}
Case #3:
Request matches action &#34;userShow&#34; with parameters {&#34;id&#34;:&#34;259&#34;}
Request matches action &#34;userShow&#34; with parameters {&#34;handle&#34;:&#34;wjmzbmr&#34;,&#34;like&#34;:&#34;true&#34;}
404 Not Found
Request matches action &#34;userShow&#34; with parameters {&#34;handle&#34;:&#34;WJMZBMR&#34;,&#34;love&#34;:&#34;true&#34;}

</pre>


# 限制与约定


<p>对于 30% 的数据，path 中不会出现正则表达式；</p>
<p>对于 100% 的数据，$N, M \leq 20000$，$T \leq 5$，输入文件大小不超过 $10\texttt{MB}$。不同名称的正则表达式最多有 $50$ 个。</p>
<p><strong>注意此题数据是良心数据。</strong></p>
<p><strong>时间限制</strong>：$20\texttt{s}$</p>
<p><strong>空间限制</strong>：$256\texttt{MB}$</p>

# 来源


<p>中国国家队清华集训2014~2015 Day 3 - By 贾志鹏</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=43">样例数据下载</a></p>
