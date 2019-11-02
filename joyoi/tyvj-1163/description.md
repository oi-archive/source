# 

 
 # 题目背景 
在这个盛大的party上，由于太多朋友的缘故，candy给每一个人划分了一个地区，飘飘乎居士的地区是1，candy的地区是n。 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;聚会上一共有n个地区，编号从1到n，（1&lt;=n&lt;=1000）。经过飘飘乎居士的计算共有p（0&lt;p&lt;=10000）对地区之间有一条相互连通的道路。飘飘乎居士将从1出发，目的地是n(也就是candy所在的地方)。他可以在2个相邻地区里行走，所耗费的体力为li。当然，飘飘乎居士为了能够尽快到达candy所在的地方，途中将会使用k(0&lt;=k&lt;=25)次飘飘神功，使用飘飘神功以后可以做到在2个相邻的地区行走不耗费任何的体力。&nbsp;我们把整条线路中某2地耗费的最大体力值称为全程的代价。问题也就是求解最小代价是多少？ 

 
 # 输入格式 
第一行，三个整数n&nbsp;p&nbsp;k<BR>接下来p行，每行3个整数ai&nbsp;bi&nbsp;li（数据保证ai与bi之间只有一条道路相连），表示编号为ai与bi的地区之间有一条道路（道路是双向的），并且如果飘飘乎居士选择通过这条道路，那么他将消耗li的体力值。<BR> 

 
 # 输出格式 
一行，表示飘飘乎居士消耗的最小体力值是多少？如果不能到达，则输出-1 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;一共5个地区，飘飘乎居士将从1出发，目的地是n。飘飘乎居士选择的路线如下1&nbsp;—&gt;3&nbsp;,3&nbsp;—&gt;&nbsp;2&nbsp;,2&nbsp;—&gt;&nbsp;5，经过这3个路线，耗费的体力分别为4&nbsp;3&nbsp;9，但是耗费体力最多的那个9，飘飘乎居士会使用飘飘神节省体力，因此，整个线路中耗费体力最多的道路变成了4，这样，代价变成了4。也就是最后的答案了。<BR>来源&nbsp;飘飘乎居士——Violet&nbsp;Hill&nbsp; 
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
<tr><td>5 7 1
1 2 5
3 1 4
2 4 8
3 2 3
5 2 9
3 4 7
4 5 6
</td><td>4</td></tr></table>
