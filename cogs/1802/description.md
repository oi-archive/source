# 题目描述


<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link type="text/css" href="../../css/Tsinsen2011.css" rel="stylesheet"/>
<div class="probtitle" id="ptit">
字符串游戏(徐捷)
</div>
<div style="text-align:center;font-size:14px;font-weight:bold;vertical-align:middle;" id="pres">
时间限制：3.0s   内存限制：256.0MB
</div>
<div id="psrc" style="margin-top:20px;display:none;">
<div class="pdsec">
试题来源
</div>
<div class="pdcont">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
给定N个仅有a~z组成的字符串a<sub>i</sub>,每个字符串都有一个权值v<sub>i</sub>,有M次操作，操作分三种：<br/>
Cv x v&#39;:把第x个字符串的权值修改为v&#39;<br/>
Cs x a&#39;:把第x个字符串修改成a&#39;<br/>
Q:求出当前的最大权字符串集合，使得这个集合中的字符串经过重新排列后满足除最后一个字符串外，前一个字符串是后一个的前缀(两个字符串相同也是前缀关系，也可以一个字符串都不选)<br/>
前50%的数据可以接受离线算法，后50%的数据要求在线算法。<br/>
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含一个正整数Test表示当前的数据类型。<br/>
输入的第二行包含两个正整数N,M表示字符串数和操作数。<br/>
以下N行，每行一个字符串a<sub>i</sub><br/>
第N+3行包含N个整数v<sub>i</sub><br/>
以下M行，为M次操作，操作有三种Cv x v&#39;,Cs x a&#39;,Q,第三种操作如题目描述一样，对于Test=1的修改操作，不用做   任何变化，对于Test=2的修改操作，假设当前最后一次询问操作的答案是ans(如果还没有询问操作，ans=0),那么对于第   一种操作中的v&#39;=min(1000,v&#39;+(ans mod 1000)),对于第二种操作的字符串a&#39;,它的每一位都要加上ans  mod 26(a~z循环)<br/>
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
对于每一次询问输出合法的最大权字符串集合的权值和。<br/>
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
1<br/>
5 5<br/>
aba<br/>
ab<br/>
babb<br/>
abaa<br/>
abab<br/>
-2 1 4 2 3<br/>
Q<br/>
Cv 1 2<br/>
Q<br/>
Cs 3 abaab<br/>
Q<br/>
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
4<br/>
6<br/>
9<br/>
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
数据分两种，A类数据可以用离线的方法来完成，B类数据必须使用在线算法。<br/>
令len=输入数据中所有出现的字符串总长度<br/>
|v|&lt;1001<br/>
<table style="border-collapse:collapse;border:medium none;" cellpadding="2px" cellspacing="0" align="center">
<tbody>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
编号<br/>
</td>
<td style="border:1pt solid;" valign="top">
数据类别<br/>
</td>
<td style="border:1pt solid;" valign="top">
范围<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
1<br/>
</td>
<td rowspan="10" style="border:1pt solid;" valign="top">
A<br/>
</td>
<td style="border:1pt solid;" valign="top">
N,M≤30,len≤500<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
2<br/>
</td>
<td rowspan="3" style="border:1pt solid;" valign="top">
N,M≤1000,len≤10000<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
3<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
4<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
5<br/>
</td>
<td rowspan="6" style="border:1pt solid;" valign="top">
N≤50000,M≤10<sup>5</sup>,len≤10<sup>6</sup><br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
6<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
7<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
8<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
9<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
10<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
11<br/>
</td>
<td rowspan="10" style="border:1pt solid;" valign="top">
B<br/>
</td>
<td rowspan="10" style="border:1pt solid;" valign="top">
N≤50000,M≤10<sup>5</sup>,len≤10<sup>6</sup><br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
12<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
13<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
14<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
15<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
16<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
17<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
18<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
19<br/>
</td>
</tr>
<tr style="border:1pt solid;" align="center">
<td style="border:1pt solid;" valign="top">
20<br/>
</td>
</tr>
</tbody>
</table>
</div>
</div>
