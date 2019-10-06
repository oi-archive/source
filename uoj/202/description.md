# 题目描述

<p>众所周知，香山的红叶非常著名。然而，CTSC 举行的时间是在 5 月，而红叶的季节是秋天，所以这个季节是看不到红叶的，于是我们在 CTSC 比赛中就只能讨论香山的树了。</p>
<p>s-quark 很喜欢这些树，他计划在每棵树上贴一个各不相同的标签。每个标签为条形，可以在树干上绕成一圈。为了区分每一棵树，s-quark 在每个标签上印了一个由小写英文字母组成的字符串。由于树干周长的限制，标签的长度也是有限的，因此这个字符串至多只能由N个字母组成。</p>
<p>但是，由于标签是在树干上围成一圈的，所以当标签在树上贴好以后，就不再能找到标签的起始位置了。所以，如果两棵树上的标签循环同构，例如分别为 &#34;<samp>abc</samp>&#34; 和 &#34;<samp>cab</samp>&#34; ，那么这两棵树就不再能通过标签区分了。针对这个问题，s-quark 想了一个巧妙的办法。对于一个已经在树上贴好的标签，s-quark 规定它的起始位置必须是能够使得字符串的字典序最小的起始位，即如果看到的字符串是 &#34;<samp>aba</samp>&#34;，那么就可以推断出从正确的起始位置开始看到的字符串应为 &#34;<samp>aab</samp>&#34;。</p>
<p>另外，对于有些标签，例如 &#34;<samp>abab</samp>&#34;，尽管符合字典序最小的规则，但是这样的起始位置不唯一，s-quark 认为这种情况也是不理想的。所以，这样的标签 s-quark 也会避免使用。s-quark 已经把所有的树都编好了顺序，准备在第一棵树上贴标签 &#34;<samp>a</samp>&#34;，之后按照字典序给每棵树贴上不同的标签。</p>
<p>以 $n=3$ 为例，s-quark将依次使用这些标签来标记这些树木：<samp>a</samp>, <samp>aab</samp>, <samp>aac</samp>, …, <samp>aaz</samp>, <samp>ab</samp>, <samp>abb</samp>, …, <samp>abz</samp>, <samp>ac</samp>, …</p>
<p>s-quark 知道，香山上的树总共有 $K$ 棵。他想知道他将在最后一棵树上贴的标签是什么。但是，这个问题显然太简单了。现在，s-quark 要问你，如果他在第一棵树上贴的标签是字符串 $S$，那么他将在最后一棵树上贴的标签是什么呢？</p>

# 输入格式


<p>输入的第一行两个正整数 $N$ 和 $K$，分别为字符串的长度和树的总数。</p>
<p>第二行一个由小写英文字母组成的字符串 $S$，表示在第一棵树上所贴的标签。$S$ 的长度不超过 $N$，并且保证是一个合法的标签。</p>

# 输出格式


<p>输出仅一行，输出一个字符串 $T$，表示 s-quark 将在最后一棵树上贴的标签，或输出 $-1$，表示剩余的合法标签数量不足以贴完所有的树。</p>

# 样例一


<h4>input</h4>
<pre>3 10
a

</pre>

<h4>output</h4>
<pre>aaj

</pre>


# 样例二


<h4>input</h4>
<pre>3 10
xy

</pre>

<h4>output</h4>
<pre>yzz

</pre>


# 样例三


<h4>input</h4>
<pre>1 100
a

</pre>

<h4>output</h4>
<pre>-1

</pre>


# 样例四


<h4>input</h4>
<pre>25 1000000000000000
u

</pre>

<h4>output</h4>
<pre>uuuuuvxzuxvwwyzzuyzvxuvxw

</pre>


# 子任务


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$K$</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td>$=8$</td><td>$\leq 10^4$</td><td>$S$ 为字符串 &#34;<samp>a</samp>&#34;</td></tr><tr><td>2, 3</td><td>$=9$</td><td>$\leq 10^6$</td><td rowspan="6">无</td></tr><tr><td>4</td><td>$=8$</td><td rowspan="5">$\leq 10^{15}$</td></tr><tr><td>5</td><td>$=9$</td></tr><tr><td>6</td><td>$=10$</td></tr><tr><td>7, 8</td><td>$\leq 30$</td></tr><tr><td>9, 10</td><td>$\leq 50$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=202">样例数据下载</a></p>
