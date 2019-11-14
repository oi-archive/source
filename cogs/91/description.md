# 题目描述


<h3>
【问题描述】
</h3>
<p>
设有N*N的方格图(N&lt;=10,我们将其中的某些方格中填入正整数,而其他的方格中则放入数字0。如下图所示(见样例)：
</p>
<p>
</p><table style="border-collapse:collapse;" border="1" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
</tr>
<tr>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
<b>13</b> 
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
<b>6</b> 
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
</tr>
<tr>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
<b>7</b> 
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
</tr>
<tr>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
<b>14</b> 
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
</tr>
<tr>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
<b>21</b> 
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
<b>4</b> 
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
</tr>
<tr>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
<b>15</b> 
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
</tr>
<tr>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
<b>14</b> 
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
</tr>
<tr>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
<td width="34" valign="top">
<div>
0
</div>
</td>
</tr>
</tbody>
</table>
<p></p>
<p>
某人从图的左上角的A 点出发，可以向下行走，也可以向右走，直到到达右下角的B点。在走过的路上（包括起点在内），他可以取走方格中的数(取走后的方格中将变为数字0)。
</p>
<p>
此人从A点到B 点共走两次，试找出2条这样的路径，使得取得的数之和为最大。
</p>
<h3>
【输入格式】
</h3>
<p>
输入的第一行为一个整数N(表示N*N的方格图)，接下来的每行有三个整数，前两个表示位置，第三个数为该位置上所放的数。一行单独的0表示输入结束。
</p>
<h3>
【输出格式】
</h3>
<p>
只需输出一个整数，表示2条路径上取得的最大的和。
</p>
<h3>
【样例输入】
</h3>
<pre>8
2 3 13
2 6 6
3 5 7
4 4 14
5 2 21
5 6 4
6 3 15
7 2 14
0 0 0
</pre>
<h3>
【样例输出】
</h3>
<pre>67
</pre>
