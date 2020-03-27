# 题目描述

<p>C 城将要举办一系列的赛车比赛。在比赛前，需要在城内修建 $m$ 条赛道。</p>
<p>C 城一共有 $n$ 个路口，这些路口编号为 $1,2, \cdots , n$，有 $n − 1$ 条适合于修建赛道的双向通行的道路，每条道路连接着两个路口。其中，第 $i$ 条道路连接的两个路口编号为 $a_i$ 和 $b_i$，该道路的长度为 $l_i$。借助这 $n − 1$ 条道路，从任何一个路口出发都能到达其他所有的路口。</p>
<p>一条赛道是一组互不相同的道路 $e_1, e_2, \cdots , e_k$，满足可以从某个路口出发，依次经过道路 $e_1, e_2, \cdots , e_k$（每条道路经过一次，不允许调头）到达另一个路口。一条赛道的长度等于经过的各道路的长度之和。为保证安全，要求每条道路至多被一条赛道经过。</p>
<p>目前赛道修建的方案尚未确定。你的任务是设计一种赛道修建的方案，使得修建的 $m$ 条赛道中长度最小的赛道长度最大（即 $m$ 条赛道中最短赛道的长度尽可能大）。</p>

# 输入格式


<p>输入文件第一行包含两个由空格分隔的正整数 $n,m$，分别表示路口数及需要修建的赛道数。<br/>接下来 $n − 1$ 行，第 $i$ 行包含三个正整数 $a_i,b_i,l_i$，表示第 $i$ 条适合于修建赛道的道路连接的两个路口编号及道路长度。保证任意两个路口均可通过这 $n − 1$ 条道路相互到达。每行中相邻两数之间均由一个空格分隔。</p>

# 输出格式


<p>输出共一行，包含一个整数，表示长度最小的赛道长度的最大值。</p>

# 样例一


<h4>input</h4>
<pre><code>7 1
1 2 10
1 3 5
2 4 9
2 5 8
3 6 6
3 7 7</code></pre>
<h4>output</h4>
<pre><code>31</code></pre>
<h4>样例解释 1</h4>
<p>所有路口及适合于修建赛道的道路如下图所示：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/438/saidao1.webp" style="width:250px;" alt="赛道"/></p>
<p>道路旁括号内的数字表示道路的编号，非括号内的数字表示道路长度。</p>
<p>需要修建 $1$ 条赛道。可以修建经过第 $3,1,2,6$ 条道路的赛道（从路口 $4$ 到路口 $7$），则该赛道的长度为 $9 + 10 + 5 + 7 = 31$，为所有方案中的最大值。</p>

# 样例二


<h4>input</h4>
<pre><code>9 3
1 2 6
2 3 3
3 4 5
4 5 10
6 2 4
7 2 9
8 4 7
9 4 4</code></pre>
<h4>output</h4>
<pre><code>15</code></pre>
<h4>样例解释 2</h4>
<p>所有路口及适合于修建赛道的道路如下图所示：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/438/saidao2.webp" style="width:300px;" alt="赛道"/></p>
<p>需要修建 $3$ 条赛道。可以修建如下 $3$ 条赛道：
1. 经过第 $1,6$ 条道路的赛道（从路口 $1$ 到路口 $7$），长度为 $6 + 9 = 15$；
2. 经过第 $5,2,3,8$ 条道路的赛道（从路口 $6$ 到路口 $9$），长度为 $4 + 3 + 5 + 4 = 16$；
3. 经过第 $7,4$ 条道路的赛道（从路口 $8$ 到路口 $5$），长度为 $7 + 10 = 17$。</p>
<p>长度最小的赛道长度为 $15$，为所有方案中的最大值。</p>

# 限制与约定


