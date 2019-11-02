# 

 
 # 题目描述 
Will很喜欢吃桃子（Will表示如果桃子不用剥皮就更好吃了，笑～）。某天Will来到了一片森林，森林中有n颗桃树，依次编号为1,&nbsp;2,&nbsp;…,&nbsp;n.&nbsp;每棵树上有数量不等的桃子。某些桃树之间有单向通行的小路，通过每条小路的时间也不一定相同。现在，Will提着一个最多可以容纳k个桃子的篮子，从编号为1的桃树出发，走过若干条小路之后来到编号为n的桃树。当Will在路上走的时候，每走1分钟，他会从篮子中拿出一个桃子来吃掉（如果篮子中还有桃子的话）。每到一棵桃树（包括起点和终点），他会把这棵桃树上的所有桃子摘下来放入篮子中。现在你的问题是：求k的最小值，使得Will能够不浪费任何桃子（i.e.&nbsp;每到一棵桃树，这棵树上的所有桃子都能够被装入篮子中）。<BR> 

 
 # 输入格式 
输入文件第一行两个整数，n,&nbsp;m，分别表示桃树的数量以及连接桃树的小路的数量。<BR>接下来一行n个用空格隔开的整数，分别表示每一颗桃树上的果实的数量。<BR>接下来m行，每行3个用空格隔开的整数，a,&nbsp;b,&nbsp;c，表示有一条小路能够从桃树a走到桃树b，（注意小路一定是单向的），走过这条小路所需要的时间是c分钟。<BR>从任意一棵桃树出发，Will不可能沿着小路走若干条之后重新回到这棵桃树。（i.e.&nbsp;给出的图是一个有向无环图。）<BR>数据保证Will一定能够从桃树1走到桃树n。<BR><BR> 

 
 # 输出格式 
输出文件有且仅有一行，一个整数，表示k的最小值<BR> 

 
 # 提示 
对于30%的数据，满足n&nbsp;&lt;=&nbsp;10,&nbsp;m&nbsp;&lt;=&nbsp;20<BR>对于60%的数据，满足n&nbsp;&lt;=&nbsp;1000,&nbsp;m&nbsp;&lt;=&nbsp;10000<BR>对于100%的数据，满足3&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;10000,&nbsp;3&nbsp;&lt;=&nbsp;m&nbsp;&lt;=&nbsp;30000,&nbsp;所有其他数据都不超过10000。<BR><BR> 
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
<tr><td>3 3
5 1 6
1 3 1
1 2 4
2 3 5

</td><td>6
</td></tr></table>
