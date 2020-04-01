# 

 
 # 题目描述 
<p>Freda是一个迷宫爱好者，她利用业余时间建造了许多迷宫。每个迷宫都是由若干房间和走廊构成的，每条走廊都连接着两个不同的房间，两个房间之间最多只有一条走廊直接相连，走廊都是双向通过。<br />
黄昏时候，Freda喜欢在迷宫当中漫步。每天，Resodo都会为Freda设计一个挑战方案。Resodo会指定起点和终点，请Freda来找到一条从起点到终点的简单路径。一条简单路径定义为一个房间序列，每个房间至多在序列里出现一次，且序列中相邻的两个房间有走廊相连。当起点和终点之间存在且仅存在一条简单路径的时候，Freda认为这个挑战方案是RD的。现在，请你帮帮Resodo来写一个程序，判断一个挑战方案是否是RD的。</p> 

 
 # 输入格式 
<p>第一行三个整数N,M,Q.分别表示房间数，走廊数，询问数。<br />
接下来M行每行2个整数x,y,&nbsp;0&lt;x,y&lt;=N,&nbsp;表示x和y之间有一条走廊相连。<br />
接下来Q行每行2个整数x,y,&nbsp;表示询问以x为起点,y为终点的挑战方案是否是RD的.</p> 

 
 # 输出格式 
<p>对于每个询问，输出一行&rdquo;Y&rdquo;或者&rdquo;N&rdquo;（不含引号）.Y表示该询问所表示的挑战方案是RD的,N表示该询问所表示的挑战方案不是RD的.</p> 

 
 # 提示 
<p>样例解释<br />
1,3之间只有一条路径&nbsp;1-&gt;2-&gt;3<br />
1,5之间有两条路径&nbsp;1-&gt;2-&gt;5&nbsp;;&nbsp;1-&gt;2-&gt;4-&gt;5<br />
2,6之间没有路径<br />
数据范围与约定<br />
对于30%的数据，N&lt;=100，&nbsp;M&lt;=1000,&nbsp;Q&lt;=100.<br />
对于50%的数据，N&lt;=1000,&nbsp;M&lt;=10000,&nbsp;Q&lt;=1000.<br />
对于100%的数据，N&lt;=10000,&nbsp;M&lt;=100000,&nbsp;Q&lt;=10000.Description&nbsp;From&nbsp;/&nbsp;Translated&nbsp;by&nbsp;-&nbsp;This_poet<br />
Contact&nbsp;me&nbsp;-&nbsp;This_poet@126.com/Freda.RD.Shi@gmail.com<br />
This_poet&#39;s&nbsp;Blog&nbsp;-&nbsp;http://thispoet.blogcn.com</p> 
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
<tr><td>6 5 3
1 2
2 3
2 4
2 5
4 5
1 3
1 5
2 6
</td><td>Y
N
N
</td></tr></table>
