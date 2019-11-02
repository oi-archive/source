# 

 
 # 题目描述 
<p>
【问题描述】<br><br>　　日本为了迎接ACM ICPC世界总决赛的到来，计划修建许多道路。日本是一个岛国，其东海岸有N座城市，西海岸有M座城市(M <= 1000, N <= 1000)。K条高速公路将要修建。每个海岸上的城市都被编号为1,2,…从北向南编号。每条高速公路连接东海岸的一座城市和西海岸的一座城市。修建道路的资金由ACM提供保障。有些高速公路会产生交叉。同一个地点最多只会有两条高速公路交汇于此。请你写一个程序，计算高速公路之间的交叉点的数目。</p> 

 
 # 输入格式 
<p>
　　输入文件首先包含数字T，表示测试数据的组数。每组测试数据以三个整数N, M, K 开头，接下来K行每行两个整数，表示高速公路两头的城市编号（第一个数是东海岸的城市编号，第二个数是西海岸的城市编号）。 </p> 

 
 # 输出格式 
<p>
　　对于每组测试数据，按如下格式输出一行：<br>　　Test case (测试数据编号): (交叉点数目)<br></p> 

 
 # 提示 
<p>
 请将你的程序在 http://poj.org/problem?id=3067 上提交测试是否能通过！</p> 
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
<tr><td>1
3 4 4
1 4
2 3
3 2
3 1
</td><td>Test case 1: 5</td></tr></table>
