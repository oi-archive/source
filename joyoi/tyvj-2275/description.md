# 

 
 # 题目描述 
<p>
这里有 N 座城镇, 和城镇之间的 M 巴士单行线(没有中间停靠站)。 城镇从1到N 标号。 一个旅行者在 0时刻位于 1号城镇想要到达 P 号城镇。他将乘坐巴士在T 时刻到达P 号城镇。如果他早到了，他必须等待。<br><br>对于任意一个巴士路线i, 我们知道其中的起点城镇si 和目标城镇ti 。我们也同样知道路线的出发时间和到达时间,但仅仅是近似值：我们知道巴士离开起点城镇si 在时间范围[ai, bi]内，且到达目标城镇ti 在时间范围[ci, di]内(端点值包括在内)。<br><br>旅行者不喜欢等待, 因此他要寻找一个旅行计划使得最大等待时间尽量小，同时保证绝对不会错过计划中的任何一辆巴士(意思是, 每次他换乘巴士, 他需要下车的巴士的最晚到达时间不会迟于他需要搭乘的下一辆巴士的最早出发时间)。<br><br>当计算等待时间时，我们必须假设最早可能到达的时间和最晚可能出发的时间。<br><br>编写一个程序，寻找一个最为合理的搭车计划。<br><br></p> 

 
 # 输入格式 
<p>
The first line contains the integer numbers N (1<=N<=50,000), M (1<=M<=100,000), P ( 1<= P<= N), and T (0<=T<=1,000,000,000).<br><br>The following M lines describe the bus routes. Each line contains the integer numbers si, ti, ai, bi, ci, di, where si and ti are the source and destination towns of the bus route i, and ai, bi, ci, di describe the departure and arrival times as explained above (1 <= si<=N, 1 <=ti<=N, 0<=ai<= bi < ci<=di<=1,000,000,000).<br><br></p> 

 
 # 输出格式 
<p>
只需要包含一个数——最合理搭车方案的最长可能等待时间。如果不可能保证在T 时刻到达城市P，那么输出-1。<br></p> 

 
 # 提示 
<p>
The most pessimistic case for the optimal travel plan for the above example is as follows:<br>Time	Action<br>0…1	Wait in town 1<br>1…7	Take the bus line 3 from town 1 to town 1<br>7…8	Wait in town 1<br>8…9	Take the bus line 4 from town 1 to town 3<br>9…35	Wait in town 3<br>35…95	Take the bus line 2 from town 3 to town 2<br>95…98	Wait in town 2<br>98…99	Take the bus line 5 from town 2 to town 2<br>99…100	Wait in town 2<br>Total waiting time: 1+1+26+3+1=32<br></p> 
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
<tr><td>3 6 2 100
1 3 10 20 30 40
3 2 32 35 95 95
1 1 1 1 7 8
1 3 8 8 9 9
2 2 98 98 99 99
1 2 0 0 99 101
</td><td>32</td></tr></table>
