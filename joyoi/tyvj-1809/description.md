# 

 
 # 题目描述 
在这个繁忙的社会中，我们往往不再去选择最短的道路，而是选择最快的路线。开车时每条道路的限速成为最关键的问题。不幸的是，有一些限速的标志丢失了，因此你无法得知应该开多快。一种可以辩解的解决方案是，按照原来的速度行驶。你的任务是计算两地间的最快路线。<BR>	你将获得一现代化城市的道路交通信息。为了使问题简化，地图只包括路口和道路。每条道路是有向的，只连接了两条道路，并且最多只有一块限速标志，位于路的起点。两地A和B，最多只有一条道路从A连接到B。你可以假设加速能够在瞬间完成并且不会有交通堵塞等情况会影响你。当然，你的车速不能超过当前的速度限制。<BR> 

 
 # 输入格式 
输入文件SPEED.IN的第一行是3个整数&nbsp;N,M和D。<BR>其中：2&lt;=N&lt;=150,表示道路的数目,用0..N-1标记。M是道路的总数，D表示你的目的地。<BR>接下来的M行，每行描述一条道路：有4个整数A&nbsp;(0&lt;=&nbsp;A&nbsp;&lt;&nbsp;N),&nbsp;B&nbsp;(0&nbsp;&lt;=B&nbsp;&lt;&nbsp;N),&nbsp;V&nbsp;(0&lt;=&nbsp;V&lt;=&nbsp;500)&nbsp;and&nbsp;L&nbsp;(1&lt;=&nbsp;L&lt;=&nbsp;500),这条路是从A到B的，速度限制是V，长度为L。如果V是0，表示这条路的限速未知。如果V不为0，则经过该路的时间T=L/V。否则T&nbsp;=&nbsp;L&nbsp;/&nbsp;Vold，Vold是你到达该路口前的速度。开始时你位于0点，并且速度为70。<BR> 

 
 # 输出格式 
输出文件SPEED.OUT仅一行整数，表示从0到D经过的城市。输出的顺序必须按照你经过这些城市的顺序，以0开始，以D结束。仅有一条最快路线。<BR><BR> 

 
 # 提示 
The&nbsp;required&nbsp;time&nbsp;is&nbsp;in&nbsp;this&nbsp;case&nbsp;2,628&nbsp;units.JSOI2008江苏省青少年信息学奥林匹克代表队组队选拔赛第一轮试题 
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
<tr><td>6 15 1
0 1 25 68
0 2 30 50
0 5 0 101
1 2 70 77
1 3 35 42
2 0 0 22
2 1 40 86
2 3 0 23
2 4 45 40
3 1 64 14
3 5 0 23
4 1 95 8
5 1 0 84
5 2 90 64
5 3 36 40
</td><td>0 5 2 3 1</td></tr></table>
