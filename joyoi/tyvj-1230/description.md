# 

 
 # 题目背景 
tyvj20100613比赛,祝大家取得好成绩。^-^<BR> 

 
 # 题目描述 
从美国州际高速公路建筑者那里，奶牛们引进了一种路径编号系统，来给牧场之间的道路编号。他们已经把N个牧场（1&lt;=N&lt;=250)用1到N的整数编了号。现在他们需要将牧场间的道路也被编上了编号，编号可以从1到2000。（不同道路的编号可以相同）（如：I-9和I-16）。<BR>看下面一个例子：牧场编号为1，2，3，4。道路编号为I-3，I-6，I-9，I-16<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4--&lt;I-6&gt;--2<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;I-16&gt;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;I-9&gt;&nbsp;&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;/<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1--&lt;I-3&gt;--3&nbsp;&nbsp;<BR>Bessie喜欢从牧场1散步到牧场2。在每次散步中，她从不经过同一个牧场两次或两次以上。所以，在上面的地图中，可能的路径只有1-4-2和1-3-2。<BR>在最近的几年中，Bessie已经具有了惊人的数学功底，所以，现在她想练习练习。在每次散步中，她记录下她所经过的道路的编号的最大公约数。例如，在路径1-4-2中，她经过了I-16和I-6，它们的最大公约数是2。她每天尝试一种不同的走法，在走完所有路径之后，她将所有的最大公约数集中起来，计算出它们的最小公倍数。例如，在上面的例子中两个最大公约数分别是2和3，所以最小公倍数是6。<BR>对于很大的地图，Bessie要走完所有的路径是很累的。但是，她仍然想知道那个最小公倍数。请你帮帮她。<BR> 

 
 # 输入格式 
第一行N，以后N行为一个邻接矩阵。第I行第J列表示从I到J的道路的编号。如果I到J没有道路相连，用0表示。<BR> 

 
 # 输出格式 
一个整数表示所有从1到2的路径的最大公约数的最小公倍数。这个数不超过500位。<BR> 

 
 # 提示 
30%的数据，图中不存在环<BR>40%的数据&nbsp;n&lt;=10<BR>70%的数据&nbsp;n&lt;=100<BR>100%&nbsp;n&lt;=250<BR> 
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
0 0 3 16
0 0 9 6
3 9 0 0
16 6 0 0

</td><td>6</td></tr></table>
