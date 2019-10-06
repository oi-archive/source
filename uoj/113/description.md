# 题目描述

<p>由于电信技术的发展，人人都可以通过手机互相联系。</p>
<p>有一位电信大佬最近想生产一大批手机，然而从生产线上一台一台地生产实在太慢了，于是他想出了一个办法 —— 让手机自我复制。</p>
<p>于是他给手机加上了一个内置的函数 <samp>fork()</samp>。手机的程序如果调用这个函数，那么手机会生产出一台<strong>完全一模一样</strong>的手机（<strong>包括程序运行状态</strong>），并且自己这台的函数返回值为 $1$，新手机的函数返回值为 $0$，然后两台手机都<strong>继续执行程序</strong>。（请注意黑体字内容）</p>
<p>初始时，只有一台手机。接着，大佬让手机计算形如这样的表达式：</p>
<pre><code class="sh_cpp">fork() &lt;op&gt; fork() &lt;op&gt; ... &lt;op&gt; fork()</code></pre>
<p>其中 <samp>&lt;op&gt;</samp> 是二元运算符，为 <samp>&amp;&amp;</samp> 或者 <samp>||</samp> 中的一种。例如：</p>
<pre><code class="sh_cpp">fork() &amp;&amp; fork() || fork() &amp;&amp; fork() &amp;&amp; fork() || fork()</code></pre>
<p>两个运算都是左结合的，且 <samp>&amp;&amp;</samp> 的优先级比 <samp>||</samp> 高，所以上面的那个表达式相当于：</p>
<pre><code class="sh_cpp">((fork() &amp;&amp; fork()) || ((fork() &amp;&amp; fork()) &amp;&amp; fork())) || fork()</code></pre>
<p>对于表达式 <samp>a &amp;&amp; b</samp>，手机会先计算 <samp>a</samp> 的值，如果为 $0$ 那么<strong>不计算</strong> <samp>b</samp> 的值（因为很重要所以说两遍，请注意这里<strong>不计算</strong> <samp>b</samp> 的值），该表达式值为 $0$；否则计算 <samp>b</samp> 的值并将其值作为该表达式的值。</p>
<p>对于表达式 <samp>a || b</samp>，手机会先计算 <samp>a</samp> 的值，如果为 $1$ 那么<strong>不计算</strong> <samp>b</samp> 的值（因为很重要所以说两遍，请注意这里<strong>不计算</strong> <samp>b</samp> 的值），该表达式值为 $1$；否则计算 <samp>b</samp> 的值并将其值作为该表达式的值。</p>
<p>表达式计算完成后，大佬制造出了数量惊人的手机，人类终于叩开了指数级工业制造的大门。</p>
<p>一万万年后，一位考古学家调查了此次事件。他得到了大佬让手机计算的表达式。他想知道大佬当年究竟制造出了多少台手机。（包括初始的那台手机）</p>
<p><strong>你可以参照样例解释来更好地理解题意。</strong></p>

# 输入格式


<p>第一行一个正整数 $n$，表示表达式中的 <samp>fork()</samp> 的数量。</p>
<p>接下来一行 $n - 1$ 个用空格隔开的字符串，每个字符串为 “<samp>&amp;&amp;</samp>” 或者 “<samp>||</samp>”，依次表示表达式中对应位置的运算符。</p>

# 输出格式


<p>一行，一个整数表示制造出的手机的数量，你只用输出答案对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数）取模后的结果。</p>

# 样例一


<h4>input</h4>
<pre>2
&amp;&amp;

</pre>

<h4>output</h4>
<pre>3

</pre>

<h4>explanation</h4>
<p>共生产 $3$ 台手机，过程如下：</p>
<ol><li>第 $1$ 台手机开始计算 <samp>fork() &amp;&amp; fork()</samp>。</li>
<li>第 $1$ 台手机开始计算 <samp>fork()</samp>，产生了第 $2$ 台手机。</li>
<li>第 $1$ 台和第 $2$ 台的 <samp>fork()</samp> 计算完成，第 $1$ 台返回 $1$，第 $2$ 台返回 $0$。</li>
<li>第 $1$ 台手机由于 <samp>fork()</samp> 返回值为 $1$，开始计算 <samp>fork() &amp;&amp; fork()</samp> 右边的 <samp>fork()</samp>，产生了第 $3$ 台手机。</li>
<li>第 $2$ 台手机由于 <samp>fork()</samp> 返回值为 $0$，于是 <samp>fork() &amp;&amp; fork()</samp> 值为 $0$（跳过右边的 <samp>fork</samp> 的计算），程序结束。</li>
<li>第 $1$ 台和第 $3$ 台的 <samp>fork()</samp> 计算完成，第 $1$ 台返回 $1$，第 $3$ 台返回 $0$。</li>
<li>第 $1$ 台手机由于 <samp>fork()</samp> 返回值为 $1$，于是 <samp>fork() &amp;&amp; fork()</samp> 值为 $1$，程序结束。</li>
<li>第 $3$ 台手机由于 <samp>fork()</samp> 返回值为 $0$，于是 <samp>fork() &amp;&amp; fork()</samp> 值为 $0$，程序结束。</li>
</ol>
# 样例二


<h4>input</h4>
<pre>6
&amp;&amp; || &amp;&amp; &amp;&amp; ||

</pre>

<h4>output</h4>
<pre>15

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
</tr></thead><tbody><tr><td>1</td><td>$n = 1$</td></tr><tr><td>2</td><td rowspan="3">$n \leq 5$</td></tr><tr><td>3</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="3">$n \leq 100$</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$n \leq 100000$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=113">样例数据下载</a></p>
