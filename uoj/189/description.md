# 题目描述

<p>火车司机出秦川，跳蚤国王下江南。每天，勤劳的火车司机们都会开着自己心爱的火车去传播福音。</p>
<p>和跳蚤国类似，火车国也有 $n$ 个城市编号为 $1$ 到 $n$，城市之间有一些铁路相连。这些铁路构成了一个仙人掌。如果一个无向连通图的任意一条边最多属于一个简单环，我们就称之为仙人掌。所谓简单环即不经过重复的结点的环。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/utility/what-is-cactus.png" alt="什么是仙人掌"/></p>
<p>第 $i$ 天会有 $k_i$ 名火车司机出秦川，第 $j$ 名司机会从城市 $s_j$ 到 $t_j$。有一些司机是老司机，他们会沿着选择经过城市最多的路径走，显示自己高超的驾驶技术。而另一些是新司机，他们会走经过城市最少的路径。但不管是新司机还是老司机，都不会走过同一个城市两次（也就是选择的路径都是简单路径）。</p>
<p>每一条铁路周围都有一些人居住，如果第 $i$ 天这条铁路被火车司机经过，这些人会收到福音。我们想知道每天有多少人收到福音。</p>
<p>当然人口是会变化的，第 $i$ 天结束以后第 $w_i$ 铁路的人口会改变为 $x_i$。</p>

# 输入格式


<p>第一行三个整数 $n,m$ 和 $q$，表示有 $n$ 个城市，有 $m$ 条铁路以及有 $q$ 天。</p>
<p>接下来 $m$ 行每行三个整数 $u,v,w$，表示一条连接 $u$ 和 $v$ 的铁路，铁路周围有 $w$ 个人。保证是仙人掌，没有自环，每个环的长度都是奇数。铁路编号从 $1$ 开始。</p>
<p>接下来 $2q$ 行，每两行表示一天。</p>
<p>第一行一个整数 $k_i$ 表示有 $k_i$ 名司机（ $k_i$ 可能为 $0$ ，这时候请忽略这个询问并输出 $0$ ），然后是 $3k_i$ 个整数 $s_j,t_j,type_j$，分别表示每个司机的起点和终点和类型，如果 $type_j$ 是 $0$ 表示是新司机，为 $1$ 是老司机。每个司机的起点和终点均不同。</p>
<p>第二行两个整数 $w_i$ 和 $x_i$，表示第 $w_i$ 条铁路的人口会改变为 $x_i$ ，如果 $w_i$ 为 $0$ 则表示没有修改。</p>

# 输出格式


<p>$q$ 行，每行一个整数表示这一天收到福音的人数。</p>

# 样例一


<h4>input</h4>
<pre>11 13 3
1 2 1
2 3 2
1 3 4
2 8 8
2 9 16
9 10 32
10 11 64
11 9 128
3 4 256
3 5 512
4 7 1024
7 6 2048
5 6 4096
1 10 7 1
3 8192
3 8 1 1 2 7 1 10 4 0
7 16384
3 8 1 0 2 7 0 10 4 1
0 16384

</pre>

<h4>output</h4>
<pre>6869
15163
32667

</pre>



# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>保证任意时刻边长和都属于int范围内。边长均为正整数。</p>
<p>$2 \leq n \leq 300000$， $n-1 \leq m \leq 2n-2,q \leq 300000$，令 $S = \sum k_i$， $S&lt;=300000$。</p>
<p>具体数据范围见下表：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>数据编号</th>
<th>$n$ 的规模</th>
<th>$q$ 的规模</th>
<th>$S$ 的规模</th>
<th>其他</th>
</tr></thead><tbody><tr><td>1</td><td>$n = 2$</td><td>$q \leq 10$</td><td>$S \leq 10$</td><td rowspan="2">无</td></tr><tr><td>2</td><td>$n = 100$</td><td>$q \leq 100$</td><td>$S \leq 100$</td></tr><tr><td>3</td><td rowspan="2">$n = 100000$</td><td rowspan="2">$q \leq 100000$</td><td rowspan="2">$S \leq 100000$</td><td>$m=n-1$，没有修改</td></tr><tr><td>4</td><td>$m=n-1$</td></tr><tr><td>5</td><td rowspan="2">$n = 300000$</td><td rowspan="2">$q \leq 300000$</td><td rowspan="2">$S \leq 300000$</td><td>$m=n-1$，没有修改</td></tr><tr><td>6</td><td>$m=n-1$</td></tr><tr><td>7</td><td rowspan="2">$n = 100000$</td><td rowspan="2">$q \leq 100000$</td><td rowspan="2">$S \leq 100000$</td><td>没有修改</td></tr><tr><td>8</td><td>无</td></tr><tr><td>9</td><td rowspan="2">$n = 300000$</td><td rowspan="2">$q \leq 300000$</td><td rowspan="2">$S \leq 300000$</td><td>没有修改</td></tr><tr><td>10</td><td>无</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$5\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=189">样例数据下载</a></p>

# IOI赛制


<p>本题在考试时排行榜上显示的成绩即为最终评测结果。</p>
