# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
矩形计算(钟沛林)
</div>
<div style="text-align:center;font-size:14px;font-weight:bold;vertical-align:middle;" id="pres">
时间限制：2.0s   内存限制：256.0M
</div>
<div id="psrc" style="margin-top:20px;">
</div>
<div id="pcont" style="margin-top:20px;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
输入一个n*m的矩阵，矩阵的每一个元素都是一个整数，然后有q个询问，每次询问一个子矩阵的权值。矩阵的权值是这样定义的，对于一个整数x，如果它在该矩阵中出现了p次，那么它给该矩阵的权值就贡献p<sup>2</sup>。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行两个整数n，m表示矩阵的规模。<br/>
接下来n行每行m个整数，表示这个矩阵的每个元素。<br/>
再下来一行一个整数q，表示询问个数。<br/>
接下来q行每行四个正整数x1，y1，x2，y2，询问以第x1行第y1列和第x2行第y2列的连线为对角线的子矩阵的权值。<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出q行每行一个整数回答对应询问。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
3 4<br/>
1 3 2 1<br/>
1 3 2 4<br/>
1 2 3 4<br/>
8<br/>
1 2 2 1<br/>
1 1 2 1<br/>
1 1 3 4<br/>
1 1 1 1<br/>
2 2 3 3<br/>
3 4 2 2<br/>
1 3 3 1<br/>
2 4 3 4<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
8<br/>
4<br/>
38<br/>
1<br/>
8<br/>
12<br/>
27<br/>
4<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于全部数据<br/>
1&lt;=n,m&lt;=200<br/>
q&lt;=100000<br/>
|矩阵元素大小|&lt;=2*10<sup>9</sup><br/>
<table style="border-collapse:collapse;border:medium none;" cellpadding="2px" cellspacing="0" align="center">
<tbody>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case1<br/>
</td>
<td colspan="2" style="border:1pt solid;" valign="top">
3 3<br/>
-1 1 2<br/>
-1 -1 1<br/>
10 2 1<br/>
3<br/>
1 3 3 1<br/>
1 3 2 2<br/>
2 1 3 2<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case2<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=10,m&lt;=10,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case3<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=100,m&lt;=100,q&lt;=5000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case4<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=1000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case5<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=1000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case6<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=1000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case7<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=100,m&lt;=100,q&lt;=50000<br/>
</td>
<td style="border:1pt solid;" valign="top">
原矩阵中的不同元素不超过200<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case8<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=100,m&lt;=100,q&lt;=50000<br/>
</td>
<td style="border:1pt solid;" valign="top">
原矩阵中的不同元素不超过200<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case9<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=100,m&lt;=100,q&lt;=50000<br/>
</td>
<td style="border:1pt solid;" valign="top">
原矩阵中的不同元素不超过200<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case10<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
原矩阵中的不同元素不超过200<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case11<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
原矩阵中的不同元素不超过200<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case12<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
原矩阵中的不同元素不超过200<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case13<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=100,m&lt;=100,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case14<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=100,m&lt;=100,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case15<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case16<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case17<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case18<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case19<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
case20<br/>
</td>
<td style="border:1pt solid;" valign="top">
n&lt;=200,m&lt;=200,q&lt;=100000<br/>
</td>
<td style="border:1pt solid;" valign="top">
</td>
</tr>
</tbody>
</table>
</div>
</div>
