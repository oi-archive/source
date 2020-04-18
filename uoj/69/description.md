# 题目描述

<p>春节期间，慢羊羊订购了一台高端电脑。结果买回来一看，果然高端：每秒能进行 $10^{20}$ 次计算，从此腰也不酸了腿也不疼了。</p>
<p>在这台电脑上有一种编程语言名叫 QAQ，它的代码由 $N$ 行组成，这台电脑会从第 $1$ 行开始，从上到下依次执行。</p>
<p>这种编程语言有 $26$ 个 32 位整数型变量，分别叫做 $a, \dots, z$。</p>
<p>有这样几种语句：</p>
<ul><li><code>input c</code> 从标准输入读入一个整数并存储在 $c$ 中。$c$ 可以是 $a$ 到 $z$ 的任意变量。</li>
<li><code>output c</code> 输出一个整数 $c$。$c$ 可以是 $a$ 到 $z$ 的任意变量。</li>
<li><code>c = b</code> 把 $b$ 的值赋给 $c$。$b$ 可以是32位整数或 $a$ 到 $z$ 的任意变量，$c$ 可以是 $a$ 到 $z$ 的任意变量。</li>
<li><code>c = a op b</code> 把 $a$ 和 $b$ 进行 <code>op</code> 运算并把值赋给 $c$。$a, b$ 可以是32位整数或 $a$ 到 $z$ 的任意变量，$c$ 可以是 $a$ 到 $z$ 的任意变量。<code>op</code> 有下面几种取值：<ol><li>算术运算符<ul><li><code>+</code> 表示 $a$ 和 $b$ 的加法。</li>
<li><code>-</code> 表示 $a$ 和 $b$ 的减法。</li>
<li><code>*</code> 表示 $a$ 和 $b$ 的乘法。</li>
<li><code>/</code> 表示 $a$ 和 $b$ 的除法，会按C++习惯向0取整。</li>
<li><code>%</code> 表示 $a$ 除以 $b$ 的余数。</li>
</ul></li>
<li>逻辑运算符<ul><li><code>==</code> $a$ 和 $b$ 相等则为 $1$ 否则为 $0$。</li>
<li><code>!=</code> $a$ 和 $b$ 不相等则为 $1$ 否则为 $0$。</li>
<li><code>&lt;</code> $a$ 小于 $b$ 则 $1$ 否则为 $0$。</li>
<li><code>&gt;</code> $a$ 大于 $b$ 则 $1$ 否则为 $0$。</li>
<li><code>&lt;=</code> $a$ 小于等于 $b$ 则 $1$ 否则为 $0$。</li>
<li><code>&gt;=</code> $a$ 大于等于 $b$ 则 $1$ 否则为 $0$。</li>
</ul></li>
</ol></li>
<li><code>if c goto t</code> 如果 $c$ 不为 $0$ 则跳到第 $t$ 行继续执行（也就是说下一次就会执行第 $t$ 行的语句）。$c$ 可以是32位整数或 $a$ 到 $z$ 的任意变量，$t$ 可以是任意正32位整数。</li>
</ul><p>当程序试图执行的语句的行号大于 $N$ 时程序结束。</p>
<p>由于要展望新的一年的发展前景，慢羊羊需要用这台电脑算出斐波那契数列的第 $n$ 项对 $m$ 取模后的结果。</p>
<p>但是很快慢羊羊发现了问题。这台电脑竟然有一定概率算错！仔细分析后慢羊羊得到了如下结论：</p>
<ol><li>在进行计算算术运算 <code>+</code>、<code>-</code>、<code>*</code>、<code>/</code>、<code>%</code> 时，有 $\frac{1}{8}$ 的概率返回一个32位随机整数。</li>
<li>在进行计算逻辑运算 <code>==</code>、<code>!=</code>、<code>&lt;</code>、<code>&gt;</code>、<code>&lt;=</code>、<code>&gt;=</code> 时，有 $\frac{1}{8}$ 的概率将返回的结果反转。即 $0$ 变 $1$，$1$ 变 $0$。</li>
<li>其它语句一定会正确执行。</li>
</ol><p>这可难坏了慢羊羊，他想请你帮他写一个程序能够以极高的概率算对斐波那契数列的第 $n$ 项对 $m$ 取模后的结果。</p>
<p><strong>所以，请你写一个程序，输出“一份能够完成任务的 QAQ 源代码”。</strong></p>
<p><strong>不看题就做题的人是厉害，如果请务必仔细读上面这句话。</strong></p>
<p>斐波那契数列 $f$ 的定义为：$f_0 = 0, f_1 = 1$，对于任意 $n \geq 2$ 的整数 $n$ 有 $f_n = f_{n - 1} + f_{n - 2}$。</p>
<p><strong>我们写了一个QAQ的解释器，见解释器下载。</strong></p>

