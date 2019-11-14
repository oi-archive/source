# 题目描述


<p>
现在有一条“叶卡特琳堡－斯维尔德洛夫斯克”铁路线。它有若干个火车站。这个铁路线可以用一条线段来表示，而火车站就是线段上的点。铁路起始于叶卡特琳堡(Eakterinburg)，终止于斯维尔德洛夫斯克(Sverlovsk)，且各站从叶卡特琳堡(它的编号是1)至斯维尔德洛夫斯克(终点编号)。
</p>
<img alt="" src="../../mw/images/8/8b/Ural_rail.png"/><br/>
<p>
<br/>
</p>
两个站之间的票价仅跟两站间的距离有关系。票价规定如下表。
<table border="1" cellpadding="9" cellspacing="1" width="473">
<tbody>
<tr>
<td valign="top" width="50%">
<span> </span> 
<p align="center">
<span>两站间距离 - <i>X</i></span> 
</p>
</td>
<td valign="top" width="50%">
<p align="center">
<span>票价</span> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<span> </span> 
<p align="center">
<span>0&lt;<i>X</i>&lt;=<i>L<sub>1</sub></i></span> 
</p>
</td>
<td valign="top" width="50%">
<i><span> </span></i> 
<p align="center">
<i><span>C<sub>1</sub></span></i> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<i><span> </span></i> 
<p align="center">
<i><span>L<sub>1</sub></span></i><span>&lt;<i>X</i>&lt;=<i>L<sub>2</sub></i></span> 
</p>
</td>
<td valign="top" width="50%">
<i><span> </span></i> 
<p align="center">
<i><span>C<sub>2</sub></span></i> 
</p>
</td>
</tr>
<tr>
<td valign="top" width="50%">
<i><span> </span></i> 
<p align="center">
<i><span>L<sub>2</sub></span></i><span>&lt;<i>X</i>&lt;=<i>L<sub>3</sub></i></span> 
</p>
</td>
<td valign="top" width="50%">
<i><span> </span></i> 
<p align="center">
<i><span>C<sub>3</sub></span></i> 
</p>
</td>
</tr>
</tbody>
</table>
<p>
<br/>
</p>
<p>
当且仅当两站间距离不大于L3时才能购买这两站之间的直达车票。所以有时须要购买若干张票来完成整个旅行。
</p>
<p>
<br/>
</p>
<p>
例如，在上图，整条铁路有七个站。从第2站不能直达第6站(因为距离大于L3)，但有另外几种方法购票。其中一种是买两张票：一张是从第2站至第3站(票价为C2)，另一张是从第3站至第6站(票价为C3)，注意，虽然从第2站至第6站的距离为2×L2，但不可以买两张价值C2的票，因为一张票只可以用一次且起点和终点必须在车站上。
</p>
<p>
<br/>
</p>
<p>
你的任务时计算给出的两站之间的最小花费。
</p>
<h2 style="color:#1A5CC8;">
输入
</h2>
<p>
输入的第一行包含六个由空格隔开的整数L1，L2，L3，C1，C2，C3(1&lt;=L1&lt;L2&lt;L3&lt;=10^9，1&lt;=C1&lt;C2&lt;C3&lt;=10^9)。第二行为车站数N(2&lt;=N&lt;=10000)。第三行有两个由空格隔开的不等的整数，表示旅行起点和终点。接下来的N-1行为起点(叶卡特琳堡)至其它站的距离。这些距离为互不相等的正整数而且呈上升序列。从叶卡特琳堡至斯维尔德洛夫斯克的距离不超过10^9。任意两相邻站之间的距离不超过L3。旅行最小花费不超过10^9。<l2<l3<=10^9，1<=c1<c2<c3<=10^9)。第二行为车站数n(2<=n<=10000)。第三行有两个由空格隔开的不等的整数，表示旅行起点和终点。接下来的n-1行为起点(叶卡特琳堡)至其它站的距离。这些距离为互不相等的正整数而且呈上升序列。从叶卡特琳堡至斯维尔德洛夫斯克的距离不超过10^9。任意两相邻站之间的距离不超过l3。旅行最小花费不超过10^9。< p=""></l2<l3<=10^9，1<=c1<c2<c3<=10^9)。第二行为车站数n(2<=n<=10000)。第三行有两个由空格隔开的不等的整数，表示旅行起点和终点。接下来的n-1行为起点(叶卡特琳堡)至其它站的距离。这些距离为互不相等的正整数而且呈上升序列。从叶卡特琳堡至斯维尔德洛夫斯克的距离不超过10^9。任意两相邻站之间的距离不超过l3。旅行最小花费不超过10^9。<>
</p>
<h2 style="color:#1A5CC8;">
输出
</h2>
<p>
一个整数------最小花费。
</p>
<h2 style="color:#1A5CC8;">
样例输入
</h2>
<pre>3 6 8 20 30 40
7
2 6
3
7
8
13
15
23

</pre>
<h2 style="color:#1A5CC8;">
样例输出
</h2>
<pre>70</pre>
