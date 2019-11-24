# 

 
 # 题目描述 
<p>
Alice和Bob在玩这样一种游戏：首先，Alice画一个N个顶点M条边的有向图,然后让Bob删去图中所有的边。规则是每步Bob选择一个顶点，然后或者所有指向这个顶点的有向边被删去(操作一)，或者所有以这个顶点为起始的有向边被删去(操作二)。<br>Alice分配两种代价到每一个顶点: Wi+ 和 Wi-. 如果Bob对顶点i执行操作一,那么他将花费$Wi+，反之他将花费$Wi-<br>请你试着帮Bob找出删去图中所有边的最小花费。<br></p> 

 
 # 输入格式 
<p>
每组输入数据第一行包括N，M(1 <= N <= 100, 1 <= M <= 5000).第二行包括N个整数Wi+.第三行包括N个整数Wi-.所有花费都是正的且不超过10^6.紧跟着M行，每行包括两个整数a, b表示由a向b连接一条有向边.注意，两个顶点间可能有不止一条边，且图中亦存在环.<br></p> 

 
 # 输出格式 
<p>
输出数据第一行包括一个整数W,Bob的最小花费</p> 
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
<tr><td>3 6
1 2 3
4 2 1
1 2
1 1
3 2
1 2
3 1
2 3
</td><td>5</td></tr></table>
