# 题目描述


<p>
 
</p>
<p>
<b>【问题描述</b>】
</p>
<div>
对大学生来说，ZSUCPC是一个年度活动。在活动中他们可以挑战编程技巧，发展他们之间的友谊。今年的活动就要举行了。组织者和评判们忙于活动的准备工作。许多工作队都进入实验室进行备战。为了让人们工作的更高效，Bea博士为此作了一个计划。<br/>
首先，Bea博士为每一个队评估工作时间。根据他们的提交申请，他想p[i]秒是第i队所需要的时间。Bea博士给第i队一个时间r[i]，在这个时间第i队必须准备工作。例如：<br/>
 
</div>
<p>
</p><table width="243" border="1">
<tbody>
<tr>
<td width="56">
<div align="center">
I
</div>
</td>
<td width="47">
<div align="center">
0
</div>
</td>
<td width="31">
<div align="center">
1
</div>
</td>
<td width="34">
<div align="center">
2
</div>
</td>
<td width="41">
<div align="center">
3
</div>
</td>
</tr>
<tr>
<td>
<div align="center">
p[i]
</div>
</td>
<td>
<div align="center">
4
</div>
</td>
<td>
<div align="center">
2
</div>
</td>
<td>
<div align="center">
6
</div>
</td>
<td>
<div align="center">
5
</div>
</td>
</tr>
<tr>
<td>
<div align="center">
r[i]
</div>
</td>
<td>
<div align="center">
0
</div>
</td>
<td>
<div align="center">
1
</div>
</td>
<td>
<div align="center">
3
</div>
</td>
<td>
<div align="center">
5
</div>
</td>
</tr>
</tbody>
</table>
<p></p>
<div>
 
</div>
<div>
在这个例子中，0队可以在开始就进行他们的工作（时间0意味着一天的开始），并且必须在4秒内完成他们的工作，1队不能在1秒以前工作，但可以在这个时间后工作，等等。
</div>
<div>
不同的队有不同的任务，包括放置课桌，安装系统等等。为避免矛盾，在任何时间Bea博士只允许一个队进入实验室。
</div>
<div>
最后，Bea博士为每一个队设置一个保留时间d[i]。因为保留时间来自于Bea博士的评估，所以计划表不可能满足所有工作队的需要。所以结束点每个队是不同的，这取决于完成时间和评估时间。设想一个队在s秒开始工作，他们将在s+p秒完成工作。如果他们的评估时间是d，他们的延迟时间是(s+p)-d,如此处理，四个队的评估时间如下所示：<br/>
 
</div>
<p>
</p><table width="243" border="1">
<tbody>
<tr>
<td width="56">
<div align="center">
I
</div>
</td>
<td width="47">
<div align="center">
0
</div>
</td>
<td width="31">
<div align="center">
1
</div>
</td>
<td width="34">
<div align="center">
2
</div>
</td>
<td width="41">
<div align="center">
3
</div>
</td>
</tr>
<tr>
<td>
<div align="center">
d[i]
</div>
</td>
<td>
<div align="center">
8
</div>
</td>
<td>
<div align="center">
12
</div>
</td>
<td>
<div align="center">
11
</div>
</td>
<td>
<div align="center">
10
</div>
</td>
</tr>
</tbody>
</table>
<p></p>
<div>
我们有许多不同的策略建立计划表。按照顺序，我们可以让0队在0秒到4秒工作，1队在4秒到6秒工作，3队在6秒到12秒工作，4队在12秒到17秒工作。他们的延迟时间是-4，-6，1 和 7。四个队的最大延迟时间是7,是3号队。但如果把戏2队放在最后。他们的最大延迟时间将是5.现在Bea博士很在意所有队的最大延迟时间，他想设计一个计划表尽量降低最大延迟时间。
</div>
<div>
【输入格式】
</div>
<div>
n<br/>
p1p2…pn<br/>
r1r2…rn<br/>
d1d2…dn
</div>
<div>
输入文件由多个测试数据组成,(所有数据都是整数),每个测试数据由包括4行,第一行有一个整数n,表示队的数量(n≤100)．第二行的个整数是每队的工作时间，第三行的n个整数是每队的准备时间，第四行的n个整数是每个队的评估时间。所有这些整数都不超过1000。输入文件以单独一行0表示结束.
</div>
<div>
【输出格式】
</div>
<p>
   对于每个测试数据输出单独一个整数，计划表中的最大延迟时间。
</p>
<div>
【输入样例】
</div>
<div>
<p>
输入文件名：<span>preparation.in</span>
</p>
<p>
4
</p>
<p>
4 2 6 5
</p>
<p>
0 1 3 5
</p>
<p>
8 12 11 10
</p>
<p>
0
</p>
</div>
<div>
输出文件名：<span> <span>preparation.out</span></span>
</div>
<div>
<span>5</span>
</div>
