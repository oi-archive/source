# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
binomial(伍一鸣)
</div>
<div style="text-align:center;font-size:14px;font-weight:bold;vertical-align:middle;" id="pres">
时间限制：3.0s   内存限制：64.0M
</div>
<div id="psrc" style="margin-top:20px;">
</div>
<div id="pcont" style="margin-top:20px;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
对于给定的n和p，求对于所有的0&lt;=i&lt;p,满足C(n,k)%p=i的k的个数<br/>
注：C(n,k)=n!/(k!*(n-k)!)<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
仅一行包含两个正整数n和p<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
仅一行，为一个长度为p的字符串s，s[i]表示C(n,k)%p=i的k的个数除以29后的余数，s[i]视为一个29进制的数字<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
20 4<br/>
</div>
<h3>
样例输出
</h3>
<div class="pddata">
D440<br/>
</div>
<h3>
数据规模和约定
</h3>
<div class="pdcont">
<table style="border-collapse:collapse;border:medium none;" align="center" cellpadding="2px" cellspacing="0">
<tbody>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
no
</td>
<td style="border:1pt solid;">
n
</td>
<td style="border:1pt solid;">
p
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
0<br/>
</td>
<td style="border:1pt solid;">
n&lt;2000
</td>
<td rowspan="20" style="border:1pt solid;">
p=51061
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
1
</td>
<td rowspan="5" style="border:1pt solid;">
n&lt;10^8
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
2
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
3
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
4
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
5
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
6
</td>
<td rowspan="7" style="border:1pt solid;">
n&lt;p^5
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
7
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
8
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
9
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
10
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
11
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
12
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
13
</td>
<td rowspan="7" style="border:1pt solid;">
n&lt;p^10
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
14
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
15
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
16
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
17
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
18
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
19
</td>
</tr>
</tbody>
</table>
</div>
</div>
