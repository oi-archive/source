# 

 
 # 题目描述 
“封印大典启动，请出Nescafe魂珠！”随着圣主applepi一声令下，圣剑护法rainbow和魔杖护法freda将Nescafe魂珠放置于封印台上。封印台是一个树形的结构，魂珠放置的位置就是根节点（编号为0）。还有n个其它节点（编号1~n）上放置着封印石，编号为i的封印石需要从魂珠上获取Ei的能量。能量只能沿着树边从魂珠传向封印石，每条边有一个能够传递的能量上限Wi，魂珠的能量是无穷大的。作为封印开始前的准备工作，请你求出最多能满足多少颗封印石的能量需求？<br>注意：能量可以经过一个节点，不满足它的需求而传向下一个节点。每条边仅能传递一次能量。 

 
 # 输入格式 
第一行一个整数n，表示除根节点之外其它节点的数量。<br>接下来n行，第i+1行有三个整数Fi、Ei、Wi，分别表示i号节点的父节点、i号节点上封印石的能量需求、连接节点i与Fi的边最多能传递多少能量。 

 
 # 提示 
对于&nbsp;100%&nbsp;的数据，满足1&lt;=n&lt;=1000，0&lt;=Fi&lt;=n，0&lt;=Ei,Wi&lt;=100。 
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
<tr><td>4
0 3 2
0 100 100
1 1 1
2 75 80</td><td>2</td></tr></table>
