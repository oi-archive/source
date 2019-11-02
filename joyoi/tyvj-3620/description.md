# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-3620/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzYyMC9wcm9ibGVtc19pbWFnZXMvMjQ3My8xMTc5LmpwZw==.jpg"><br></p> 

 
 # 输入格式 
<p>
第一行包含两个整数N、M。N表示路口的个数，M表示道路条数。接下来M行，每行两个整数，这两个整数都在1到N之间，第i+1行的两个整数表示第i条道路的起点和终点的路口编号。接下来N行，每行一个整数，按顺序表示每个路口处的ATM机中的钱数。接下来一行包含两个整数S、P，S表示市中心的编号，也就是出发的路口。P表示酒吧数目。接下来的一行中有P个整数，表示P个有酒吧的路口的编号</p> 

 
 # 输出格式 
<p>
输出一个整数，表示Banditji从市中心开始到某个酒吧结束所能抢劫的最多的现金总数。</p> 

 
 # 提示 
<p>
50%的输入保证N, M<=3000。所有的输入保证N, M<=500000。每个ATM机中可取的钱数为一个非负整数且不超过4000。输入数据保证你可以从市中心沿着Siruseri的单向的道路到达其中的至少一个酒吧。</p> 
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
<tr><td>6 7
1 2
2 3
3 5
2 4
4 1
2 6
6 5
10
12
8
16
1 5
1 4
4
3
5
6</td><td>
47</td></tr></table>
