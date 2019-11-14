# 题目描述

<p>在设计电路的过程中，常常要手动分析电路。</p>
<p>我们故事的主人公 —— 奸笑熊是一个参加了 NOI2015 结果遗憾退役的 OIer。</p>
<p>马上就要回班搞高考了，奸笑熊不免有点伤感。于是奸笑熊开始玩电路散散心。</p>
<p>奸笑熊的电路有 $n \times m$ 个节点，排成 $n$ 行 $m$ 列。任意两个相邻节点之间连着一条导线。如果两个节点 $(x_1, y_1), (x_2, y_2)$ 满足 $\lvert x_1 - x_2 \rvert + \lvert y_1 - y_2 \rvert = 1$ 则称这两个节点相邻。</p>
<p>奸笑熊定义一个电路的复杂程度为最大的非负整数 $s$ 满足可以选出 $s$ 个节点使得任意两个被选中的节点间都有一根导线相连。</p>
<p>奸笑熊手里还有 $r$ 根导线，可以连在 $r$ 对节点之间。奸笑熊希望新加上不超过 $r$ 根导线后，电路的复杂程度最大。</p>
<p>请你帮奸笑熊手动分析他的电路，告诉他复杂程度最大是多少。</p>

# 输入格式


<p>共一行，包含三个整数 $n, m, r$。保证 $n, m \geq 1$，$r \geq 0$。</p>

# 输出格式


<p>共一行，包含一个整数表示答案。</p>
<p>C/C++ 输入输出 long long 时请用 <code>%lld</code>。C++ 可以直接使用 cin/cout 输入输出。</p>

# 样例一


<h4>input</h4>
<pre>2 2 0

</pre>

<h4>output</h4>
<pre>2

</pre>

<h4>explanation</h4>
<p>不能加导线。所以只能选择两个相邻的节点，复杂程度为 $2$。</p>

# 样例二


<h4>input</h4>
<pre>2 3 3

</pre>

<h4>output</h4>
<pre>4

</pre>


# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n, m$ 的规模</th><th>$r$ 的规模</th></tr></thead><tbody><tr><td>1</td><td rowspan="3">$n, m \leq 4$</td><td rowspan="3">$r \leq 13$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="2">$n = 1, m \leq 10^9$</td><td rowspan="7">$r \leq 10^{18}$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="2">$n, m \leq 1000$</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3">$n, m \leq 10^9$</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=133">样例数据下载</a></p>