# 例子


<p>下面这个例子读入一个整数 $n$，计算 $\sum_{k = 1}^{n} k$。（当然有一定概率算错）</p>
<pre><code class="sh_cpp">input n
k = 1
s = 0
c = k &gt; n
if c goto 9
s = s + k
k = k + 1
if 1 goto 4
output s</code></pre>
<p>下面的这些语句都是不合法的：</p>
<pre><code class="sh_cpp">input 233
if a + b == 2 goto 9
s = (a + b) * c
if c goto a
sb = s + b
k=1
k    =  1</code></pre>

# 输入格式


<p>没有输入文件。</p>

# 输出格式


<p>一份 QAQ 源代码。代码长度不能超过 $10^5$ 行。</p>
<p><strong>我们写了一个QAQ的解释器，见解释器下载。（很重要所以说两遍）</strong></p>

# QAQ程序的输入格式


<p>一行两个正整数 $n, m$。表示要你求斐波那契数列第 $n$ 项对 $m$ 取模后的结果。</p>

# QAQ程序的输出格式


<p>一行一个整数，表示结果。</p>

# QAQ程序的样例一


<h4>input</h4>
<pre>5 3

</pre>

<h4>output</h4>
<pre>2

</pre>

<h4>explanation</h4>
<p>前 $5$ 项分别为 $1, 1, 2, 3, 5$，而 $5 \bmod 3 = 2$，所以答案是 $2$。</p>

# 限制与约定


<p><strong>我们写了一个QAQ的解释器，见解释器下载。（很重要所以说三遍）</strong></p>
<p>本题共 $100$ 组测试数据。对于每个测试点，如果QAQ程序输出了正确答案则得 $1$ 分，否则得 $0$ 分。测评时使用伪随机数，随机数种子是以某种方式采集的，保证同一份源代码测评多次仍能得到同样的结果。</p>
<p>这 $100$ 组数据中，有 <samp>A</samp>，<samp>B</samp>，<samp>C</samp>，<samp>D</samp> 四类：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>数据类型</th>
<th>数据组数</th>
<th>特点</th>
</tr></thead><tbody><tr><td><samp>A</samp></td><td>10</td><td>$n = 2$，$10^8 \leq m \leq 10^9$</td></tr><tr><td><samp>B</samp></td><td>10</td><td>$n = 3$，$10^8 \leq m \leq 10^9$</td></tr><tr><td><samp>C</samp></td><td>50</td><td>$n \leq 16$，$10^8 \leq m \leq 10^9$</td></tr><tr><td><samp>D</samp></td><td>30</td><td>$n \leq 200$，$2 \leq m \leq 10^9$</td></tr></tbody></table></div>

<p>比赛时只会从每种类型的数据中抽取 $\frac{1}{10}$ 进行评测。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>
<p><strong>QAQ的时间限制：</strong>$10^6$ 条语句</p>

# 如何本地测试


<p><strong>我们写了一个QAQ的解释器，见解释器下载。（很重要所以说四遍）</strong>这是一个 C++ 的源代码，你可以自己编译后使用。</p>
<p>这个解释器会从当前目录下 prog.txt 里读取 QAQ 源代码并执行，根据当前系统时间定下随机数种子。</p>
<p>如果你不会使用，请参见 FAQ 里我们的联系方式。</p>

# 来源


<p>UOJ Goodbye Jiawu</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=69">解释器下载</a></p>
