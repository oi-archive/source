# 

 
 # 题目描述 
<p>
N(1 ≤ N ≤ 1000)个农场中的每个农场都有一只奶牛去参加位于第X个农场的聚会.共有M (1 ≤ M ≤ 100,000)条单向的道路,每条道路连接一对农场.通过道路i会花费Ti (1 ≤ Ti ≤ 100)的时间. <br><br>作为参加聚会的奶牛必须走到聚会的所在地(农场X).当聚会结束时,还要返回各自的农场.奶牛都是很懒的,她们想找出花费时间最少的路线.由于道路都是单向的,所有她们前往农场X的路线可能会不同于返程的路线. <br><br>Of all the cows, what is the longest amount of time a cow must spend walking to the party and back? 对于所有参加聚会的奶牛,找出前往聚会和返程花费总时间最多的奶牛,输出这只奶牛花费的总时间. <br><br><br></p> 

 
 # 输入格式 
<p>
第1行:三个用空格隔开的整数. <br>第2行到第M+1行,每行三个用空格隔开的整数:Ai, Bi,以及Ti.表示一条道路的起点,终点和需要花费的时间. <br><br><br></p> 

 
 # 输出格式 
<p>
唯一一行:一个整数: 所有参加聚会的奶牛中,需要花费总时间的最大值. <br></p> 
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
<tr><td>4 8 2
1 2 4
1 3 2
1 4 7
2 1 1
2 3 5
3 1 2
3 4 4
4 2 3
</td><td>
10
样例说明: 

共有4只奶牛参加聚会,有8条路,聚会位于第2个农场. 

第4只奶牛可以直接到聚会所在地(花费3时间),然后返程路线经过第1和第3个农场(花费7时间),总共10时间. </td></tr></table>
