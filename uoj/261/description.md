# 题目描述

<p>小C同学认为跑步非常有趣，于是决定制作一款叫做《天天爱跑步》的游戏。《天天爱跑步》是一个养成类游戏，需要玩家每天按时上线，完成打卡任务。</p>
<p>这个游戏的地图可以看作一棵包含 $n$ 个结点和 $n-1$ 条边的树，每条边连接两个结点，且任意两个结点存在一条路径互相可达。树上结点编号为从 $1$ 到 $n$ 的连续正整数。</p>
<p>现在有 $m$ 个玩家，第 $i$ 个玩家的起点为 $S_i$，终点为 $T_i$。每天打卡任务开始时，所有玩家<strong>在第 $0$ 秒</strong>同时从<strong>自己的起点</strong>出发，以<strong>每秒跑一条边</strong>的速度，不间断地沿着最短路径向着<strong>自己的终点</strong>跑去，跑到终点后该玩家就算完成了打卡任务。（由于地图是一棵树，所以每个人的路径是唯一的）</p>
<p>小C想知道游戏的活跃度，所以在每个结点上都放置了一个观察员。在结点 $j$ 的观察员会选择在第 $W_j$ 秒观察玩家，一个玩家能被这个观察员观察到当且仅当该玩家在第 $W_j$ 秒也<strong>正好</strong>到达了结点 $j$。小C想知道每个观察员会观察到多少人？</p>
<p><strong>注意：</strong>我们认为一个玩家到达自己的终点后该玩家就会结束游戏，他不能等待一段时间后再被观察员观察到。即对于把结点 $j$ 作为终点的玩家：若他在第 $W_j$ 秒<strong>前</strong>到达终点，则在结点 $j$ 的观察员<strong>不能观察到</strong>该玩家；若他<strong>正好</strong>在第 $W_j$ 秒到达终点，则在结点 $j$ 的观察员<strong>可以观察到</strong>这个玩家。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行有两个整数 $n$ 和 $m$。其中 $n$ 代表树的结点数量，同时也是观察员的数量，$m$ 代表玩家的数量。</p>
<p>接下来 $n-1$ 行每行两个整数 $u$ 和 $v$，表示结点 $u$ 到结点 $v$ 有一条边。</p>
<p>接下来一行 $n$ 个整数，其中第 $j$ 个整数为 $W_j$，表示结点 $j$ 出现观察员的时间。</p>
<p>接下来 $m$ 行，每行两个整数 $S_i$ 和 $T_i$，表示一个玩家的起点和终点。</p>
<p>对于所有的数据，保证 $1 \leq S_i, T_i \leq n$，$0 \leq W_j \leq n$。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出 $1$ 行 $n$ 个整数，第 $j$ 个整数表示结点 $j$ 的观察员可以观察到多少人。</p>

# 样例一


<h4>input</h4>
<pre>6 3
2 3
1 2
1 4
4 5
4 6
0 2 5 1 2 3
1 5
1 3
2 6

</pre>


<h4>output</h4>
<pre>2 0 0 1 1 1

</pre>

<h4>explanation</h4>
<p>对于 $1$ 号点，$W_1=0$，故只有起点为 $1$ 号点的玩家才会被观察到，所以玩家 $1$ 和玩家 $2$ 被观察到，共 $2$ 人被观察到。</p>
<p>对于 $2$ 号点，没有玩家在第 $2$ 秒时在此结点，共 $0$ 人被观察到。</p>
<p>对于 $3$ 号点，没有玩家在第 $5$ 秒时在此结点，共 $0$ 人被观察到。</p>
<p>对于 $4$ 号点，玩家 $1$ 被观察到，共 $1$ 人被观察到。</p>
<p>对于 $5$ 号点，玩家 $1$ 被观察到，共 $1$ 人被观察到。</p>
<p>对于 $6$ 号点，玩家 $3$ 被观察到，共 $1$ 人被观察到。</p>

# 样例二


<h4>input</h4>
<pre>5 3
1 2
2 3
2 4
1 5
0 1 0 3 0
3 1
1 4
5 5

</pre>

<h4>output</h4>
<pre>1 2 1 0 1

</pre>


# 限制与约定


<p>每个测试点的数据规模及特点如下表所示。提示：数据范围的个位上的数字可以帮助判断是哪一种数据类型。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n$</th><th rowspan="1">$m$</th><th rowspan="1">约定</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="2">$=991$</td><td rowspan="2">$=991$</td><td rowspan="2">所有人的起点等于自己的终点，即 $S_i = T_i$</td></tr><tr><td rowspan="1">2</td></tr><tr><td rowspan="1">3</td><td rowspan="2">$=992$</td><td rowspan="2">$=992$</td><td rowspan="2">$W_j=0$</td></tr><tr><td rowspan="1">4</td></tr><tr><td rowspan="1">5</td><td rowspan="1">$=993$</td><td rowspan="1">$=993$</td><td rowspan="1">无</td></tr><tr><td rowspan="1">6</td><td rowspan="3">$=99994$</td><td rowspan="3">$=99994$</td><td rowspan="3">树退化成一条链，其中 $1$ 与 $2$ 有边，$2$ 与 $3$ 有边，$\dots$，$n-1$ 与 $n$ 有边</td></tr><tr><td rowspan="1">7</td></tr><tr><td rowspan="1">8</td></tr><tr><td rowspan="1">9</td><td rowspan="4">$=99995$</td><td rowspan="4">$=99995$</td><td rowspan="4">所有的 $S_i=1$</td></tr><tr><td rowspan="1">10</td></tr><tr><td rowspan="1">11</td></tr><tr><td rowspan="1">12</td></tr><tr><td rowspan="1">13</td><td rowspan="4">$=99996$</td><td rowspan="4">$=99996$</td><td rowspan="4">所有的 $T_i=1$</td></tr><tr><td rowspan="1">14</td></tr><tr><td rowspan="1">15</td></tr><tr><td rowspan="1">16</td></tr><tr><td rowspan="1">17</td><td rowspan="3">$=99997$</td><td rowspan="3">$=99997$</td><td rowspan="4">无</td></tr><tr><td rowspan="1">18</td></tr><tr><td rowspan="1">19</td></tr><tr><td rowspan="1">20</td><td rowspan="1">$=299998$</td><td rowspan="1">$=299998$</td></tr></tbody></table></div>


<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=261">样例数据下载</a></p>
