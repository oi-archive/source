# 

 
 # 题目背景 
公园里有个人在练开奔驰&nbsp;-&nbsp;-!，但是总是撞在bench上&nbsp;(众人曰：狼来了，快跑啊!) 

 
 # 题目描述 
公园里的bench与奔驰都是无敌的，不会被撞坏。<BR>由于开奔驰的人比较"有特点"，总是向上下左右四个方向开，而且只会在撞到椅子之后改变方向(起步时除外)&nbsp;-&nbsp;-!<BR>现在他给你一张地图，上面标明&nbsp;他的位置&nbsp;、&nbsp;公园里的bench的位置&nbsp;和&nbsp;他想到达的位置，可能会有冲出地图的可能<BR>请你告诉他最少撞多少下才能到达目的地，并答应事成之后会给你一辆奔驰..............................................的照片<BR> 

 
 # 输入格式 
第一行，两个数，分别表示地图的行和列，都不大于50<BR>以下是地图，"."表示地面，"S"表示起点，"E"表示终点,"B"表示bench(什么意思呢？)<BR>保证只有一个终点和一个起点，并不会出现其他字符<BR> 

 
 # 输出格式 
第一行，表示他能不能到达目的地。如果能，就输出"Yes"。否则，输出"No"<BR>如果能到达目的地，就在第二行输出最少的撞击次数 

 
 # 提示 
测试数据1：点火后直接向右走<BR>测试数据2：四个方向都会冲出地图某个经典的游戏...... 
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
<tr><td>测试数据1:
5 5
BBBBB
B...B
BSE.B
B...B
BBBBB

测试数据2:
3 3
S..
...
..E

</td><td>测试数据1：
Yes
0

测试数据2：
No

</td></tr></table>
