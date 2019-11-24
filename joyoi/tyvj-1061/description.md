# 

 
 # 题目描述 
一个公司有三个移动服务员。如果某个地方有一个请求，某个员工必须赶到那个地方去（那个地方没有其他员工），某一时刻只有一个员工能移动。被请求后，他才能移动，不允许在同样的位置出现两个员工。从p到q移动一个员工，需要花费c(p,q)。这个函数没有必要对称，但是c(p,p)=0。公司必须满足所有的请求。目标是最小化公司花费。 

 
 # 输入格式 
第一行有两个整数L,N(3&lt;=L&lt;=200,&nbsp;1&lt;=N&lt;=1000)。L是位置数；N是请求数。每个位置从1到L编号。下L行每行包含L个非负整数。第i+1行的第j个数表示c(i,j)&nbsp;，并且它小于2000。最后一行包含N个数，是请求列表。一开始三个服务员分别在位置1，2，3。 

 
 # 输出格式 
一个数M，表示最小服务花费。 
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
<tr><td>5 9
0 1 1 1 1
1 0 2 3 2
1 1 0 4 1
2 1 5 0 1
4 2 3 4 0
4 2 4 1 5 4 3 2 1</td><td>5
</td></tr></table>
