# 题目描述


<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
<h3>
【试题来源】
</h3>
<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
小T的城市刚刚开始推行BRT（Bus Rapid Transit），其实，就是一种公交车。<br/>
BRT有N个站台，分别编号为1到N，按照列车通过的顺序递增排列。在列车到站时，会有一些乘客上车，也会有一些乘客下车。<br/>
由于BRT内空间狭小，乘客完全无法走动，在车上只有靠近车门的乘客才能够下车。和大部分公交车一样，BRT有2个车门——前门和后门。每一个上车的乘客可以选择从前门或者后门上车。<br/>
现在有M个乘客，编号为1到M，每个人都有各自的起点和终点，现在，需要聪明的你来安排一种上下车的方案，使得每个乘客都能够在各自的终点下车。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
第一行是两个整数N,M。下面依次有M行，每行有两个整数，表示一个乘客的起点和终点。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出你的方案：<br/>
<table cellspacing="0" cellpadding="2px" align="center" style="border-collapse:collapse;border:none;">
<tbody>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
1 X<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
编号为X的乘客从前门上车<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
2 X<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
编号为X的乘客从后门上车<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td valign="top" style="border:solid 1.0pt;">
3 X<br/>
</td>
<td valign="top" style="border:solid 1.0pt;">
编号为X的乘客下车<br/>
</td>
</tr>
</tbody>
</table>
<br/>
输出包括2M行，每行一种操作
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
5 7<br/>
1 3<br/>
1 2<br/>
2 3<br/>
2 4<br/>
4 5<br/>
3 5<br/>
3 5
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
1 1<br/>
1 2<br/>
3 2<br/>
2 4<br/>
1 3<br/>
3 3<br/>
3 1<br/>
1 7<br/>
1 6<br/>
3 4<br/>
1 5<br/>
3 7<br/>
3 6<br/>
3 5
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于100%的数据满足1≤n,m≤200
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p>
【问题描述】
</p>
<p>
小T的城市刚刚开始推行BRT（Bus Rapid Transit），其实，就是一种公交车。
</p>
<p>
BRT有N个站台，分别编号为1到N，按照列车通过的顺序递增排列。在列车到站时，会有一些乘客上车，也会有一些乘客下车。
</p>
<p>
由于BRT内空间狭小，乘客完全无法走动，在车上只有靠近车门的乘客才能够下车。和大部分公交车一样，BRT有2个车门——前门和后门。每一个上车的乘客可以选择从前门或者后门上车。
</p>
<p>
现在有M个乘客，编号为1到M，每个人都有各自的起点和终点，现在，需要聪明的你来安排一种上下车的方案，使得每个乘客都能够在各自的终点下车。
</p>
<p>
【输入格式】
</p>
<p>
第一行是两个整数N,M。下面依次有M行，每行有两个整数，表示一个乘客的起点和终点。
</p>
<p>
【输出格式】
</p>
<p>
输出你的方案：
</p>
<div align="center">
<table border="1" cellspacing="0" cellpadding="0" width="461">
<tbody>
<tr>
<td valign="top" width="105">
<p>
1 X
</p>
</td>
<td valign="top" width="356">
<p>
编号为X的乘客从前门上车
</p>
</td>
</tr>
<tr>
<td valign="top" width="105">
<p>
2 X
</p>
</td>
<td valign="top" width="356">
<p>
编号为X的乘客从后门上车
</p>
</td>
</tr>
<tr>
<td valign="top" width="105">
<p>
3 X
</p>
</td>
<td valign="top" width="356">
<p>
编号为X的乘客下车
</p>
</td>
</tr>
</tbody>
</table>
</div>
<p>
输出包括2M行，每行一种操作
</p>
<p>
【样例输入】
</p>
<p>
5 7
</p>
<p>
1 3
</p>
<p>
1 2
</p>
<p>
2 3
</p>
<p>
2 4
</p>
<p>
4 5
</p>
<p>
3 5
</p>
<p>
3 5
</p>
<p>
【样例输出】
</p>
<p>
1 1
</p>
<p>
1 2
</p>
<p>
3 2
</p>
<p>
2 4
</p>
<p>
1 3
</p>
<p>
3 3
</p>
<p>
3 1
</p>
<p>
1 7
</p>
<p>
1 6
</p>
<p>
3 4
</p>
<p>
1 5
</p>
<p>
3 7
</p>
<p>
3 6
</p>
<p>
3 5
</p>
<p>
【数据范围】
</p>
<p>
对于100%的数据满足1≤n,m≤200
</p>
</div>
</div>
