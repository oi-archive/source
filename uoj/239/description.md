# 题目描述

<p>伊尔沙特是一位软件工程师，他的工作是设计高效的数据结构。有一天，他发明了一个新的数据结构，这个数据结构可以存储一个 $n$ 位非负整数集合，$n$ 是 $2$ 的整数次幂，即 $n = 2^b$，$b$ 是非负整数。</p>
<p>这个数据结构初始为空，使用该数据结构的程序必须要遵守下列规则：</p>
<ul><li>程序可以添加一些元素到这个数据结构中，每次利用函数 <code>add_element(x)</code> 添加一个元素，每个元素是一个 $n$ 位整数，如果程序要添加的元素已经在数据结构中，则什么事情也不会发生；</li>
<li>当添加完最后一个元素以后，程序应该调用一次函数 <code>compile_set()</code>，而且只能调用一次；</li>
<li>最后，程序可以调用函数 <code>check_element(x)</code> 来检查元素 $x$ 是否在数据结构中，这个函数可以调用多次。</li>
</ul><p>当伊尔沙特第一次实现该数据结构时，他在写函数 <code>compile_set()</code> 时出现一个 bug，这个 bug 将集合中每个元素的二进制位以相同的方式重新排序，伊尔沙特希望你能帮助他找到由于该 bug 导致的重排列。</p>
<p>考虑一个序列 $p = [p_0, \ldots, p_{n - 1}]$，该序列中 $0$ 到 $n - 1$ 这 $n$ 个数字每个数字恰好出现一次，我们称该序列为一个排列。考虑集合终点一个元素，该元素的二进制表达为 $a_0, \ldots, a_{n - 1}$（$a_0$ 是最高位）。当函数 <code>compile_set()</code> 被调用时，这个元素将被元素 $a_{p_0}, a_{p_1}, \ldots, a_{p_{n - 1}}$ 替代。</p>
<p>同样的排列 $p$ 会被用于每个元素的二进制位的重排列，这个排列 $p$ 可以是任意一个排列，包括 $p_i = i，0 \le i \le n - 1$。</p>
<p>例如，假设 $n = 4, p = [2, 1, 3, 0]$，你已经插入的整数所对应的二进制表示为 $0000, 1100$ 和 $1111$。调用函数 <code>compile_set</code> 会将元素分别变成 $0000, 0101$ 和 $1110$。</p>
<p>你的任务是写一个程序，该程序通过和数据结构的交互来找到排列 $p$。该程序应该（按照下列顺序）：</p>
<ol><li>选择一个 $n$ 位整数的集合；</li>
<li>将这些整数插入到数据结构中；</li>
<li>调用函数 <code>compile_set</code> 来激活 bug；</li>
<li>检查某些元素是否在修改以后的集合中；</li>
<li>利用该信息来判断和返回排列 $p$。</li>
</ol><p>注意你的程序只能调用函数 <code>compile_set</code> 一次。</p>
<p>而且，你的程序调用库函数的次数是有限制的，具体的，你的程序可以</p>
<ul><li>调用 <code>add_element</code> 最多 $w$ 次（$w$ 表示“写”）；</li>
<li>调用 <code>check_element</code> 最多 $r$ 次（$r$ 表示“读”）。</li>
</ul>
# 实现细节


<p>你应该实现一个函数（方法）：</p>
<ul><li><code>std::vector&lt;int&gt; restore_permutation(int n, int w, int r)</code><ul><li>$n$：集合中每个元素的二进制表示的位数（也是排列 $p$ 的长度）；</li>
<li>$w$：你的程序调用函数 <code>add_element</code> 的最大次数；</li>
<li>$r$：你的程序调用函数 <code>check_element</code> 的最大次数；</li>
<li>函数应该返回恢复的排列 $p$。</li>
</ul></li>
</ul>
# 库函数


