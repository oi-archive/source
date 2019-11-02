# 

 
 # 题目背景 
清北学堂杯NOIP模拟赛第四道<BR> 

 
 # 题目描述 
随着航空业的不断发展，且面对不断攀升的油价，航空公司不得不要学会精打细算。某导航公司在调研中发现，各城市加油站的售价不尽相同，因此飞行路线规划是否合理直接决定油费的开销。于是他们瞄准这个商机，着手在导航仪中加入为用户提示油费开销最低路线的功能。为此，他们将问题抽象描述为图：加油站对应于节点，加油站之间的航线对应于边。为简单起见，假定每次飞行的起点和终点本身都是加油站，油耗线性正比于路程长度而与方向无关。 

 
 # 输入格式 
第一行为两个整数n&nbsp;和m，表示共有n&nbsp;个加油站以及m&nbsp;条联接于其间的航线。<BR>以下n&nbsp;行各用一个整数pi&nbsp;给出第i&nbsp;个加油站的油价，1&nbsp;≤&nbsp;pi&nbsp;&lt;&nbsp;100，0&nbsp;≤&nbsp;i&nbsp;&lt;&nbsp;n。<BR>再以下m&nbsp;行各用三个整数i、j&nbsp;和dij&nbsp;给出加油站i与j之间航线的长度（即对应的油耗）dij，其中0&nbsp;≤&nbsp;i&nbsp;&lt;&nbsp;j&nbsp;&lt;&nbsp;n，0&nbsp;&lt;&nbsp;dij&nbsp;&lt;&nbsp;200。<BR>接下来一行用一个整数q&nbsp;表示查询次数。<BR>以下q&nbsp;行各用三个整数c、s&nbsp;和t（1&nbsp;≤&nbsp;c&nbsp;≤&nbsp;100，0&nbsp;≤&nbsp;s&nbsp;&lt;&nbsp;n，0&nbsp;≤&nbsp;t&nbsp;&lt;&nbsp;n）表示一次查询：对于油箱容量为c&nbsp;且初始为空的飞机，计算其从s&nbsp;号加油站到t&nbsp;号加油站最经济的航线。<BR> 

 
 # 输出格式 
对于每一查询，输出对应的最低煤油花费；如果不存在这样的航线，那么输出‐1。 

 
 # 提示 
1&nbsp;≤&nbsp;n&nbsp;≤&nbsp;500，1&nbsp;≤&nbsp;m&nbsp;≤&nbsp;5,000，1&nbsp;≤&nbsp;q&nbsp;&lt;&nbsp;1000 
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
<tr><td>3 3
20
10
30
0 1 10
1 2 15
0 2 20
2
20 0 2
5 1 2</td><td>350
-1</td></tr></table>
