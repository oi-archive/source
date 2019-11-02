# 

 
 # 题目描述 
<p>
给定一个长度为N的已知序列A[i]( 1 <= i <= N )，要求维护这个序列，能够支持以下两种操作：<br>1、查询A[i],A[i+1],A[i+2],...,A[j]( 1 <= i <= j <= N )中，升序排列后排名第k的数。<br>2、修改A[i]的值为j。<br><br>所谓排名第k，指一些数按照升序排列后，第k位的数。例如序列{6,1,9,6,6}，排名第3的数是6，排名第5的数是9。</p> 

 
 # 输入格式 
<p>
第一行包含一个整数D(0&lt;=D&lt;=4)，表示测试数据的数目。接下来有D组测试数据，每组测试数据中，首先是两个整数N( 1 <= N <= 50000 ),M( 1 <= M <= 10000 )，表示序列的长度为N，有M个操作。接下来的N个不大于1,000,000,000正整数，第i个表示序列A[i]的初始值。然后的M行，每行为一个操作<br>Q i j k 或者<br>C i j<br>分别表示查询A[i],A[i+1],A[i+2],...,A[j](1&lt;=i&lt;=j&lt;=N)中，升序排列后排名第k的数，和修改A[i]的值为j。</p> 

 
 # 输出格式 
<p>
对于每个查询，输出一行整数，为查询的结果。测试数据之间不应有空行。</p> 
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
<tr><td>2
5 3
3 2 1 4 7
Q 1 4 3
C 2 6
Q 2 5 3
5 3
3 2 1 4 7
Q 1 4 3
C 2 6
Q 2 5 3</td><td>3
6
3
6</td></tr></table>
