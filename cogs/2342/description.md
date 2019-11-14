# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<p>
有n个城市和m条单向道路，城市编号为1~n。每条道路连接两个不同的城市，且任意两条道路要么起点不同要么终点不同，因此n和m满足m&lt;=n(n-1)。给定两个城市a和b，可以给a到b的所有简单路（所有城市最多经过一次，包括起点和终点）排序：先按长度从小到大排序，长度相同时按照字典序从小到大排序。你的任务是求出a到b的第k短路。
</p>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
输入第一行包含五个正整数n, m, k, a, b。以下m行每行三个整数u, v, l，表示从城市u到城市v有一条长度<br/>
为l的单向道路。100%的数据满足：2&lt;=n&lt;=50, 1&lt;=k&lt;=200
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
如果a到b的简单路不足k条，输出No，否则输出第k短路：从城市a开始依次输出每个到达的城市，直到城市b，中间用减号&#34;-&#34;分割。
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>【样例输入1】
  5 20 10 1 5
  1 2 1
  1 3 2
  1 4 1
  1 5 3
  2 1 1
  2 3 1
  2 4 2
  2 5 2
  3 1 1
  3 2 2
  3 4 1
  3 5 1
  4 1 1
  4 2 1
  4 3 1
  4 5 2
  5 1 1
  5 2 1
  5 3 1
  5 4 1
  【样例输入2】
  4 6 1 1 4
  2 4 2
  1 3 2
  1 2 1
  1 4 3
  2 3 1
  3 4 1
  【样例输入3】
  3 3 5 1 3
  1 2 1
  2 3 1
  1 3 1</pre>
<h3>
【样例输出】
</h3>
<pre>【样例输出1】
  1-2-4-3-5
  【样例输出2】
  1-2-3-4
  【样例输出3】
  No</pre>
<h3>
【提示】
</h3>
<div class="content">
<p>
<br/>
</p>
<p>
<span style="font-size:medium;">第一个例子有5个城市，所有可能出现的道路均存在。从城市1到城市5一共有5条简单路</span> 
</p>
<p>
<span style="font-size:medium;"></span> 
</p>
<p>
</p><table width="253" class="ke-zeroborder" style="border-collapse:collapse;width:190pt;" border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td width="72" height="18">
序号
</td>
<td width="72">
长度
</td>
<td width="109">
路径
</td>
</tr>
<tr>
<td height="18" align="right">
1
</td>
<td align="right">
3
</td>
<td>
 1-2-3-5
</td>
</tr>
<tr>
<td height="18" align="right">
2
</td>
<td align="right">
3
</td>
<td class="xl63">
 1—2—5
</td>
</tr>
<tr>
<td height="18" align="right">
3
</td>
<td align="right">
3
</td>
<td>
 1—3—5
</td>
</tr>
<tr>
<td height="18" align="right">
4
</td>
<td align="right">
3
</td>
<td>
 1—4—3—5
</td>
</tr>
<tr>
<td height="18" align="right">
5
</td>
<td align="right">
3
</td>
<td>
 1—4—5
</td>
</tr>
<tr>
<td height="18" align="right">
6
</td>
<td align="right">
3
</td>
<td>
 1—5
</td>
</tr>
<tr>
<td height="18" align="right">
7
</td>
<td align="right">
4
</td>
<td>
 1—4—2—3—5
</td>
</tr>
<tr>
<td height="18" align="right">
8
</td>
<td align="right">
4
</td>
<td>
 1—4—2—5
</td>
</tr>
<tr>
<td height="18" align="right">
9
</td>
<td align="right">
5
</td>
<td>
 1—2—3—4—5
</td>
</tr>
<tr>
<td height="18" align="right">
10
</td>
<td align="right">
5
</td>
<td>
1—2—4—3—5
</td>
</tr>
<tr>
<td height="18" align="right">
11
</td>
<td align="right">
5
</td>
<td>
1—2—4—5
</td>
</tr>
<tr>
<td height="18" align="right">
12
</td>
<td align="right">
5
</td>
<td>
1—3—4—5
</td>
</tr>
<tr>
<td height="18" align="right">
13
</td>
<td align="right">
6
</td>
<td>
1—3—2—5
</td>
</tr>
<tr>
<td height="18" align="right">
14
</td>
<td align="right">
6
</td>
<td>
1—3—4—2—5
</td>
</tr>
<tr>
<td height="18" align="right">
15
</td>
<td align="right">
6
</td>
<td>
1—4—3—2—5
</td>
</tr>
<tr>
<td height="18" align="right">
16
</td>
<td align="right">
8
</td>
<td>
1—3—2—4—5
</td>
</tr>
</tbody>
</table>
<p></p>
<p>
<br/>
</p>
<p>
<br/>
</p>
</div>
<h3>
【来源】
</h3>
<p>
<br/>
</p>
<p>
这道题只是由于做题人被坑了好长时间才弄上来的，数据来自Tyvj极其丧心病狂因此把内存开到 1G ，希望大家嚎嚎享受。
</p>
<p>
然而事实证明即使内存开到1G也还是过不了第⑥个点，希望能看到不打表的 袋马 。_(:з」∠)_
</p>
<p>
<br/>
</p>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=1073">耒阳大世界（衡阳八中） OJ 1073</a>
