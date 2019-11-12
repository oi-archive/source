# 题目描述


<p>
<b>【问题描述】</b><br/>
    在一个 N*N 的棋盘上（ 1 ≤ N ≤ 11 ），填入 1 ， 2 ，…， N*N 共 N*N 个数，使得任意两个相邻的数之和为素数。
</p>
<p>
例如：当 N=2 时，有：
</p>
<table border="1" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td width="31" valign="top">
<p align="center">
1
</p>
</td>
<td width="36" valign="top">
<p align="center">
2
</p>
</td>
</tr>
<tr>
<td width="31" valign="top">
<p align="center">
4
</p>
</td>
<td width="36" valign="top">
<p align="center">
3
</p>
</td>
</tr>
</tbody>
</table>
<p>
当 N=4 时，一种可以填写的方案如下：在这里我们约定：左上角的格子里必须填数字 1 。
</p>
<table border="1" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td width="34" valign="top">
<p align="center">
1
</p>
</td>
<td width="34" valign="top">
<p align="center">
2
</p>
</td>
<td width="34" valign="top">
<p align="center">
11
</p>
</td>
<td width="34" valign="top">
<p align="center">
12
</p>
</td>
</tr>
<tr>
<td width="34" valign="top">
<p align="center">
4
</p>
</td>
<td width="34" valign="top">
<p align="center">
9
</p>
</td>
<td width="34" valign="top">
<p align="center">
8
</p>
</td>
<td width="34" valign="top">
<p align="center">
5
</p>
</td>
</tr>
<tr>
<td width="34" valign="top">
<p align="center">
7
</p>
</td>
<td width="34" valign="top">
<p align="center">
10
</p>
</td>
<td width="34" valign="top">
<p align="center">
3
</p>
</td>
<td width="34" valign="top">
<p align="center">
14
</p>
</td>
</tr>
<tr>
<td width="34" valign="top">
<p align="center">
6
</p>
</td>
<td width="34" valign="top">
<p align="center">
13
</p>
</td>
<td width="34" valign="top">
<p align="center">
16
</p>
</td>
<td width="34" valign="top">
<p align="center">
15
</p>
</td>
</tr>
</tbody>
</table>
<p>
【输入格式】 <br/>
    文件只有一行为一个正整数n
</p>
<p>
【输出格式】 <br/>
    输出文件有n行,每行有n个数,中间用一个空格隔开
</p>
<p>
如有多种解，设a[i,j]为解的第i行第j个数,则输出以i为第一关键字，j为第二关键字，小数在前的那一种方案；若无解，则输出“NO”。
</p>
<p>
【输入输出样例】<br/>
 <b><br/>
</b>输入： <br/>
2
</p>
<p>
输出：<br/>
1 2 <br/>
4 3
</p>
