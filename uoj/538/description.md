# 题目描述

<p>Kenan 为沿着巴库大街某一侧的建筑和天桥绘制了一张规划图。规划图中有 $n$ 栋建筑，从 $0$ 到 $n-1$ 编号。还有 $m$ 座天桥，从 $0$ 到 $m-1$ 编号。这张规划图绘制在一张二维平面上，其中建筑和天桥分别是垂直和水平的线段。</p>
<p>第 $i$ 栋建筑的底部坐落在坐标 $(x_i,0)$ 上，建筑的高度为 $h_i$ 。因此，它对应一条连接点 $(x_i,0)$ 和 $(x_i,h_i)$ 的线段。</p>
<p>第 $i$ 座天桥的两端分别在第 $l_i$ 栋建筑和第 $r_i$ 栋建筑上 $(l_i \le r_i)$，并具有正的 $y_i$ 坐标 。因此，它对应一条连接点 $(x_{l_i},y_i)$ 和 $(x_{r_i},y_{i})$ 的线段。</p>
<p>称某座天桥和某栋建筑相交，如果它们有某个公共的点。因此，一座天桥在它的两个端点处与两栋建筑相交，同时还可能在中间和其他建筑相交。</p>
<p>Kenan 想要找出从第 $s$ 栋建筑的底部到第 $g$ 栋建筑的底部的最短路径长度，或者确认这样的路径不存在。在这里行人只能沿着建筑和天桥行走，并且不允许在地面上行走，也就是说不允许沿着 $y$ 坐标为 $0$ 的水平线行走。</p>
<p>行人能够在任意交点从某座天桥走进某栋建筑，或者从某栋建筑走上某座天桥。如果两座天桥的端点之一在同一点上，行人也可以从其中一座天桥走上另一座天桥。</p>
<p>你的任务是帮助 Kenan 回答他的问题。</p>

# 输入格式


<p>第一行两个整数 $n,m$，表示建筑的栋数和天桥的座数。</p>
<p>以下 $n$ 行，第 $i$ 行两个整数 $x_{i-1},h_{i-1}$，表示第 $i-1$ 栋建筑坐标和高度。</p>
<p>以下 $m$ 行，第 $i$ 行三个整数 $l_{i-1},r_{i-1},y_{i-1}$，表示第 $i-1$ 座天桥的左右端点和 $y$ 坐标。</p>
<p>最后一行，两个整数 $s,g$，表示起点和终点。</p>

# 输出格式


<p>如果不存在一条合法的从 $s$ 的底部到 $g$ 的底部的路径，输出$-1$。</p>
<p>否则输出所有路径中长度最短的那一条。</p>

# 样例一


<h4>plain</h4>
<pre><code class="sh_plain">7 7
0 8
3 7
5 9
7 7
10 6
12 6
14 9
0 1 1
0 2 6
0 6 8
2 3 1
2 6 7
3 4 2
4 6 5
1 5</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">27</code></pre>
<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/538/skywalk.png" alt="样例一示意图"/></p>

# 样例二


<h4>plain</h4>
<pre><code class="sh_plain">5 3
0 6
4 6
5 6
6 6
9 6
3 4 1
1 3 3
0 2 6
0 4</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">21</code></pre>

# 数据范围


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试包编号</th><th>限制与约定</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$n,m \le 50$</td><td>10</td></tr><tr><td>$2$</td><td>每座天桥至多与$10$座建筑相交</td><td>14</td></tr><tr><td>$3$</td><td>$s=0,g=n-1$,且所有建筑高度相等</td><td>15</td></tr><tr><td>$4$</td><td>$s=0,g=n-1$</td><td>18</td></tr><tr><td>$5$</td><td>无特殊约定</td><td>43</td></tr></tbody></table></div>

<p>对于所有测试数据，满足$1 \le n,m \le 100000,0 \le x_i \le 10^9,1 \le h_i \le 10^9$。</p>
<p>对于所有测试数据，满足$0 \le l_i \le r_i \le n-1,0 \le y_i \le min(h_{l_i},h_{r_i}),x_i \le x_{i+1}$。</p>
<p>保证所有天桥仅可能在端点处相交。</p>
<p><strong>时间限制:</strong> $4\texttt{s}$</p>
<p><strong>空间限制:</strong> $1\texttt{GB}$</p>
