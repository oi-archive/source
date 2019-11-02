# 

 
 # 题目描述 
<p>
给你一棵树，现在要建立一些消防站，有以下要求:<br>1. 消防站要建立在节点上，每个节点可能建立不只一个消防站。<br>2. 每个节点应该被一个消防站管理，这个消防站不一定建立在该节点上。<br>3. 每个消防站可以管理至多s个节点。<br>4. 消防站只能管理距离（两点间最短路径的边数）不超过k的结点。<br>请问至少要设立多少个消防站。<br><br></p> 

 
 # 输入格式 
<p>
第一行n,s,k。<br>接下来n-1行每行xi,yi描述一条边连接xi与yi。<br><br>1<=n<=100000<br>1<=s<=n<br>1<=k<=20<br>1<=xi<yi<=n</p> 

 
 # 输出格式 
<p>
一个数，最少的消防站个数。<br><br></p> 

 
 # 提示 
<p>
感谢MT大牛贡献译文.</p> 
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
<tr><td>12 3 1
1 12
3 8
7 8
8 9
2 12
10 12
9 12
4 8
5 8
8 11
6 8
</td><td>4
<img border="0" src="/source/joyoi/tyvj-2416/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjQxNi9wcm9ibGVtc19pbWFnZXMvMjQxNi8xMTE3LmpwZw==.jpg"></td></tr></table>
