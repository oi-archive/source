# 题目描述

<p>这一天，小Y、小D、小C正在愉快地玩耍。</p>
<p>小Y是个数学家，他一拍脑袋冒出了一个神奇的<strong>完全平方数</strong> $n$。</p>
<p>小D是个机灵鬼，很快从小Y嘴里套出了 $n$ 的值。然后在脑内把 $n$ 写成了 $a \times b$的形式。其中 $a, b$都是正整数。</p>
<p>小C是个八卦狂，他发现小D从小Y那里获知了神奇的东西，于是死缠烂打追问小D。最后小D说道：“我可以告诉你正整数 $g$ 和 $l$ 的值，我保证 $ab = gl = n$ 且 $a, b$ 都是 $g$的倍数。但是 $a, b$ 我可不能告诉你。”</p>
<p>这可急坏了小C。他决定退而求其次，找出$a + b$的最小值和最大值。请你帮帮他吧！</p>

# 输入格式


<p>第一行一个正整数 $T$，表示有 $T$ 组询问。</p>
<p>接下来 $T$ 行每行两个正整数 $g, l$ 表示一组询问。</p>

# 输出格式


<p>对于每个询问输出一行两个正整数，分别表示 $a + b$ 的最小值与最大值。保证问题有解。</p>
<p>C/C++ 输入输出 long long 时请用 <code>%lld</code>。C++ 可以直接使用 cin/cout 输入输出。</p>

# 样例一


<h4>input</h4>
<pre>1
1 4

</pre>

<h4>output</h4>
<pre>4 5

</pre>

<h4>explanation</h4>
<p>只有三组解：$\{a = 1, b = 4\}, \{a = 2, b = 2\}, \{a = 4, b = 1\}$。</p>

# 样例二


<h4>input</h4>
<pre>1
2 8

</pre>

<h4>output</h4>
<pre>8 10

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$g, l$</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="3">$\leq 10^3$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="3">$\leq 10^9$</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$\leq 10^{18}$</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>保证 $T \leq 5$。</p>
<p><strong>时间限制：</strong>$1 \texttt{s}$</p>
<p><strong>空间限制：</strong>$256 \texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=12">样例数据下载</a></p>
