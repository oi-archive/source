# 

 
 # 题目描述 
<p>
<br>John在他的农场中闲逛时发现了许多虫洞。虫洞可以看作一条十分奇特的有向边，并可以使你<br>返回到过去的一个时刻（相对你进入虫洞之前）。John的每个农场有M条小路（无向边)连接着N<br>（从1..N标号）块地，并有W个虫洞。其中1<=N<=500,1<=M<=2500,1<=W<=200。<br><br>现在John想借助这些虫洞来回到过去（出发时刻之前），请你告诉他能办到吗。<br>John将向你提供F(1<=F<=5)个农场的地图。没有小路会耗费你超过10000秒的时间，当然也没有<br>虫洞回帮你回到超过10000秒以前。<br></p> 

 
 # 输入格式 
<p>
* Line 1: 一个整数 F, 表示农场个数。<br><br>* Line 1 of each farm: 三个整数 N, M, W。<br><br>* Lines 2..M+1 of each farm: 三个数（S, E, T）。表示在标号为S的地与标号为E的地<br>中间有一条用时T秒的小路。<br>* Lines M+2..M+W+1 of each farm: 三个数（S, E, T）。表示在标号为S的地与标号为E的地<br>中间有一条可以使John到达T秒前的冲动。<br></p> 

 
 # 输出格式 
<p>
<br>* Lines 1..F: 如果John能在这个农场实现他的目标，输出"YES",否则输出"NO"。<br><br><br></p> 
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
<tr><td>
2
3 3 1
1 2 2
1 3 4
2 3 1
3 1 3
3 2 1
1 2 3
2 3 4
3 1 8

</td><td>
NO
YES</td></tr></table>