<p>为了和数据结构进行交互，你的程序应该使用下列三个函数（方法）</p>
<ul><li><code>void add_element(std::string x)</code>，该函数将 $x$ 所描述的元素添加到集合中。<ul><li>$x$：一个由 <samp>&#39;0&#39;</samp> 和 <samp>&#39;1&#39;</samp> 构成的字符串，它是要添加到集合中的元素的二进制表示，$x$ 的长度必须是 $n$。</li>
</ul></li>
<li><code>void compile_set()</code>，该函数必须调用一次且仅能调用一次。在调用该函数后，你的程序不能再调用函数 <code>add_element()</code>。在调用该函数之前，你的程序也不能调用函数 <code>check_element()</code>。</li>
<li><code>bool check_element(std::string x)</code>，该函数检查元素 $x$ 是否在修改以后的集合当中。<ul><li>$x$：一个由 <samp>&#39;0&#39;</samp> 和 <samp>&#39;1&#39;</samp> 构成的字符串，它是要检查的元素的二进制表示，$x$ 的长度必须是 $n$。</li>
<li>如果元素 $x$ 在修改后的集合中，则返回 <code>true</code>，否则返回 <code>false</code>。</li>
</ul></li>
</ul><p>注意：如果你的程序违反上述的任何一条限制，其评分输出将是 “Wrong Answer”。</p>
<p>对于所有的字符串，第一个字符都表示所对应整数的最高位。</p>
<p>评测程序在调用函数 <code>restore_permutation</code> 之前已经确定了排列 $p$。</p>

# 样例


<p>评测程序执行下列函数调用：</p>
<ul><li><code>restore_permutation(4, 16, 16)</code>，我们有 $n = 4$ 而且程序最多执行 $16$ 次 “写” 和 $16$ 次 “读” 操作。</li>
</ul><p>程序执行下列函数调用：</p>
<ul><li><code>add_element(&#34;0001&#34;)</code></li>
<li><code>add_element(&#34;0011&#34;)</code></li>
<li><code>add_element(&#34;0100&#34;)</code></li>
<li><code>compile_set()</code></li>
<li><code>check_element(&#34;0001&#34;)</code> <samp>returns</samp> <code>false</code></li>
<li><code>check_element(&#34;0010&#34;)</code> <samp>returns</samp> <code>true</code></li>
<li><code>check_element(&#34;0100&#34;)</code> <samp>returns</samp> <code>true</code></li>
<li><code>check_element(&#34;1000&#34;)</code> <samp>returns</samp> <code>false</code></li>
<li><code>check_element(&#34;0011&#34;)</code> <samp>returns</samp> <code>false</code></li>
<li><code>check_element(&#34;0101&#34;)</code> <samp>returns</samp> <code>false</code></li>
<li><code>check_element(&#34;1001&#34;)</code> <samp>returns</samp> <code>false</code></li>
<li><code>check_element(&#34;0110&#34;)</code> <samp>returns</samp> <code>false</code></li>
<li><code>check_element(&#34;1010&#34;)</code> <samp>returns</samp> <code>true</code></li>
<li><code>check_element(&#34;1100&#34;)</code> <samp>returns</samp> <code>false</code></li>
</ul><p>只有一个排列和函数 <code>check_element()</code> 返回的值一致：
排列 $p = [2, 1, 3, 0]$，因此，<code>restore_permutation</code> 应该返回 $[2, 1, 3, 0]$。</p>

# 子任务


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分数</th>
<th>$n = $</th>
<th>$w = $</th>
<th>$r = $</th>
<th>其他限制</th>
</tr></thead><tbody><tr><td>1</td><td>20</td><td>$8$</td><td>$256$</td><td>$256$</td><td>最多有两个下标 $i$ 满足 $p_i \ne i~(0 \le i \le n - 1)$</td></tr><tr><td>2</td><td>18</td><td>$32$</td><td>$320$</td><td>$1024$</td><td rowspan="4">无</td></tr><tr><td>3</td><td>11</td><td>$32$</td><td>$1024$</td><td>$320$</td></tr><tr><td>4</td><td>21</td><td>$128$</td><td>$1792$</td><td>$1792$</td></tr><tr><td>5</td><td>30</td><td>$128$</td><td>$896$</td><td>$896$</td></tr></tbody></table></div>


# 评测方式


<p>评测程序按照以下格式读入输入：</p>
<ul><li>第一行：整数 $n, w, r$，</li>
<li>第二行：$n$ 个整数，表示排列 $p$ 的元素。</li>
</ul><p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$2\texttt{GB}$</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=239">样例及测评库下载</a></p>
