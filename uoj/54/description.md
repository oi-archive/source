# 题目描述

<p>小 X 驾驶着他的飞船准备穿梭过一个 $n$ 维空间，这个空间里每个点的坐标可以用 $n$ 个实数表示，即 $(x_1, x_2, \dots, x_n)$。</p>
<p>为了穿过这个空间，小 X 需要在这个空间中选取 $c$（$c \geq 2$）个点作为飞船停留的地方，而这些点需要满足以下三个条件：</p>
<ol><li>每个点的每一维坐标均为正整数，且第 $i$ 维坐标不超过 $m_i$。</li>
<li>第 $i + 1$（$1 \leq i &lt; c$）个点的第 $j$（$1 \leq j \leq n$）维坐标必须严格大于第 $i$ 个点的第 $j$ 维坐标。</li>
<li>存在一条直线经过所选的所有点。在这个 $n$ 维空间里，一条直线可以用 $2n$ 个实数 $p_1, p_2, \dots, p_n, v_1, v_2, \dots, v_n$ 表示。直线经过点 $(x_1, x_2, \dots, x_n)$，当且仅当存在实数 $t$，使得对 $i = 1 \dots n$ 均满足 $x_i = p_i + tv_i$。</li>
</ol><p>小 X 还没有确定他的最终方案，请你帮他计算一下一共有多少种不同的方案满足他的要求。由于答案可能会很大，你只需要输出答案 $\bmod 10007$ 后的值。</p>

# 输入格式


<p>第一行包含一个正整数 $T$，表示有 $T$ 组数据需要求解。</p>
<p>每组数据包含两行，第一行包含两个正整数 $n, c$（$c \geq 2$），分别表示空间的维数和需要选择的暂停点的个数。</p>
<p>第二行包含 $n$ 个正整数，依次表示 $m_1, m_2, \dots, m_n$。</p>

# 输出格式


<p>共 $T$ 行，每行包含一个非负整数，依次对应每组数据的答案。</p>

# 样例一


<h4>input</h4>
<pre>3
2 3
3 4
3 3
3 4 4
4 4
5 9 7 8

</pre>

<h4>output</h4>
<pre>2
4
846

</pre>

<h4>explanation</h4>
<p>对于第一组数据，共有两种可行的方案：一种选择 $(1, 1), (2, 2), (3, 3)$，另一种选择 $(1, 2), (2, 3), (3, 4)$。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$T$</th><th>$n$</th><th>$c$</th><th>$m_i$</th></tr></thead><tbody><tr><td>1</td><td>$= 1000$</td><td>$= 1$</td><td>$\leq 20$</td><td>$\leq 100000$</td></tr><tr><td>2</td><td>$= 3$</td><td>$\leq 4$</td><td>$\leq 20$</td><td>$\leq 30$</td></tr><tr><td>3</td><td>$= 3$</td><td>$= 2$</td><td>$= 3$</td><td>$\leq 100000$</td></tr><tr><td>4</td><td>$= 1000$</td><td>$= 2$</td><td>$= 3$</td><td>$\leq 100000$</td></tr><tr><td>5</td><td>$= 20$</td><td>$\leq 5$</td><td>$= 3$</td><td>$\leq 100000$</td></tr><tr><td>6</td><td>$= 100$</td><td>$\leq 11$</td><td>$= 3$</td><td>$\leq 100000$</td></tr><tr><td>7</td><td>$= 1$</td><td>$\leq 5$</td><td>$\leq 20$</td><td>$\leq 100000$</td></tr><tr><td>8</td><td>$= 20$</td><td>$\leq 5$</td><td>$\leq 20$</td><td>$\leq 100000$</td></tr><tr><td>9</td><td>$= 100$</td><td>$\leq 11$</td><td>$\leq 20$</td><td>$\leq 100000$</td></tr><tr><td>10</td><td>$= 100$</td><td>$\leq 11$</td><td>$\leq 20$</td><td>$\leq 100000$</td></tr></tbody></table></div>


<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=54">样例数据下载</a></p>
