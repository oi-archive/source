# 题目描述

<p>一年一度的“跳石头”比赛又要开始了！</p>
<p>这项比赛将在一条笔直的河道中进行，河道中分布着一些巨大岩石。组委会已经选择好了两块岩石作为比赛起点和终点。在起点和终点之间，有 $N$ 块岩石（不含起点和终点的岩石）。在比赛过程中，选手们将从起点出发，每一步跳向相邻的岩石，直至到达终点。</p>
<p>为了提高比赛难度，组委会计划移走一些岩石，使得选手们在比赛过程中的最短跳跃距离尽可能长。由于预算限制，组委会至多从起点和终点之间移走 $M$ 块岩石（不能移走起点和终点的岩石）。</p>

# 输入格式


<p>输入文件第一行包含三个整数 $L,N,M$，分别表示起点到终点的距离，起点和终点之间的岩石数，以及组委会至多移走的岩石数。保证 $L \geq 1$ 且 $N \geq M \geq 0$。</p>
<p>接下来 $N$ 行，每行一个整数，第 $i$ 行的整数 $D_i（ 0 &lt; D_i &lt; L）$， 表示第 $i$ 块岩石与起点的距离。这些岩石按与起点距离从小到大的顺序给出，且不会有两个岩石出现在同一个位置。</p>

# 输出格式


<p>输出文件只包含一个整数，即最短跳跃距离的最大值。</p>

# 样例一


<h4>input</h4>
<pre>25 5 2
2
11
14
17
21

</pre>

<h4>output</h4>
<pre>4

</pre>

<h4>explanation</h4>
<p>将与起点距离为 $2$ 和 $14$ 的两个岩石移走后，最短的跳跃距离为 $4$（从与起点距离 $17$ 的岩石跳到距离 $21$ 的岩石，或者从距离 $21$ 的岩石跳到终点）。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n,m$的规模</th>
<th>$L$的规模</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$n,m \leq 10$</td><td rowspan="10"> $L \leq 10^9$</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="3">$n,m \leq 100$</td></tr><tr><td>4</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5">$n,m \leq 50000$</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>


<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$128\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=148">样例数据下载</a></p>
