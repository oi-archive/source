# 

 
 # 题目背景 
阴森的蛇灵迷宫地下，怎么会有背景呢。。？<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;李元芳和闪灵在打斗中不慎掉入了蛇灵总坛地下的迷宫，十分恐惧~~~&nbsp;迷宫是由n个点组成的，他们停留在1号点，规定他们两个人在一起，每个人轮流决定下一步怎么走，并且只能从序号小的点走向序号大的点，最后无法决定接下来怎么走(走到死路)的人会被处死，另一个人得以逃生。<BR>&nbsp;&nbsp;&nbsp;&nbsp;在这个危机的时刻，拿到地图的李元芳必须以迅雷不及掩耳盗铃的速度判断出自己能否通过做出正确决策来逃生(既然对方是闪灵嘛！当然他每次做出的决策肯定是最好的)，所以李元芳向会OI的你求救~~~请你判断出元芳能否通过做出正确决策来逃生，并且求出在他和闪灵同时做出正确决策的情况下，他们两人可能到达的点的编号。 

 
 # 输入格式 
第一行三个数&nbsp;n,m,f<BR>n表示迷宫的点数&nbsp;m表示迷宫的边数&nbsp;f表示第一次作出决定的人(0-闪灵先&nbsp;1-元芳先)<BR>接下来m行&nbsp;每行两个数x和y&nbsp;表示编号为x的点和和编号为y的点是连通的<BR>数据范围：<BR>1&lt;=n&lt;=1000&nbsp;1&lt;=m&lt;=10000&nbsp;0&lt;=f&lt;=1<BR>1&lt;=x,y&lt;=n<BR><BR> 

 
 # 输出格式 
第一行一个数l&nbsp;(1表示最后元芳能活下来，0表示闪灵能活下来)<BR>第二行按从小到大顺序打出两人可能到达的点的编号，中间用空格隔开 

 
 # 提示 
By&nbsp;lydliyudong 
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
<tr><td>5 5 1
1 2
1 3
2 4
4 5
3 5</td><td>1
1 2 4 5</td></tr></table>
