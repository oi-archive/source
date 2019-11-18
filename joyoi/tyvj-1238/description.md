# 

 
 # 题目背景 
tyvj20100619比赛,祝大家取得好成绩。^-^<BR> 

 
 # 题目描述 
图是由一组顶点和一组边组成的。一条边连接两个顶点。例如，图1表示了一个有4个顶点V、5条边的图。图中，每条边e是有方向的，方向从起点到终点，并且每条边都有价值。用整数0,1,…,m-1可以表示一个有m个顶点的图。<BR><img src="/source/joyoi/tyvj-1238/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTIzOC9wcm9ibGVtaW1nLzEyMzguanBn.jpg" border=0 align=middle><BR>图1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;图2<BR>一条路径连接了一个点Vi和另一个点Vj，其方向与经过的一系列边的方向一致。路径的长度是途经边的条数，路径的费用是边价值的总和。对于一个给定的图，你的任务是在所有最短路径中，找出需要最少费用的连接V0和V1的路径。一个需要最少费用的最短路径称之为廉价最短路径。<BR><BR>让我们重新考虑图1，从0到1的最短路径是只含一条边的路径0→1，费用是10。当然，还有更便宜的路：0→2→1和&nbsp;0→3→1，但是它们比第一条路径长(有2条边)。所以，0→1是廉价最短路径。<BR>看一下另一个例子，图2，它有2条最短路径，其长度是2，路径0→3→1(费用=4)比路径0→2→1(费用=5)花费少。还用另一条路径0→2→3→1(费用=3)，虽然便宜但是很长。所以，廉价最短路径是0→3→1。<BR> 

 
 # 输入格式 
输入文件第一行有两个整数m和n，用一个空格隔开，其中，m是顶点数，而n是边数。接下来的n行给出所有的边及其价值，每行有3个整数(相邻两个整数间有一个空格)，表示起点，终点和边的价值。顶点最多有100个，编号在0到99之间。边最多有1000条，其价值在0到215-1之间。 

 
 # 输出格式 
输出文件仅有一行包含一个整数，即V0→V1的廉价最短路径的费用。当出现有多个廉价最短路径的情况时，它们的费用是一样的。 
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
<tr><td>4 5
0 2 2
0 3 2
0 1 10
2 1 2
3 1 2
</td><td>10</td></tr></table>
