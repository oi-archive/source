# 题目描述


<h3>
【问题描述】
</h3>
<p>
<br/>
</p>
<p>
给你一个长度为N的数组，一个长为K的滑动的窗体从最左移至最右端，你只能见到窗口的K个数，每次窗体向右移动一位，如下表：
</p>
<table width="515" border="1">
<tbody>
<tr>
<td width="317">
Window position
</td>
<td width="85">
Min value
</td>
<td width="91">
Max value
</td>
</tr>
<tr>
<td>
<span style="color:#E53333;"><strong>[</strong></span>1 3 -1<span style="color:#E53333;"><strong>]</strong></span> -3 5 3 6 7
</td>
<td>
-1
</td>
<td>
3
</td>
</tr>
<tr>
<td>
1 <strong><span style="color:#E53333;">[</span></strong>3 -1 -3<strong><span style="color:#E53333;">]</span></strong> 5 3 6 7
</td>
<td>
-3
</td>
<td>
3
</td>
</tr>
<tr>
<td>
1 3 <strong><span style="color:#E53333;">[</span></strong>-1 -3 5<span style="color:#E53333;"><strong>]</strong></span>3 6 7
</td>
<td>
-3
</td>
<td>
5
</td>
</tr>
<tr>
<td>
1 3 -1 <strong><span style="color:#E53333;">[</span></strong>-3 5 3<strong><span style="color:#E53333;">]</span></strong> 6 7
</td>
<td>
-3
</td>
<td>
5
</td>
</tr>
<tr>
<td>
1 3 -1 -3 <strong><span style="color:#E53333;">[</span></strong>5 3 6<strong><span style="color:#E53333;">]</span></strong> 7
</td>
<td>
3
</td>
<td>
6
</td>
</tr>
<tr>
<td>
1 3 -1 -3 5 <strong><span style="color:#E53333;">[</span></strong>3 6 7<strong><span style="color:#E53333;">]</span></strong> 
</td>
<td>
3
</td>
<td>
7
</td>
</tr>
</tbody>
</table>
<p>
<br/>
你的任务是找出窗口在各位置时的max value,min value．
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<br/>
第一行n，k，第二行为长度为n的数组
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<br/>
第一行每个位置的min value,第二行每个位置的max value
<p>
<br/>
</p>
<h3>
【输入输出样例】
</h3>
<p>
window.in<br/>
8 3<br/>
1 3 -1 -3 5 3 6 7
</p>
<p>
window.out<br/>
-1 -3 -3 -3 3 3<br/>
3 3 5 5 6 7
</p>
<h3>
【数据范围】
</h3>
<br/>
20％：n≤500； 50％：n≤100000；100％：n≤1000000；
<p>
<br/>
</p>
