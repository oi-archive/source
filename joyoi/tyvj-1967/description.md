# 

 
 # 题目背景 
（喵星人rainbow和freda同心协力击退了汪星人的入侵，不幸的是，汪星人撤退之前给它们制造了一片幻象迷宫。）<BR>freda：呜呜，肿么办啊……<BR>rainbow：momo...我们一定能走出去的！<BR>freda：嗯，+U+U！ 

 
 # 题目描述 
幻象迷宫可以认为是无限大的，不过它由若干个N*M的矩阵重复组成。矩阵中有的地方是道路，用'.'表示；有的地方是墙，用'#'表示。rainbow和freda所在的位置用'S'表示。也就是对于迷宫中的一个点(x,y)，如果(x&nbsp;mod&nbsp;n,y&nbsp;mod&nbsp;m)是'.'或者'S'，那么这个地方是道路；如果(x&nbsp;mod&nbsp;n,y&nbsp;mod&nbsp;m)是'#'，那么这个地方是墙。rainbow和freda可以向上下左右四个方向移动，当然不能移动到墙上。<BR>请你告诉rainbow和freda，它们能否走出幻象迷宫（如果它们能走到距离起点无限远处，就认为能走出去）。如果不能的话，rainbow就只好启动城堡的毁灭程序了……当然不到万不得已，他不想这么做。。。 

 
 # 输入格式 
输入包含多组数据，以EOF结尾。<BR>每组数据的第一行是两个整数N、M。<BR>接下来是一个N*M的字符矩阵，表示迷宫里(0,0)到(n-1,m-1)这个矩阵单元。 

 
 # 输出格式 
对于每组数据，输出一个字符串，Yes或者No。 

 
 # 提示 
对于30%的数据，N,M&lt;=20<BR>对于50%的数据，N.M&lt;=100.<BR>对于100%的数据，N,M&lt;=1500，每个测试点不超过10组数据. 
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
<tr><td>5 4
##.#
##S#
#..#
#.##
#..#
5 4
##.#
##S#
#..#
..#.
#.##</td><td>Yes
No</td></tr></table>
