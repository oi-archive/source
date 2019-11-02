# 

 
 # 题目背景 
<p>谁能忘记过去一路走来陪你受的伤。</p> 

 
 # 题目描述 
<p>简单来说，你走过的路和会走的路构成了一个n个顶点n&nbsp;-&nbsp;1条边的无向连通图。<br />
每经过一个点i都会对你产生vi的伤害。<br />
有时候某个点的伤害值会改变。<br />
你想知道经过最短路径从u走到v的过程中（包括u和v）受到的第k大的伤害是多大。</p>

<p>&nbsp;</p> 

 
 # 输入格式 
<p>第一行两个正整数n和q，表示树的节点数和操作数。<br />
第二行n个数vi，表示第i个节点的初始伤害值。<br />
接下来n-1行每行两个数x,&nbsp;y，表示有一条连接x和y的无向边。<br />
接下来q行每行三个非负整数k,&nbsp;x,&nbsp;y，表示一个操作。<br />
如果k=0，那么表示x号点的伤害值变为y。<br />
否则表示询问从x到y的路径上的第k大伤害值。</p> 

 
 # 输出格式 
<p>对于每个k不为0的操作输出一行表示答案。<br />
如果路径上的点数不足k个那么输出一行&quot;naive&quot;（不含引号）。</p> 

 
 # 提示 
<p>对于10%的数据，n,&nbsp;q&nbsp;&lt;=&nbsp;1000。<br />
对于40%的数据，k&nbsp;&lt;=&nbsp;5。<br />
对于100%的数据，n,&nbsp;q&nbsp;&lt;=&nbsp;50,000,&nbsp;vi&nbsp;&lt;=&nbsp;100,000,000,&nbsp;0&nbsp;&lt;=&nbsp;k&nbsp;&lt;=&nbsp;n。</p>

<p>&nbsp;</p> 
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
<tr><td>5 5
5 1 2 3 4
3 1
2 1
4 3
5 3
2 4 5
0 1 2
2 2 3
2 1 4
3 3 5
</td><td>3
2
2
naive
</td></tr></table>
