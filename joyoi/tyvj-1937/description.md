# 

 
 # 题目描述 
在你的帮助下，太空战队的组建工作顺利结束了。太空战队即将开始它的第一次任务——协助打击陆上目标。要想对陆上目标进行精确的打击，首先要进行的就是地形勘探。狡猾的敌人经常利用山谷来掩护自己，并且在山峰上设立岗哨。陆军的战士历经千难万险绘制出了需要打击的区域的地图，你需要根据这个地图计算出山峰和山谷的数目。<BR>地图是一个N*N的网格，第i行第j个格子的高度h[i][j]是给出的。如果两个格子有公共顶点，我们就认为它们互为相邻的格子。所以，与(i,j)这个格子相邻的有八个格子，即：(i-1,&nbsp;j-1),(i-1,j),(i-1,j+1),(i,j-1),(i,j+1),(i+1,j-1),(i+1,j),(i+1,j+1).<BR>我们定义一个格子的集合S为“山峰”当且仅当<BR>1.S的所有格子都有相同的高度<BR>2.S的所有格子都连通（此处连通指的是八连通）<BR>3.对于所有属于S的点s，与s相邻的所有不属于S的点的高度都小于s的高度.<BR><BR>我们定义一个格子的集合S为“山谷”当且仅当<BR>1.S的所有格子都有相同的高度<BR>2.S的所有格子都连通（此处连通指的是八连通）<BR>3.对于所有属于S的点s，与s相邻的所有不属于S的点的高度都大于s的高度.<BR><BR><img src="/source/joyoi/tyvj-1937/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTkzNy9odHRwOi8vZmlsZS0wNC5ibG9nY24uY29tL3dwMDQvTTAwLzA2LzQyL3dLZ0tERkJHcnlRQUFBQUFBQUVwQ2ltSVl5MDE4NS5qcGc=.jpg" border=0 align=middle> 

 
 # 输入格式 
第一行包含一个正整数N，表示地图的大小。接下来一个N*N的矩阵，表示地图上每个格子的高度。 

 
 # 输出格式 
一行两个用空格隔开的数，分别表示山峰和山谷的数量。 

 
 # 提示 
如图所示，虚线圈表示的是山谷，实线圈表示的是山峰。　　　<BR>对于50%的数据，N&lt;=100.<BR>对于100%的数据，N&lt;=1000,&nbsp;0&lt;=格子的高度&lt;=10^9. 
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
<tr><td>5
5 7 8 3 1
5 5 7 6 6
6 6 6 2 8
5 7 2 5 8
7 1 0 1 7</td><td>3 3</td></tr></table>
