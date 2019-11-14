# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
Painting(艾雨青)
</div>
<div style="text-align:center;font-size:14px;font-weight:bold;vertical-align:middle;" id="pres">
时间限制：1.0s   内存限制：256.0MB
</div>
<div id="psrc" style="margin-top:20px;display:none;">
<div class="pdsec">
试题来源
</div>
<div class="pdcont">
</div>
</div>
<p>
<br/>
</p>
<h3>
【问题描述】
</h3>
<div class="pdcont">
给出一颗n个节点的树，要给每一条边染一个1~n-1的颜色，染颜色i的代价为i，要求同一个节点连出的所有边所染颜色都互不相同，求一个为整棵树染色的方案，使得代价之和尽量小。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行一个正整数n<br/>
接下来n-1行，每行两个互不相同的正整数a,b表示节点a与b之间有一条边，保证给出的图是一颗树<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
一行一个正整数，表示你的方案的总代价<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
3<br/>
1 2<br/>
1 3<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
3<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<p>
注意这里的输出格式及评分标准与原题不同，原题有部分分，且要求输出方案。
</p>
<p>
<br/>
</p>
<p>
</p><table style="border-collapse:collapse;border:medium none;" cellpadding="2px" cellspacing="0" align="center">
<tbody>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
Test
</td>
<td style="border:1pt solid;">
N
</td>
<td style="border:1pt solid;">
Test
</td>
<td style="border:1pt solid;">
N
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
1
</td>
<td style="border:1pt solid;">
=5
</td>
<td style="border:1pt solid;">
11
</td>
<td style="border:1pt solid;">
=105
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
2
</td>
<td style="border:1pt solid;">
=10
</td>
<td style="border:1pt solid;">
12
</td>
<td style="border:1pt solid;">
=110
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
3
</td>
<td style="border:1pt solid;">
=10
</td>
<td style="border:1pt solid;">
13
</td>
<td style="border:1pt solid;">
=115
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
4
</td>
<td style="border:1pt solid;">
=50
</td>
<td style="border:1pt solid;">
14
</td>
<td style="border:1pt solid;">
=120
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
5
</td>
<td style="border:1pt solid;">
=50
</td>
<td style="border:1pt solid;">
15
</td>
<td style="border:1pt solid;">
=125
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
6
</td>
<td style="border:1pt solid;">
=60
</td>
<td style="border:1pt solid;">
16
</td>
<td style="border:1pt solid;">
=130
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
7
</td>
<td style="border:1pt solid;">
=70
</td>
<td style="border:1pt solid;">
17
</td>
<td style="border:1pt solid;">
=135
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
8
</td>
<td style="border:1pt solid;">
=80
</td>
<td style="border:1pt solid;">
18
</td>
<td style="border:1pt solid;">
=140
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
9
</td>
<td style="border:1pt solid;">
=90
</td>
<td style="border:1pt solid;">
19
</td>
<td style="border:1pt solid;">
=145
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;">
10
</td>
<td style="border:1pt solid;">
=100
</td>
<td style="border:1pt solid;">
20
</td>
<td style="border:1pt solid;">
=150
</td>
</tr>
</tbody>
</table>
<span style="font-size:small;"><span style="line-height:normal;"><br/>
</span></span> 
<p></p>
<p>
<br/>
</p>
