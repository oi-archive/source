# 题目描述

<p>红包是一个有拖延症的男孩子。</p>
<p>红包由于NOI惨挂心情不好，直到还剩下 $n$ 周的时候他才开始写作业。</p>
<p>由于红包会 “时间静止” 大法，所以红包的一周有 $m$ 天。</p>
<p>现在他把这 $n \times m$ 天排成 $n$ 行 $m$ 列的日历开始计划每天要写的作业量。</p>
<p>初始时每天要做的作业量都是 $0$。</p>
<p>接下来，红包会有 $q$ 个行为，每次都会选择一个红包的形状，把红包内的每一天的作业量增加一个奇怪的组合数。</p>
<p>详细地说，每个行为可以用 $v, u, k$ 表示：对所有的 $i, j$，若满足 $0 \leq i \leq j$ 且 $j \geq k$ 则将第 $v + i$ 周第 $u - i + j$ 天的作业量增加 ${j \choose i}$，即 $j$ 个里面选 $i$ 个的方案数（如果不存在这一天则不执行）。</p>
<p>在所有行为结束后，红包就计划好了每天要做的作业量。</p>
<p>虽然能不能完成是另一回事，但是现在请帮红包算出每天计划要做的作业量。</p>

# 输入格式


<p>由于本题输入数据很大，所以采取在程序内生成数据的方式。</p>
<p>有一个随机数产生器，有个内部变量 $x$ 初始时为 $x_0$，每次产生随机数时它会将 $x$ 变为 $(100000005x+20150823) \bmod 998244353$，然后返回 $\lfloor \frac{x}{100} \rfloor$。（$a \bmod b$ 表示 $a$ 除以 $b$ 的余数，该运算的优先级高于加减法。$\lfloor \alpha \rfloor$ 表示 $\alpha$ 向下取整后的结果。）</p>
<p>输入文件共一行，包含四个整数 $n, m, q, x_0$。保证 $n, m, q \geq 1$，$0 \leq x_0 &lt; 998244353$。</p>
<p>每次，你需要按顺序产生三个随机数 $\hat{v}, \hat{u}, \hat{k}$，然后令 $v = \hat{v} \bmod n + 1$，$u = \hat{u} \bmod m + 1$，$k = \hat{k} \bmod (n + m - v - u + 1)$，表示一个行为。你需要重复该过程 $q$ 次来获得所有行为的参数。</p>

# 输出格式


<p>共 $n$ 行，每行 $m$ 个整数，其中第 $i$ 行第 $j$ 个整数表示第 $i$ 周第 $j$ 天要做的作业量。你只用输出答案对 $998244353$ 取模后的结果。</p>

# 样例一


<h4>input</h4>
<pre>3 2 2 1234

</pre>

<h4>output</h4>
<pre>0 0
1 1
1 4

</pre>

<h4>explanation</h4>
<p>两次操作分别为：$(2, 1, 2)$ 和 $(2, 1, 0)$。</p>

# 样例二


<h4>input</h4>
<pre>10 10 20 5678

</pre>

<h4>output</h4>
<pre>0 0 0 0 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 0
0 0 0 0 0 0 0 0 0 1
0 0 0 0 0 0 0 0 6 7
0 0 0 0 0 0 0 16 22 30
0 0 0 0 1 1 26 42 72 104
0 1 2 3 4 30 56 126 198 1227
0 1 4 7 27 58 170 296 1293 4522
0 1 5 18 48 176 346 1153 5449 9971
0 1 7 28 133 309 895 5480 10929 20908

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n, m$ 的规模</th>
<th>$q$ 的规模</th>
</tr></thead><tbody><tr><td>1</td><td>$n, m \leq 10$</td><td>$q \leq 10$</td></tr><tr><td>2</td><td>$n, m \leq 100$</td><td>$q \leq 100$</td></tr><tr><td>3</td><td>$n, m \leq 30$</td><td rowspan="3">$q \leq 5 \times 10^6$</td></tr><tr><td>4</td><td rowspan="2">$n, m \leq 100$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5">$n, m \leq 300$</td><td rowspan="2">$q \leq 2 \times 10^6$</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$q \leq 5 \times 10^6$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=137">样例数据下载</a></p>
