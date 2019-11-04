# 

 
 # 题目描述 
Rainbow和Freda在掷骰子的时候rp爆发，居然掷出了满点&gt;&lt;（其实我就不说所有的a[i]都是1），顺利到达了环岛旁。它们正观察着这个环岛的时候，环岛居然开口说话了T_T：<br>欢迎来到魔界环岛。我会告诉你们环岛的运行方式，并且邀请你们帮我解决一个问题。环岛在东西南北四个方向分别有一个入口和出口，环岛内的车辆逆时针行驶。车辆可以进入、离开环岛或者在环岛内行进一步，这三种操作每次都是耗时1秒。在环岛内行进一步，即从东走到北，从北走到西，从西走到南或者从南走到东（换句话说，行进两步就可以围绕环岛走半圈了）。如果操作不互相干扰，所有车辆的操作可以同时进行。比如，环岛上有两辆车，一辆在另一辆的后面，它们可以一起在环岛内行进一步。一辆车是否进入环岛取决于它们这一秒是否可以进入，如果此时可以进入，它一定会进入，否则就将加入或者停留在该方向的等待序列中。每个方向的等待序列是按照车辆到达的时间从早到晚排序的，任何一辆车都不可能“插队”。<br>什么时候一辆车可以进入环岛呢？这取决于它上一秒得到的信息。如果第i-1秒时，它所在方向的顺时针紧邻方向的环岛上和等待序列里面都没有车，而且它是所在方向等待序列的第一辆车，那么它在第i秒可以进入环岛。特别地，四个方向的等待序列里都有车的时候，北面的车优先行驶——即只要第i-1秒时东面环岛上没有车，第i秒的时候，北面等待的第一辆车就可以进入环岛了；当然，如果第i秒的时候东面环岛上有车，所有等待车辆将一直等待，直到东面环岛上没有车的时候，北面等待的第一辆车才可以通行。<br>当然，每个车辆都有一个目标方向，一旦一辆车A到达了目标方向，它就会马上离开环岛。注意，如果此时它的目标方向有另一辆车B在等待进入环岛且B车这时可以进入环岛，A车离开环岛和B车进入环岛是发生在同一秒的。<br>“我将给你们每秒车辆到达环岛旁的信息，请你们帮我计算，最后一辆车离开环岛的时间好吗？”<br><br><br> 

 
 # 输入格式 
四行，每行一个字符串。<br>第一行一个字符串N，只含有‘-’，‘S’,‘W’,‘E’四种字符，字符串的第i个字符N[i]表示第i-1秒的时候，有一辆来自北方向、目标方向为N[i]的车等待进入环岛，如果N[i]=’-＇，表示第i-1秒没有车来自北方向。<br>第二行一个字符串E，只含有&nbsp;‘-’，‘S’,‘W’,‘N’四种字符，含义同上。<br>第三行一个字符串S，只含有&nbsp;‘-’，‘N’,‘W’,‘E’四种字符，含义同上。<br>第四行一个字符串W，只含有&nbsp;‘-’，‘S’,‘N’,‘E’四种字符，含义同上。<br>对于字符串中的字符，N表示北方向，E表示东方向，W表示西方向，S表示南方向。<br><br><br> 

 
 # 输出格式 
一行一个整数totalTime，表示最后一辆车离开环岛的时间。<br><br> 

 
 # 提示 
样例解释<br>样例1如图所示：<br><img src="/source/joyoi/tyvj-2047/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjA0Ny9odHRwOi8vZmlsZS0wNC5ibG9nY24uY29tL3dwMDQvTTAwLzA2LzgyL3dLZ0tERkNSM0RrQUFBQUFBQUFUR0R6YmNtNDcxNC5naWY=.gif" border=0 align=middle><br><br>数据范围与约定<br>对于50%的数据，每个字符串长度&lt;=10.<br>对于100%的数据，0&lt;每个字符串长度&lt;=100.<br><br><br>From&nbsp;-&nbsp;This_poet<br>Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br>This_poet's&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com<br><br> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>样例输入1
--
--
WE
-S

样例输入2
ES
N
E
--


</td><td>样例输出1
6
样例输出2
9


</td></tr></table>