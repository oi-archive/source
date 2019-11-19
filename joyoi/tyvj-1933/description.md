# 

 
 # 题目背景 
随着新版百度空间的上线，Blog宠物绿豆蛙完成了它的使命，去寻找它新的归宿。 

 
 # 题目描述 
给出一个有向无环图，起点为1终点为N，每条边都有一个长度，并且从起点出发能够到达所有的点，所有的点也都能够到达终点。绿豆蛙从起点出发，走向终点。<BR>到达每一个顶点时，如果有K条离开该点的道路，绿豆蛙可以选择任意一条道路离开该点，并且走向每条路的概率为&nbsp;1/K&nbsp;。<BR>现在绿豆蛙想知道，从起点走到终点的所经过的路径总长度期望是多少？ 

 
 # 输入格式 
第一行:&nbsp;两个整数&nbsp;N&nbsp;M，代表图中有N个点、M条边<BR>第二行到第&nbsp;1+M&nbsp;行:&nbsp;每行3个整数&nbsp;a&nbsp;b&nbsp;c，代表从a到b有一条长度为c的有向边<BR> 

 
 # 输出格式 
从起点到终点路径总长度的期望值，四舍五入保留两位小数。 

 
 # 提示 
对于20%的数据&nbsp;&nbsp;&nbsp;N&lt;=100<BR>对于40%的数据&nbsp;&nbsp;&nbsp;N&lt;=1000<BR>对于60%的数据&nbsp;&nbsp;&nbsp;N&lt;=10000<BR>对于100%的数据&nbsp;&nbsp;N&lt;=100000，M&lt;=2*N<BR> 
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
<tr><td>4 4
1 2 1
1 3 2
2 3 3
3 4 4
</td><td>7.00</td></tr></table>
