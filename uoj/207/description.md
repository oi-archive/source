# 题目描述

<p>火车司机出秦川，跳蚤国王下江南，共价大爷游长沙。每个周末，勤劳的共价大爷都会开车游历长沙市。</p>
<p>长沙市的交通线路可以抽象成为一个 $n$ 个点 $n-1$ 条边的无向图，点编号为 $1$ 到 $n$，任意两点间均存在<strong>恰好</strong>一条路径，显然两个点之间最多也只会有一条边相连。有一个包含一些点对 $(x,y)$ 的<strong>可重</strong>集合S，共价大爷的旅行路线是这样确定的：<strong>每次他会选择 $S$ 中的某一对点 $(x,y)$，并从 $x$ 出发沿着唯一路径到达 $y$。</strong></p>
<p>小L是共价大爷的脑残粉，为了见到共价大爷的尊容，小L决定守在这张图的某条边上等待共价大爷的到来。为了保证一定能见到他，<strong>显然小L必须选择共价大爷一定会经过的边——也就是所有共价大爷可能选择的路径都经过的边。</strong></p>
<p>现在小L想知道，如果他守在某一条边，是否一定能见到共价大爷。</p>
<p>然而长沙市总是不断的施工，也就是说，<strong>可能某个时刻某条边会断开，同时这个时刻一定也有某条新边会出现，且任意时刻图都满足任意两点间均存在恰好一条路径的条件。</strong>注意断开的边有可能和加入的新边连接着相同的两个端点。共价大爷的兴趣也会不断变化，<strong>所以S也会不断加入新点对或者删除原有的点对。</strong>当然，<strong>小L也有可能在任何时候向你提出守在某一条边是否一定能见到共价大爷的问题。你能回答小L的所有问题吗？</strong></p>

# 输入格式


<p>输入的第一行包含一个整数 $\mathrm{id}$，表示测试数据编号，如第一组数据的$\mathrm{id} = 1$，样例数据的 $\mathrm{id}$ 可以忽略。<strong>hack数据中的 $\mathrm{id}$必须为 $0$ 到 $10$ 之间的整数。hack数据中$\mathrm{id}$的值和数据类型没有任何关系。</strong></p>
<p>输入的第二行包含两个整数 $n, m$，分别表示图中的点数，以及接下来会发生的事件数，事件的定义下文中会有描述。初始时 $S$ 为空。</p>
<p>接下来 $n - 1$ 行，每行两个正整数 $x, y$，表示点 $x$ 和点 $y$ 之间有一条无向边。</p>
<p>接下来 $m$ 行，每行描述一个事件，每行的第一个数 $\mathrm{type}$ 表示事件的类型。</p>
<p>若$\mathrm{type} = 1$，那么接下来有四个正整数$x, y, u, v$，表示先删除连接点$x$和点$y$的无向边，保证存在这样的无向边，然后加入一条连接点$u$和点$v$的无向边，保证操作后的图仍然满足题中所述条件。</p>
<p>若$\mathrm{type} = 2$，那么接下来有两个正整数 $x, y$，表示在 $S$ 中加入点对 $(x, y)$。</p>
<p>若$\mathrm{type} = 3$，那么接下来有一个正整数 $x$，表示删除第 $x$ 个加入 $S$ 中的点对，即在第 $x$ 个 $\mathrm{type} = 2$ 的事件中加入 $S$ 中的点对，保证这个点对存在且仍然在 $S$ 中。</p>
<p>若 $\mathrm{type} = 4$，那么接下来有两个正整数 $x, y$，表示小L询问守在连接点 $x$ 和点 $y$ 的边上是否一定能见到共价大爷，保证存在这样的无向边且此时 $S$ 不为空。</p>

# 输出格式


<p>对于每个小L的询问，输出“<samp>YES</samp>”或者“<samp>NO</samp>”（均不含引号）表示小L一定能或者不一定能见到共价大爷。</p>

# 样例一


<h4>input</h4>
<pre>0
5 7
1 2
1 3
2 4
1 5
2 1 5
1 1 5 2 5
4 2 5
2 1 4
4 2 5
3 1
4 2 4

</pre>

<h4>output</h4>
<pre>YES
NO
YES

</pre>


# explanation


<p>最开始将点对 $(1,5)$ 加入到 $S$ 中，此时点 $1$ 和点 $5$ 之间的路径是 $1 \rightarrow 5$。</p>
<p>接着将连接点 $1$ 和点 $5$ 的边断开，加入连接点 $2$ 和点 $5$ 的边，我们发现图仍然满足题中所述条件，且点 $1$ 和点 $5$ 之间的路径是 $1 \rightarrow 2 \rightarrow 5$，经过点了 $2$ 和点 $5$ 之间的边，因此第一个询问答案是 <samp>YES</samp>。</p>
<p>接着将点对 $(1,4)$ 加入到 $S$ 中，点 $1$ 和点 $4$ 之间的路径是 $1 \rightarrow 2 \rightarrow 4$，没有经过点 $2$ 和点 $5$ 之间的边，因此第二个询问答案是 <samp>NO</samp>。</p>
<p>接着，我们删除了第一个加入到 $S$ 中的点对，也就是点对 $(1,5)$，此时 $S$ 中唯一的点对就是 $(1,4)$，经过了点 $2$ 和点 $4$ 之间的边，因此最后一个询问答案是 <samp>YES</samp>。</p>

# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。这组数据中 $\mathrm{type} \ne 1$。</p>

# 限制与约定


<p>每组测试数据的限制与约定如下所示：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>$\mathrm{type}=$</th>
<th>限制与约定</th>
</tr></thead><tbody><tr><td>1</td><td>$n \le 100$</td><td>$m \le 100$</td><td>$1,2,3,4$</td><td rowspan="5"></td></tr><tr><td>2</td><td rowspan="9">$n \le 100000$</td><td rowspan="9">$m \le 300000$</td><td rowspan="2">$2,4$</td></tr><tr><td>3</td>
</tr><tr><td>4</td><td rowspan="2">$2,3,4$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5">$1,2,3,4$</td><td rowspan="2">任意时刻 $|S| \le 10$</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3"></td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 来源


<p>matthew99</p>

# 题解


<p><a href="https://matthew99.blog.uoj.ac/blog/1771">https://matthew99.blog.uoj.ac/blog/1771</a></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=207">样例数据下载</a></p>
