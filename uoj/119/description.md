# 题目描述

<p>数学考试，一道圆锥曲线的题难住了你，你开始疯狂地笔算。但是，这题实在太难，于是你决定每种思路多尝试尝试。</p>
<p>你的思维过程可以转化为如下过程：</p>
<ul><li>有一个随机数产生器，有个内部变量 $x$ 初始时为 $x_0$，每次产生随机数时它会将 $x$ 变为 $(100000005x+20150609) \bmod 998244353$，然后返回 $\lfloor \frac{x}{100} \rfloor$。（$a \bmod b$ 表示 $a$ 除以 $b$ 的余数，该运算的优先级高于加减法。$\lfloor \alpha \rfloor$ 表示 $\alpha$ 向下取整后的结果。）</li>
<li>初始时有 $n$ 个点，分别编号为 $1, \dots, n$，按编号从小到大顺序生成第 $i$ 个点的坐标：<ul><li>把横坐标赋为 $i$。</li>
<li>产生一个随机数 $\hat{y}$，把纵坐标赋为 $\hat{y} \bmod 100001$。</li>
</ul></li>
<li>有 $m$ 个操作，表示你的思路过程。操作共有三种：<ul><li><samp>C</samp>：按顺序产生随机数 $\hat{p}, \hat{y}$，令 $p = \hat{p} \bmod n + 1, y = \hat{y} \bmod 100001$，然后把第 $p$ 个点的纵坐标修改为 $y$。</li>
<li><samp>R</samp>：按顺序产生随机数 $\hat{p}, \hat{q}$，令 $p = \min\{\hat{p} \bmod n + 1, \hat{q} \bmod n + 1\}, q = \max\{\hat{p} \bmod n + 1, \hat{q} \bmod n + 1\}$，把编号大于等于 $p$ 小于等于 $q$ 的点的纵坐标 $y$ 改为 $100000 - y$。</li>
<li><samp>Q $a$ $b$ $c$</samp>：查询操作。按顺序产生随机数 $\hat{p}, \hat{q}$，令 $p = \min\{\hat{p} \bmod n + 1, \hat{q} \bmod n + 1\}, q = \max\{\hat{p} \bmod n + 1, \hat{q} \bmod n + 1\}$，求最小的整数 $t$ 使得：对于所有编号大于等于 $p$ 小于等于 $q$ 的点 $(x, y)$ 都满足 $ax + by + cxy \leq t$。（$a, b, c$ 均为非负整数）</li>
</ul></li>
</ul>
# 输入格式


<p>第一行三个整数 $n, m, x_0$。保证 $n, m \geq 1$，$0 \leq x_0 &lt; 998244353$ 且 $x_0 \neq 340787122$。</p>
<p>接下来 $m$ 行，每行表示一个操作，格式如前所述。</p>

# 输出格式


<p>对于每个查询操作输出一个整数表示最小的 $t$。</p>

# 样例一


<h4>input</h4>
<pre>3 3 2705443
C
R
Q 872784 195599 7

</pre>

<h4>output</h4>
<pre>13035048532

</pre>

<h4>explanation</h4>
<p>最开始三个点的坐标分别是 $(1,91263),(2,33372),(3,10601)$。</p>
<p>第一个操作把第三个点的坐标改成了 $(3,94317)$。</p>
<p>第二个操作修改了区间 $[2,3]$，第二个点变成了 $(2,66628)$，第三个点变成了 $(3,5683)$。</p>
<p>最后一个操作询问区间 $[2,3]$，可以发现最小的 $t$ 是 $13035048532$。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>所有数据中，对于所有查询操作保证 $0 \leq a, b &lt; 10^6$，$0 \leq c &lt; 40$，<strong>保证查询操作的出现次数不超过 $10^5$</strong>。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
<th>$m$的规模</th>
<th>特殊限制</th>
</tr></thead><tbody><tr><td>1</td><td>$n \leq 100$</td><td>$m \leq 100$</td><td>无</td></tr><tr><td>2</td><td rowspan="2">$n \leq 10^5$</td><td rowspan="2">$m \leq 10^6$</td><td rowspan="2">所有查询操作中 $a = c = 0$</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="2">$n \leq 10^5$</td><td rowspan="2">$m \leq 2 \times 10^5$</td><td rowspan="2">所有查询操作中 $c = 0$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="2">$n \leq 10^5$</td><td rowspan="2">$m \leq 2 \times 10^5$</td><td rowspan="2">无</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$n \leq 10^5$</td><td rowspan="3">$m \leq 10^6$</td><td rowspan="3">无</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=119">样例数据下载</a></p>
