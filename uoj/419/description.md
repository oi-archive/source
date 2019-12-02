# 题目描述

<p>Snuke 有一个白色的平面。她会依次进行 $n$ 次操作。在第 $i$ 次操作中，她会把圆心在 $(x_i, y_i)$、半径为 $r_i$ 的圆涂成黑色。</p>
<p>Takahashi 想要知道，每一次操作结束后，平面上黑色部分的面积是多少。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行输入一个整数 $T$，表示子任务编号。</p>
<p>第二行输入一个整数 $n$。</p>
<p>接下来 $n$ 行，第 $i + 1$ 行输入三个整数 $x_i, y_i, r_i$。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出 $n$ 行，第 $i$ 行输出一个实数，表示第 $i$ 次操作结束后，平面上黑色部分的面积。</p>
<p>你的答案被判定为正确，当且仅当你每一行输出的答案与参考答案之间的<strong>绝对或相对误差</strong>小于 $10^{-9}$。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">1
2
0 0 1
1 0 2</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">3.1415926536
12.5663706144</code></pre>
<h4>explanation</h4>
<p>第一个圆的圆心在 $(0, 0)$，半径为 $1$，它的面积是 $\pi$。</p>
<p>第二个圆的圆心在 $(1, 0)$，半径为 $2$。它完全包含了第一个圆，所以这两个圆的并的面积是 $4 \pi$。</p>

# 样例二


<h4>input</h4>
<pre><code class="sh_plain">2
6
-9 -6 3
9 -2 2
0 -1 2
0 -1 2
10 -6 6
-3 -7 7</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">28.2743338823
40.8407044967
53.4070751110
53.4070751110
154.0763284686
282.6344779456</code></pre>

# 样例三


<h4>input</h4>
<pre><code class="sh_plain">3
6
2 10 1
1 10 1
2 10 1
2 9 1
4 8 1
4 8 1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">3.1415926536
5.0548156086
5.0548156086
6.8402137720
9.9818064256
9.9818064256</code></pre>

# 限制及约定


<p>对于所有数据，保证：</p>
<ul><li>$1 \le n \le 2000$</li>
<li>$-10^4 &lt; x_i, y_i &lt; 10^4$</li>
<li>$0 &lt; r_i &lt; 10^4$</li>
</ul><div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n \le$</th><th rowspan="1">特殊性质</th><th rowspan="1">分数</th><th rowspan="1">依赖的子任务</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">$2$</td><td rowspan="2">无</td><td rowspan="1">18</td><td rowspan="1">无</td></tr><tr><td rowspan="1">2</td><td rowspan="1">$30$</td><td rowspan="1">15</td><td rowspan="1">1</td></tr><tr><td rowspan="1">3</td><td rowspan="2">$200$</td><td rowspan="1">$r_i = 1$</td><td rowspan="1">13</td><td rowspan="1">无</td></tr><tr><td rowspan="1">4</td><td rowspan="2">无</td><td rowspan="1">25</td><td rowspan="1">1, 2, 3</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$2000$</td><td rowspan="1">29</td><td rowspan="1">1, 2, 3, 4</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$2\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=419">样例数据下载</a></p>
