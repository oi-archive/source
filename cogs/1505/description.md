# 题目描述


<h3>
【题目描述】
</h3>
<p>
有一个奶牛运输公司，设在农场A中，它有一个用来在七个农场A，B，C，D、E、F、G之间运输奶牛的运输车。七个农场之间的距离由下表给出：
</p>
<p>
</p><table class="MsoNormalTable" border="1" cellspacing="0" cellpadding="0" style="border-collapse:collapse;border:none;">
<tbody>
<tr>
<td width="49" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"></span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> B</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> C</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> D</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> E</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> F</span> 
</p>
</td>
<td width="47" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> G</span> 
</p>
</td>
</tr>
<tr>
<td width="49" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> A</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 56</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 43</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 71</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 35</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 41</span> 
</p>
</td>
<td width="47" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 36</span> 
</p>
</td>
</tr>
<tr>
<td width="49" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> B</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 0</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 54</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 58</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 36</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 79</span> 
</p>
</td>
<td width="47" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 31</span> 
</p>
</td>
</tr>
<tr>
<td width="49" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> C</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> .</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 0</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 30</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 20</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 31</span> 
</p>
</td>
<td width="47" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 58</span> 
</p>
</td>
</tr>
<tr>
<td width="49" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> D</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> .</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> .</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 0</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 38</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 59 </span> 
</p>
</td>
<td width="47" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 75</span> 
</p>
</td>
</tr>
<tr>
<td width="49" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> E</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> .</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> .</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> .</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 0</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 44</span> 
</p>
</td>
<td width="47" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 67</span> 
</p>
</td>
</tr>
<tr>
<td width="49" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> F</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> .</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> .</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> .</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> .</span> 
</p>
</td>
<td width="48" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 0</span> 
</p>
</td>
<td width="47" valign="top" style="border:solid windowtext 1.0pt;">
<p class="MsoNormal">
<span style="font-size:12.0pt;"> 72</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p></p>
<p>
每天早晨，运输公司都要决定运输奶牛的顺序，使得总路程最少。下面是规则：
</p>
<p>
1：运输车总是从位于农场A的公司总部出发，而且当所有的运输任务完成之后还要返回总部；
</p>
<p>
2：运输车一次只能运送一头奶牛；
</p>
<p>
3：每个运输任务是由一对字母给出的，分别代表奶牛将从哪个农场被运向另一个农场。
</p>
<p>
你的任务是写一个程序，对一组给定的任务，求出一条完成所有任务的最短路线（从农场A出发，最后返回农场A）。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有一个正整数N(N&lt;=12)，表示任务个数
</p>
<p>
接下来的N行，每行有两个字符ch1,ch2，表示一个将奶牛从ch1运向ch2的任务
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个正整数：最短路线的长度。
</p>
<h3>
【样例输入】
</h3>
<p>
5
</p>
<p>
F C
</p>
<p>
G B
</p>
<p>
B D
</p>
<p>
A E
</p>
<p>
G A
</p>
<h3>
【样例输出】
</h3>
<p>
368
</p>
<h3>
【提示】
</h3>
<p>
表格中，“.”意味着这个值前面已经出现过，因为道路是双向的。
</p>
<h3>
【来源】
</h3>
<p>
<span style="font-family:serif;background-color:white;font-size:16px;font-weight:normal;line-height:20px;">《信息学奥林匹克》杂志1998年1-2期</span> 
</p>
<p>
1995年美国计算机程序设计选拔赛试题
</p>
<p>
李刚，《动态规划的深入讨论》
</p>
