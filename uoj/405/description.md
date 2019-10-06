# 题目描述

<p>你在玩一个动作游戏。游戏控制器有 $ 4 $ 个按键，<code>A</code>、<code>B</code>、<code>X</code> 和 <code>Y</code>。在游戏中，你用组合动作来赚金币。你可以依次按这些按键来完成一个组合动作。</p>
<p>这个游戏有一个隐藏的按键序列，可以表示为由这 $ 4 $ 个字符组成的串 $ S $。你并不知道这个串 $ S $，但是你知道它的长度为 $ N $。</p>
<p><strong>你还知道，$S$ 的首字符不会在串中重复出现。</strong>例如，$S$ 可以是“<code>ABXYY</code>”或者“<code>XYYAA</code>”，但不能是“<code>AAAAA</code>”或“<code>BXYBX</code>”。</p>
<p>你可以依次按最多 $ 4N $ 个按键来完成一个组合动作。串 $ p $ 为你所按的按键序列。你用这个组合动作赚到的金币数量，等于同时为 $ p $ 之子串和 $ S $ 之前缀的最长字符串的长度。串 $ t $ 的子串定义为 $ t $ 中的连续字符序列（可以为空）。$ t $ 的前缀定义为 $ t $ 的子串，其或者为空，或者包含 $ t $ 的首字符。</p>
<p>例如，如果 $S$ 是“<code>ABXYY</code>”，而 $ p $ 是“<code>XXYYABYABXAY</code>”，你会得到 $ 3 $ 个金币，因为“<code>ABX</code>”是可作为 $ p $ 的子串的 $ S $ 的前缀中最长的。</p>
<p>你的任务是，用少量的组合动作，找出隐藏字符串 $ S $。</p>

# 实现细节


<p>你需要实现下面的函数：</p>
<pre><code class="sh_cpp">std::string guess_sequence(int N)</code></pre>
<ul><li><code>N</code>：串 $S$ 的长度。</li>
<li>对每个测试用例，该函数被调用恰好一次。</li>
<li>该函数应返回串 $S$。</li>
</ul><p>你的程序可以调用下面的函数：</p>
<pre><code class="sh_cpp">int press(std::string p)</code></pre>
<ul><li><code>p</code>：你的按键序列。</li>
<li><code>p</code> 必须是长度为从 $0$ 到 $4N$ 的串（包括 $0$ 和 $4N$）。<code>p</code> 的每个字符必须是 <code>A</code>、<code>B</code>、<code>X</code> 或者 <code>Y</code>。</li>
<li>对每个测试用例，你调用该函数的次数不能超过 $8\ 000$ 次。</li>
<li>该函数的返回结果是，当按出按键序列 <code>p</code> 后你赚到的金币数量。</li>
</ul><p>如果不满足上面的条件，你的程序将被判为 <code>Wrong  Answer</code>。否则，你的程序将被判为 <code>Accepted</code>，而你的得分将根据 <code>press</code> 的调用次数来计算（参见子任务）。</p>

# 例子


