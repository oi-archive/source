# 题目描述

<p>在数轴上有 $n$ 个闭区间 $[l_1,r_1],[l_2,r_2],...,[l_n,r_n]$。现在要从中选出 $m$ 个区间，使得这 $m$ 个区间共同包含至少一个位置。换句话说，就是使得存在一个 $x$，使得对于每一个被选中的区间 $[l_i,r_i]$，都有 $l_i \le x \le r_i$。</p>
<p>对于一个合法的选取方案，它的花费为<strong>被选中的最长区间长度减去被选中的最短区间长度</strong>。区间 $[l_i,r_i]$ 的长度定义为 $r_i-l_i$，即等于它的右端点的值减去左端点的值。</p>
<p>求所有合法方案中最小的花费。如果不存在合法的方案，输出 $−1$。</p>

# 输入格式


<p>第一行包含两个正整数 $n,m$，用空格隔开，意义如上文所述。保证 $1 \le m \le n$。</p>
<p>接下来 $n$ 行，每行表示一个区间，包含用空格隔开的两个整数 $l_i$ 和 $r_i$ 为该区间的左右端点。</p>

# 输出格式


<p>只有一行，包含一个正整数，即最小花费。</p>

# 样例一


<h4>input</h4>
<pre>6 3
3 5
1 2
3 4
2 2
1 5
1 4

</pre>

<h4>output</h4>
<pre>2

</pre>

<h4>explanation</h4>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/222/seg.png" alt="样例图"/></p>
<p>如图，当 $n=6,~m=3$ 时，花费最小的方案是选取 $[3,5]$、$[3,4]$、$[1,4]$ 这三个区间，他们共同包含了 $4$ 这个位置，所以是合法的。其中最长的区间是 $[1,4]$，最短的区间是 $[3,4]$，所以它的花费是 $(4−1)−(4−3)=2$。</p>

# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>所有测试数据的范围和特点如下表所示：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>$l_i,r_i$</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="2">$20$</td><td>$9$</td><td rowspan="2">$0 \le l_i \le r_i \le 100$</td></tr><tr><td>2</td><td>$10$</td>
</tr><tr><td>3</td><td>$199$</td><td rowspan="2">$3$</td><td rowspan="4">$0 \le l_i \le r_i \le 100000$</td></tr><tr><td>4</td><td>$200$</td></tr><tr><td>5</td><td>$1000$</td><td rowspan="2">$2$</td></tr><tr><td>6</td><td>$2000$</td></tr><tr><td>7</td><td>$199$</td><td>$60$</td><td rowspan="2">$0 \le l_i \le r_i \le 5000$</td></tr><tr><td>8</td><td rowspan="2">$200$</td><td rowspan="2">$50$</td></tr><tr><td>9</td><td>$0 \le l_i \le r_i \le 10^9$</td></tr><tr><td>10</td><td>$1999$</td><td>$500$</td><td rowspan="2">$0 \le l_i \le r_i \le 5000$</td></tr><tr><td>11</td><td rowspan="2">$2000$</td><td>$400$</td></tr><tr><td>12</td><td>$500$</td><td>$0 \le l_i \le r_i \le 10^9$</td></tr><tr><td>13</td><td>$30000$</td><td>$2000$</td><td rowspan="4">$0 \le l_i \le r_i \le 100000$</td></tr><tr><td>14</td><td>$40000$</td><td>$1000$</td></tr><tr><td>15</td><td>$50000$</td><td>$15000$</td></tr><tr><td>16</td><td>$100000$</td><td rowspan="2">$20000$</td></tr><tr><td>17</td><td>$200000$</td><td rowspan="4">$0 \le l_i \le r_i \le 10^9$</td></tr><tr><td>18</td><td>$300000$</td><td>$50000$</td></tr><tr><td>19</td><td>$400000$</td><td>$90000$</td></tr><tr><td>20</td><td>$500000$</td><td>$200000$</td></tr></tbody></table></div>


<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=222">样例数据下载</a></p>
