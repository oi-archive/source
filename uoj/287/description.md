# 题目描述

<p>小 Z 在一块棋盘上玩游戏。这块棋盘是一个由 $n$ 个顶点和 $m$ 条边组成的无向连通图，图上的顶点编号为 $[1,n]$ 中的正整数。游戏开始时，每个顶点上都放有一个棋子，每个棋子上有一个 $[0,n-1]$ 中的整数，表示棋子的编号。不同棋子的编号互不相同。</p>
<p>每次操作时，小 Z 需要先选择棋盘上的一条边，这条边的一个端点此时放有 $0$ 号棋子。然后，小 Z 将这条边两个端点上的棋子交换。</p>
<p>现在你已经知道棋盘的模样，以及初始状态下每个顶点上的棋子编号。小Z想请你回答 $q$ 个询问。每个询问指定了棋盘的目标状态，你需要回答能否通过若干次操作，将棋盘由初始状态变为这个目标状态。</p>

# 输入格式


<p>第一行输入三个正整数 $n,m,q$，分别表示图中的顶点数、边数，以及询问的个数。</p>
<p>接下来 $m$ 行，每行两个整数 $u,v (1\leq u,v\leq n)$ ，表示图中有一条连接 $u,v$ 两顶点的无向边。保证 $u \neq v$ ，即图中不存在自环。保证给出的图是连通图，即任意两个顶点都可以经过若干条边而相互到达。</p>
<p>接下来一行有 $n$ 个空格隔开的整数，其中第 $i$ 个整数表示初始状态下 $i$ 号顶点上的棋子的编号，保证编号都为 $[0,n-1]$ 中的整数，且两两不同。</p>
<p>接下来 $q$ 行，每行有 $n$ 个空格隔开的整数，表示一个询问，其中第 $i$ 个整数表示目标状态中第 $i$ 号顶点上的棋子的编号，保证编号都为 $[0,n-1]$ 中的整数，且两两不同。</p>

# 输出格式


<p>输出 $q$ 行，每行一个字符串 “Yes” 或者 “No”（不含引号）作为回答。“Yes” 表示从棋子的初始状态可以经过若干次操作而达到询问中所指定的目标状态，“No” 表示不存在这样的操作步骤。注意：“Yes” 和 “No” 的首字母都是大写的。</p>

# 样例一


<h4>input</h4>
<pre>5 6 3
2 1
4 5
3 5
3 4
2 3
1 3
1 2 3 4 0
0 1 2 3 4
2 1 0 4 3
4 3 0 1 2

</pre>

<h4>output</h4>
<pre>Yes
Yes
No

</pre>

<h4>explanation</h4>
<p>棋盘如下图所示：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/287/sample.jpg" alt="样例" style="width:300px;"/></p>
<p>对于第一组询问，只要将 $0$ 号点沿着 $5-4-3-2-1$ 的路径移动。对于第二组询问，将 $0$ 号点沿着$5-3-1-2-3$移动。对于第三组询问是无解的。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>本题共有 20 个测试点。</p>
<p>对于每个测试点，只有当你的输出与标准输出完全相同时，才能得到该测试点的满分。</p>
<p>下表为各个测试点的数据范围和约定。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>数据特性</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$\leq 8$</td><td rowspan="2">$\leq 15$</td><td rowspan="4">无</td></tr><tr><td>2</td></tr><tr><td>3</td><td rowspan="18">$\leq 50$</td><td rowspan="2">$= n - 1$</td></tr><tr><td>4</td></tr><tr><td>5</td><td rowspan="4">$=n$</td><td rowspan="2">特性 1</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="2">无</td></tr><tr><td>8</td></tr><tr><td>9</td><td rowspan="12">$\le 100$</td><td rowspan="2">特性 2</td></tr><tr><td>10</td></tr><tr><td>11</td><td rowspan="3">特性 3</td></tr><tr><td>12</td></tr><tr><td>13</td></tr><tr><td>14</td><td rowspan="7">无</td></tr><tr><td>15</td></tr><tr><td>16</td></tr><tr><td>17</td></tr><tr><td>18</td></tr><tr><td>19</td></tr><tr><td>20</td></tr></tbody></table></div>

<p>$1\le q\le 1000$</p>
<p>特性 1：所有顶点的度数均为 $2$。</p>
<p>特性 2：这个棋盘可以绘制在一个$k \times k$ 的矩形网格图上。其中 $k \times k = n$ 且 $2k \times (k-1) = m$。</p>
<p>特性 3：每条边至多属于一个简单环。</p>
<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$1\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=287">样例数据下载</a></p>
