# 

 
 # 题目描述 
众所周知，GF同学喜欢打dota，而且打得非常好。今天GF和Spartan同学进行了一场大战。现在GF拿到一张地图，地图上一共有n个地点，GF的英雄处于1号点，Spartan的基地位于n号点，GF要尽快地选择较短的路线让他的英雄去虐掉Spartan的基地。但是Spartan早就料到了这一点，他有可能会开挂(BS~)使用一种特别的魔法，一旦GF所走的路线的总长度等于最短路的总长度时，GF的英雄就要和这种魔法纠缠不休。这时GF就不得不选择非最短的路线。现在请你替GF进行规划。<BR><BR>对于描述的解释与提醒：<BR>1.无向路径，花费时间当然为非负值。<BR>2.对于本题中非最短路线的定义：不管采取任何迂回、改道方式，只要GF所走的路线总长度不等于1到n最短路的总长度时，就算做一条非最短的路线。<BR>3.保证1~n有路可走。<BR> 

 
 # 输入格式 
第一行为n，m(表示一共有m条路径)<BR>接下来m行，每行3个整数a，b，c，表示编号为a,b的点之间连着一条花费时间为c的无向路径。<BR>接下来一行有一个整数p，p=0表示Spartan没有开挂使用这种魔法，p=1则表示使用了。<BR> 

 
 # 输出格式 
所花费的最短时间t，数据保证一定可以到达n。 

 
 # 提示 
对于50%的数据，1&lt;=n,m&lt;=5000<BR>对于70%的数据，1&lt;=n&lt;=10000,&nbsp;1&lt;=m&lt;=50000,p=0,<BR>对于100%的数据，1&lt;=n&lt;=10000,&nbsp;1&lt;=m&lt;=50000,p=1<BR>无向图，花费时间c&gt;=0<BR>&nbsp;<BR>来源：lydliyudong&nbsp;&nbsp;&nbsp;&nbsp;Tyvj&nbsp;February二月月赛第二场&nbsp;&nbsp;第2道 
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
<tr><td>样例输入1：
5 5
1 2 1
1 3 2
3 5 2
2 4 3
4 5 1
0

样例输入2：
5 5
1 2 1
1 3 2
3 5 2
2 4 3
4 5 1
1
</td><td>样例输出1：
4
样例输出2：
5
</td></tr></table>
