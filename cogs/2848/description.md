# 题目描述


<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width initial-scale=1"/>
<title>
obc.md
</title>
<h3>
题目描述
</h3>
<p>
ZQR肥肠喜欢打808，尤其爱玩obc。
</p>
<p>
在一个课间，ZQR又来到了机房，准备进入召唤师峡谷大杀四方。
</p>
<p>
他又点开了排位赛，选了他最爱玩的ADC(Atm Damage Carry)。
</p>
<p>
召唤师峡谷可以看做一个二维平面。
</p>
<p>
ZQR决定使用HB射手，使用w技楞万箭齐发。
</p>
<p>
ZQR每次可以选择一条长为$L\ (1\leq L\leq 10^6)$的，与x轴或与y轴平行的线段，消灭这一条线段上所有的小兵。
</p>
<p>
共有$n\ (1\leq n\leq 100000)$个小兵在战(song)斗(qian)，ZQR想知道他使用$k$次万箭齐发，最多可以消灭多少小兵?
</p>
<p>
由于ZQR比较懒，他在这$k$次的技能使用中不会改变攻击的方向，即$k$次都与x轴平行或$k$次都与y轴平行。
</p>
<h3>
输入格式
</h3>
<p>
第一行三个整数$n,k,L$表示小兵的数目与使用万箭齐发的次数。
</p>
<p>
接下来第$2$行到第$n+1$行每行两个非负整数$x,y$，表示第$i$个小兵的坐标是$(x,y)$ 。
</p>
<h3>
输出格式
</h3>
<p>
一个整数,代表ZQR最多消灭小兵的个数
</p>
<h3>
样例输入
</h3>
<pre>6 1 10
5 2
1 3
4 1
1 5
3 4
2 4
</pre>
<h3>
样例输出
</h3>
<pre><code> 2 </code></pre>
<h3>
数据范围
</h3>
<table>
<thead>
<tr>
<th style="text-align:center;">
数据编号
</th>
<th style="text-align:center;">
n
</th>
<th style="text-align:center;">
k
</th>
<th style="text-align:center;">
x,y
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:center;">
1
</td>
<td style="text-align:center;">
$\leq100$
</td>
<td style="text-align:center;">
0
</td>
<td style="text-align:center;">
$\leq1000$
</td>
</tr>
<tr>
<td style="text-align:center;">
2
</td>
<td style="text-align:center;">
$\leq100$
</td>
<td style="text-align:center;">
1
</td>
<td style="text-align:center;">
$\leq1000$
</td>
</tr>
<tr>
<td style="text-align:center;">
3
</td>
<td style="text-align:center;">
$\leq100$
</td>
<td style="text-align:center;">
2
</td>
<td style="text-align:center;">
$\leq1000$
</td>
</tr>
<tr>
<td style="text-align:center;">
4
</td>
<td style="text-align:center;">
$\leq1000$
</td>
<td style="text-align:center;">
2
</td>
<td style="text-align:center;">
$\leq1000$
</td>
</tr>
<tr>
<td style="text-align:center;">
5
</td>
<td style="text-align:center;">
$\leq1000$
</td>
<td style="text-align:center;">
1
</td>
<td style="text-align:center;">
$\leq1000$
</td>
</tr>
<tr>
<td style="text-align:center;">
6
</td>
<td style="text-align:center;">
$\leq100000$
</td>
<td style="text-align:center;">
1
</td>
<td style="text-align:center;">
$\leq10^9$
</td>
</tr>
<tr>
<td style="text-align:center;">
7
</td>
<td style="text-align:center;">
$\leq100000$
</td>
<td style="text-align:center;">
1
</td>
<td style="text-align:center;">
$\leq10^9$
</td>
</tr>
<tr>
<td style="text-align:center;">
8
</td>
<td style="text-align:center;">
$\leq100000$
</td>
<td style="text-align:center;">
2
</td>
<td style="text-align:center;">
$\leq10^9$
</td>
</tr>
<tr>
<td style="text-align:center;">
9
</td>
<td style="text-align:center;">
$\leq100000$
</td>
<td style="text-align:center;">
2
</td>
<td style="text-align:center;">
$\leq10^9$
</td>
</tr>
<tr>
<td style="text-align:center;">
10
</td>
<td style="text-align:center;">
$\leq100000$
</td>
<td style="text-align:center;">
2
</td>
<td style="text-align:center;">
$\leq10^9$
</td>
</tr>
</tbody>
</table>
<p>
对于所有的数据，有$0\leq x, y\leq 10^9$
</p>
