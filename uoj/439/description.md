# 题目描述

<p>小 Y 是一个爱好旅行的 OIer。她来到 X 国，打算将各个城市都玩一遍。</p>
<p>小 Y 了解到，X 国的 $n$ 个城市之间有 $m$ 条双向道路。每条双向道路连接两个城市。不存在两条连接同一对城市的道路，也不存在一条连接一个城市和它本身的道路。并且，从任意一个城市出发，通过这些道路都可以到达任意一个其他城市。小 Y 只能通过这些道路从一个城市前往另一个城市。</p>
<p>小 Y 的旅行方案是这样的：任意选定一个城市作为起点，然后从起点开始，每次可以选择一条与当前城市相连的道路，走向一个没有去过的城市，或者沿着第一次访问该城市时经过的道路后退到上一个城市。当小 Y 回到起点时，她可以选择结束这次旅行或继续旅行。需要注意的是，小 Y 要求在旅行方案中，每个城市都被访问到。</p>
<p>为了让自己的旅行更有意义，小 Y 决定在每到达一个新的城市（包括起点）时，将它的编号记录下来。她知道这样会形成一个长度为 $n$ 的序列。她希望这个序列的字典序最小，你能帮帮她吗？</p>
<p>对于两个长度均为 $n$ 的序列 $A$ 和 $B$，当且仅当存在一个正整数 $x$，满足以下条件时，我们说序列 $A$ 的字典序小于 $B$。</p>
<ul><li>对于任意正整数 $1\le i\lt x$，序列 $A$ 的第 $i$ 个元素 $A_i$ 和序列 $B$ 的第 $i$ 个元素 $B_i$ 相同。</li>
<li>序列 $A$ 的第 $x$ 个元素的值小于序列 $B$ 的第 $x$ 个元素的值。</li>
</ul>
# 输入格式


<p>输入文件共 $m+1$ 行。第一行包含两个整数 $n,m$ 中间用一个空格分隔。 </p>
<p>接下来 $m$ 行，每行包含两个整数 $u,v$，表示编号为 $u$ 和 $v$ 的城市之间有一条道路，两个整数之间用一个空格分隔。</p>

# 输出格式


<p>输出包含一行，$n$ 个整数，表示字典序最小的序列。相邻两个整数之间用一个空格分隔。</p>

# 样例一


<h4>input</h4>
<pre><code>6 5
1 3
2 3
2 5
3 4
4 6</code></pre>
<h4>output</h4>
<pre><code>1 3 2 5 4 6</code></pre>

# 样例二


<h4>input</h4>
<pre><code>6 6
1 3
2 3
2 5
3 4
4 5
4 6</code></pre>
<h4>output</h4>
<pre><code>1 3 2 4 5 6</code></pre>

# 限制与约定


<p>对于全部测试数据，$1\le n\le 5\times 10^3$，且 $m=n-1$ 或 $m=n$。保证 $1\le u,v\le n$。</p>
<p>对于不同的测试点，我们约定数据的规模如下：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th style="text-align:center;">测试点编号 </th>
    <th style="text-align:center;">$n=$ </th>
    <th style="text-align:center;">$m=$ </th>
    <th style="text-align:center;">特殊性质 </th>
  </tr></thead><tbody><tr><td style="text-align:center;">$1\sim 3$ </td>
    <td style="text-align:center;">$10$ </td>
    <td style="text-align:center;" rowspan="6">$m=n-1$ </td>
    <td style="text-align:center;" rowspan="2">无 </td>
  </tr><tr><td style="text-align:center;">$4,5$ </td>
    <td style="text-align:center;">$100$ </td>
  </tr><tr><td style="text-align:center;">$6\sim 8$ </td>
    <td style="text-align:center;">$10^3$ </td>
    <td style="text-align:center;">每个城市最多与两个城市相连 </td>
  </tr><tr><td style="text-align:center;">$9,10$ </td>
    <td style="text-align:center;">$10^3$ </td>
    <td style="text-align:center;">无 </td>
  </tr><tr><td style="text-align:center;">$11\sim 13$ </td>
    <td style="text-align:center;">$5\times 10^3$ </td>
    <td style="text-align:center;">每个城市最多与三个城市相连 </td>
  </tr><tr><td style="text-align:center;">$14,15$ </td>
    <td style="text-align:center;">$5\times 10^3$ </td>
    <td style="text-align:center;" rowspan="3">无 </td>
  </tr><tr><td style="text-align:center;">$16,17$ </td>
    <td style="text-align:center;">$10$ </td>
    <td style="text-align:center;" rowspan="4">$m=n$ </td>
  </tr><tr><td style="text-align:center;">$18,19$ </td>
    <td style="text-align:center;">$100$ </td>
  </tr><tr><td style="text-align:center;">$20\sim 22$ </td>
    <td style="text-align:center;">$10^3$ </td>
    <td style="text-align:center;">每个城市最多与两个城市相连 </td>
  </tr><tr><td style="text-align:center;">$23\sim 25$ </td>
    <td style="text-align:center;">$5\times 10^3$ </td>
    <td style="text-align:center;">无 </td>
    </tr></tbody></table></div>

<p><strong>时间限制：$\texttt{1s}$。</strong></p>
<p><strong>空间限制：$\texttt{512MB}$。</strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=439">样例数据下载</a></p>
