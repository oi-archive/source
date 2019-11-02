# 

 
 # 题目描述 
<p>
给出n个结点以及每个点初始时对应的权值wi。起始时点与点之间没有连边。有3类操作：<br>1、bridge A B：询问结点A与结点B是否连通。如果是则输出“no”。否则输出“yes”，并且在结点A和结点B之间连一条无向边。<br>2、penguins A X：将结点A对应的权值wA修改为X。<br>3、excursion A B：如果结点A和结点B不连通，则输出“impossible”。否则输出结点A到结点B的路径上的点对应的权值的和。<br>给出q个操作，要求在线处理所有操作。<br>数据范围：1<=n<=30000, 1<=q<=300000, 0<=wi<=1000。<br></p> 

 
 # 输入格式 
<p>
第一行包含一个整数n(1<=n<=30000)，表示节点的数目。<br>第二行包含n个整数，第i个整数表示第i个节点初始时对应的权值。<br>第三行包含一个整数q(1<=n<=300000)，表示操作的数目。<br>以下q行，每行包含一个操作，操作的类别见题目描述。<br>任意时刻每个节点对应的权值都是1到1000的整数。<br></p> 

 
 # 输出格式 
<p>
输出所有bridge操作和excursion操作对应的输出，每个一行。</p> 
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
4 2 4 5 6
10
excursion 1 1
excursion 1 2
bridge 1 2
excursion 1 2
bridge 3 4
bridge 3 5
excursion 4 5
bridge 1 3
excursion 2 4
excursion 2 5</td><td>
4
impossible
yes
6
yes
yes
15
yes
15
16</td></tr></table>