<p>所有测试数据的范围和特点如下表所示：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th style="text-align:center;">测试点编号 </th>
    <th style="text-align:center;">$n$ </th>
    <th style="text-align:center;">$m$ </th>
    <th style="text-align:center;">$a_i=1$ </th>
    <th style="text-align:center;">$b_i=a_i+1$ </th>
    <th style="text-align:center;">分支不超过 $3$ </th>
  </tr></thead><tbody><tr><td style="text-align:center;">$1$ </td>
    <td style="text-align:center;">$\le 5$ </td>
    <td style="text-align:center;">$=1$ </td>
    <td style="text-align:center;" rowspan="2">否 </td>
    <td style="text-align:center;">否 </td>
    <td style="text-align:center;" rowspan="2">是 </td>
  </tr><tr><td style="text-align:center;">$2$ </td>
    <td style="text-align:center;">$\le 10$ </td>
    <td style="text-align:center;" rowspan="2">$\le n-1$ </td>
    <td style="text-align:center;">是 </td>
  </tr><tr><td style="text-align:center;">$3$ </td>
    <td style="text-align:center;">$\le 15$ </td>
    <td style="text-align:center;">是 </td>
    <td style="text-align:center;" rowspan="6">否 </td>
    <td style="text-align:center;">否 </td>
  </tr><tr><td style="text-align:center;">$4$ </td>
    <td style="text-align:center;">$\le 10^3$ </td>
    <td style="text-align:center;" rowspan="3">$=1$ </td>
    <td style="text-align:center;">否 </td>
    <td style="text-align:center;">是 </td>
  </tr><tr><td style="text-align:center;">$5$ </td>
    <td style="text-align:center;" rowspan="3">$\le 3\times 10^4$ </td>
    <td style="text-align:center;">是 </td>
    <td style="text-align:center;" rowspan="4">否 </td>
  </tr><tr><td style="text-align:center;">$6$ </td>
    <td style="text-align:center;">否 </td>
  </tr><tr><td style="text-align:center;">$7$ </td>
    <td style="text-align:center;" rowspan="14">$\le n-1$ </td>
    <td style="text-align:center;" rowspan="2">是 </td>
  </tr><tr><td style="text-align:center;">$8$ </td>
    <td style="text-align:center;">$\le 5\times 10^4$ </td>
  </tr><tr><td style="text-align:center;">$9$ </td>
    <td style="text-align:center;">$\le 10^3$ </td>
    <td style="text-align:center;" rowspan="12">否 </td>
    <td style="text-align:center;" rowspan="3">是 </td>
    <td style="text-align:center;" rowspan="8">是 </td>
  </tr><tr><td style="text-align:center;">$10$ </td>
    <td style="text-align:center;">$\le 3\times 10^4$ </td>
  </tr><tr><td style="text-align:center;">$11$ </td>
    <td style="text-align:center;">$\le 5\times 10^4$ </td>
  </tr><tr><td style="text-align:center;">$12$ </td>
    <td style="text-align:center;" rowspan="2">$\le 50$ </td>
    <td style="text-align:center;" rowspan="9">否 </td>
  </tr><tr><td style="text-align:center;">$13$ </td>
  </tr><tr><td style="text-align:center;">$14$ </td>
    <td style="text-align:center;" rowspan="2">$\le 200$ </td>
  </tr><tr><td style="text-align:center;">$15$ </td>
  </tr><tr><td style="text-align:center;">$16$ </td>
    <td style="text-align:center;" rowspan="2">$\le 10^3$ </td>
  </tr><tr><td style="text-align:center;">$17$ </td>
    <td style="text-align:center;" rowspan="4">否 </td>
  </tr><tr><td style="text-align:center;">$18$ </td>
    <td style="text-align:center;" rowspan="2">$\le 3\times 10^4$ </td>
  </tr><tr><td style="text-align:center;">$19$ </td>
  </tr><tr><td style="text-align:center;">$20$ </td>
    <td style="text-align:center;">$\le 5\times 10^4$ </td>
  </tr></tbody></table></div>

<p>其中，「分支不超过 $3$」的含义为：每个路口至多有 $3$ 条道路与其相连。</p>
<p>对于所有的数据，$2 \le n \le 5\times 10^4, \ 1 \le m \le n − 1,\ 1 \le a_i,b_i \le n,\  1 \le l_i \le 10^4$。</p>
<p><strong>时间限制：$\texttt{1s}$。</strong></p>
<p><strong>空间限制：$\texttt{512MB}$。</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=438">样例数据下载</a></p>