<p>设 $S$ 为“<code>ABXYY</code>”。评测程序调用了 <code>guess_sequence(5)</code>。数据交互过程的例子如下所示：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>调用</th>
<th>返回值</th>
</tr></thead><tbody><tr><td> $ \texttt{press(&#34;XXYYABYABXAY&#34;)} $ </td><td> $ 3 $ </td></tr><tr><td> $ \texttt{press(&#34;ABXYY&#34;)} $ </td><td> $ 5 $ </td></tr><tr><td> $ \texttt{press(&#34;ABXYYABXYY&#34;)} $ </td><td> $ 5 $ </td></tr><tr><td> $ \texttt{press(&#34;&#34;)} $ </td><td> $ 0 $ </td></tr><tr><td> $ \texttt{press(&#34;X&#34;)} $ </td><td> $ 0 $ </td></tr><tr><td> $ \texttt{press(&#34;BXYY&#34;)} $ </td><td> $ 0 $ </td></tr><tr><td> $ \texttt{press(&#34;YYXBA&#34;)} $ </td><td> $ 1 $ </td></tr><tr><td> $ \texttt{press(&#34;AY&#34;)} $ </td><td> $ 1 $ </td></tr></tbody></table></div>

<p>对于 <code>press</code> 的第 $1$ 次调用，“<code>ABX</code>”是“<code>XXYYABYABXAY</code>”的子串，而“<code>ABXY</code>”不是，因此返回 $3$。</p>
<p>对于 <code>press</code> 的第 $3$ 次调用，“<code>ABXYY</code>”本身是“<code>ABXYYABXYY</code>”的子串，因此返回 $5$。</p>
<p>对于 <code>press</code> 的第 $6$ 次调用，除了空串以外没有“<code>ABXYY</code>”的其他前缀可以是“<code>BXYY</code>”的子串，因此返回 $0$。</p>
<p>最后，<code>guess_sequence(5)</code> 应当返回“<code>ABXYY</code>”。</p>
<p>在样例数据下载中的文件<code>ex_combo1.in</code>对应于本例。注意：样例包中的输出没有任何意义。</p>

# 限制条件


<ul><li>$1\le N\le 2\ 000$</li>
<li>串 $S$ 的每个字符必须是 <code>A</code>、<code>B</code>、<code>X</code> 或 <code>Y</code>。</li>
<li>$S$ 的首字符不会再 $S$ 中重复出现。</li>
</ul><p>在本题中，评测程序<strong>不是</strong>适应性的。意思是说，在评测程序开始运行的时候 $S$ 就固定下来，而且不依赖于你的程序所做的询问。</p>

# 子任务


<ol><li>（5分）$N=3$</li>
<li>（95分）没有附加限制。对该子任务，你在每个测试用例上的得分将计算如下。设 $q$ 为调用 <code>press</code> 的次数。<ul><li>如果 $q\le N+2$ ，你的得分为 $95$。</li>
<li>如果 $N+2 \lt q \le N+10$，你的得分为 $95-3(q-N-2)$。</li>
<li>如果 $N+10\lt q \le 2N+1$，你的得分为 $25$。</li>
<li>如果 $\max\{N+10,2N+1\}\lt q \le 4N$，你的得分为 $5$。</li>
<li>否则，你的得分为 $0$。</li>
</ul></li>
</ol><p>注意，你在每个子任务上的得分，等于你在该子任务下所有测试用例上的最低得分。</p>
<p><strong>请注意：在测试中，如果你的程序的询问次数超过 $ N + 2 $，则会得到 $ 0 $ 分。</strong>。</p>

# 评测程序示例


<p>评测程序示例将读取如下格式的输入：</p>
<ul><li>第 $1$ 行：$S$</li>
</ul><p>如果你的程序被判为 <code>Accepted</code>，评测系统示例将打印出 <code>Accepted:  q</code>，这里 <code>q</code> 为函数 <code>press</code> 的调用次数。</p>
<p>如果你的程序被判为 <code>Wrong Answer</code>，它打印出 <code>Wrong Answer: MSG</code>。各类 <code>MSG</code> 的含义如下：</p>
<ul><li><code>invalid press</code>：输入到 <code>press</code> 的值 <code>p</code> 是无效的。也就是说，<code>p</code> 的长度不在 $0$ 到 $4N$ 之间（含 $0$ 和 $4N$），或者 <code>p</code> 的某些字符不是 <code>A</code>、<code>B</code>、<code>X</code> 和 <code>Y</code>。</li>
<li><code>too many moves</code>：函数 <code>press</code> 的调用次数超过 $8\ 000$ 次。</li>
<li><code>wrong guess</code>：<code>guess_sequence</code> 返回的不是 $S$。</li>
</ul>
# 约定及限制


<p>对于所支持的各种编程语言，下面列出了对应的数据类型。对于数据类型的细节等，参见实现示例。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>语言</th>
<th>$\texttt{int}$</th>
<th>$\texttt{int64}$</th>
<th>$\texttt{int[]}$</th>
<th>数组$a$的长度</th>
<th>$\texttt{string}$</th>
</tr></thead><tbody><tr><td>$\texttt{C++}$</td><td>$\texttt{int}$</td><td>$\texttt{long long}$</td><td>$\texttt{std::vector&lt;int&gt;}$</td><td>$\texttt{a.size()}$</td><td>$\texttt{std::string}$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$268\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=405">样例数据下载</a></p>
