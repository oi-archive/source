# 题目描述


<p>
【问题描述】
</p>
<p>
Tom 是调皮的孩子，特别喜欢玩火，现在他手上有若干根长度分别为 1 和 sqrt(2) 的木棍，还有一张不能燃烧的平板，他把平板划分成长度为 1 的单元格，并标上座标。然后按以下规则把平板上的木棍组成一个连通图：木棍的两端必须放在单元格的顶点上。即长度为 1 的木棍放在单元格的某一边上，长度为 sqrt(2) 的木棍放在单元格的对角线上。
</p>
<p align="left">
<img alt="" src="http://acm.hit.edu.cn/hoj/static/attach/20170430/20170430232701_85823.jpg" height="359" width="460"/> 
</p>
<p>
Tom 的点火规则是，只能从木棍的两端点火，而不能从木棍的中间点火。 如图 ，不能在 A 点点火，但在 C 点或 B 点点火都是允许的。点火后，火会沿着木棍向前燃烧（每根都有自己的燃烧速度），并能点燃与它相接的其它木棍。
</p>
<p>
任务： 写一程序计算从哪里开始点火，使得燃烧的总时间最短，输出最短时间。
</p>
<p>
Input Data
</p>
<p>
输入文件第一行为一个正整数 N ，表示组成图形的木棍数目，后面共有 N 行，每行 5 个数： X1 Y1 X2 Y2 T , 其中（ X1 , Y1 ） 和（ X2 , Y2 ）分别表示木棍两端的坐标， T 表示木棍燃烧时间，是指从木棍的某一端点火燃烧到别一端，燃完所需的时间。
</p>
<p>
Output Data
</p>
<p>
输出文件是一个保留 4 位小数的实数，表示所有木棍完全燃烧的最少时间。
</p>
<p>
约束 1 ≤n≤40
</p>
<p>
保证图形是连通的，所有的木棍长度都是 1 或 sqrt(2)，没有任何两根木棍重合 .
</p>
<p>
-200≤ X1, Y1, X2, Y2 ≤200; 0≤ T ≤ 10^7 .
</p>
<p>
如果你的输出结果与标准答案相差小于 0.001 ，则认为你的结果正确。
</p>
<p>
样例 1
</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="103">
<p>
firez.in
</p>
</td>
<td valign="top" width="84">
<p>
firez.out
</p>
</td>
<td valign="top" width="324">
<p>
解释
</p>
</td>
</tr>
<tr>
<td valign="top" width="103">
<p>
1
</p>
<p>
0 0 1 1 1
</p>
</td>
<td valign="top" width="84">
<p>
1.0000
</p>
</td>
<td valign="top" width="324">
<p>
从任一端点火都行，燃烧时间都是 1
</p>
</td>
</tr>
</tbody>
</table>
<p>
样例 2
</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="103">
<p>
firez.in
</p>
</td>
<td valign="top" width="84">
<p>
firez.out
</p>
</td>
<td valign="top" width="324">
<p>
解释
</p>
</td>
</tr>
<tr>
<td valign="top" width="103">
<p>
5
</p>
<p>
0 0 0 1 1
</p>
<p>
1 0 0 1 10
</p>
<p>
0 0 1 0 1
</p>
<p>
0 0 1 1 1
</p>
<p>
2 2 1 1 1
</p>
</td>
<td valign="top" width="84">
<p>
3.2500
</p>
</td>
<td valign="top" width="324">
<p>
在 (0,0) 位置点火
</p>
<p>
木棍 1, 3 和 4 将被点燃，燃烧 0.5 分钟后，木棍 2 将被从中间点燃向两端燃烧，再过 0.5 分钟，木棍 1, 3, 4 将被完全燃烧，木棍 5 将被点燃并在 1 分钟后燃烧完 ( 比木棍 2 早燃完 ) 。
</p>
<p>
木棍 2 从中间向两端燃烧 0.5 分钟以后，变成两小段，每段的燃烧时间是 4.5 分钟。但因为此时两小段木棍的另一端也同时被点燃，燃烧速度变成原来的两倍，还需 2.25 分钟的燃烧时间， 所以总时间： 1 + 2 . 25 = 3 . 25
</p>
</td>
</tr>
</tbody>
</table>
<p>
样例 3
</p>
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="103">
<p>
firez.in
</p>
</td>
<td valign="top" width="84">
<p>
firez.out
</p>
</td>
<td valign="top" width="324">
<p>
解释
</p>
</td>
</tr>
<tr>
<td valign="top" width="103">
<p>
3
</p>
<p>
1 1 1 2 10
</p>
<p>
1 2 2 2 10
</p>
<p>
1 1 2 2 50
</p>
</td>
<td valign="top" width="84">
<p>
35.0000
</p>
</td>
<td valign="top" width="324">
<p>
在 (1,2) 位置点火， 木棍 (1 1, 1 2) 和 (1 2, 2 2) 将燃烧 10 分钟。 . 最后一根木棍在 10 分钟后从两端被点燃，燃烧时间为 25 分钟。
</p>
</td>
</tr>
</tbody>
</table>
<p>
<br/>
 
</p>
