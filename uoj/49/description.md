# 题目描述

<p>顽皮的小O潜入了著名核物理专家 Picks 的研究所，走进了存放浓缩铀的仓库。</p>
<p>浓缩铀存放在一个个箱子里，一共有 $n$ 叠箱子排成一条直线，不妨想象一根数轴，第 $i$ 叠箱子坐标为 $x_i$，竖直方向叠着 $a_i$ 个箱子。</p>
<p>小O脑洞大开，决定进行一项游戏。他会先选择一个整数坐标 $s$（可以不和任意一个 $x_i$ 相等），然后初始时他两手空空站在坐标 $s$ 处，进行至多 $t$ 秒的行动。</p>
<p>这段时间内他的行动方式包括：</p>
<ol><li>向左移动单位 $1$ 的距离，花费 $1$ 秒。</li>
<li>向右移动单位 $1$ 的距离，花费 $1$ 秒。</li>
<li>如果现在手上是空的，那么可以从当前位置拿起一个装有浓缩铀的箱子，瞬间完成。</li>
<li>如果现在拿着一个装有浓缩铀的箱子，那么可以把这个箱子放在当前位置所有箱子的顶部，瞬间完成。</li>
</ol><p>由于小O很小，任意时刻他只能拿着至多一个箱子。他希望进行至多 $t$ 秒的行动后，初始位置 $s$ 叠着的箱子尽量多。</p>
<p>请你帮小O计算，他如果 $s$ 选择得恰到好处，并且行动足够机智，那么最多能在位置 $s$ 叠放多少个箱子。</p>
<p>（PS：危险动作，请勿模仿。）</p>

# 输入格式


<p>第一行两个整数 $n, t$。保证 $n \geq 1, t \geq 0$。</p>
<p>第二行 $n$ 个严格递增的正整数，第 $i$ 个为 $x_i$。</p>
<p>第三行 $n$ 个正整数，第 $i$ 个为 $a_i$。</p>

# 输出格式


<p>一行一个非负整数，表示位置 $s$ 至多能叠放多少个箱子。</p>
<p>C/C++ 输入输出 long long 时请用 <code>%lld</code>。C++ 可以直接使用 cin/cout 输入输出。</p>

# 样例一


<h4>input</h4>
<pre>2 3
1 2
2 3

</pre>

<h4>output</h4>
<pre>4

</pre>


# 样例二


<h4>input</h4>
<pre>9 15
2 3 5 7 11 13 17 23 29
4 5 4 1 2 4 6 1 3

</pre>

<h4>output</h4>
<pre>10

</pre>


# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>数据规模</th>
<th>特殊限制</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="3">$n \le 100$，$t \le 1000$</td><td rowspan="3">$x_i \leq 1000$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="5">$n \le 10^5$，$t \le 10^{18}$</td><td rowspan="2">$a_i = 1$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="2">$x_i=i$</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">\</td></tr><tr><td>9</td><td rowspan="2">$n \le 5 \times 10^5$，$t \le 10^{18}$</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于全部数据，均有 $1 \le a_i \le 10^4$，$1 \le x_i \le 10^9$，且输入时 $x_i$ 严格递增。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=49">样例数据下载</a></p>
