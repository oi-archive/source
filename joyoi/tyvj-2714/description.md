# 

 
 # 题目描述 
<p>
   给出一个单环图（每个点的出度为1），求出最少添加多少条边使得所有点满足从1到它的距离小于等于K。</p> 

 
 # 输入格式 
<p>
The first line of input contains two integers N and K (2 ≤ N ≤ 500 000, 1 ≤ K ≤ 20 000) – the number of pages <br>and the target maximum number of links to be followed. <br>Each of the following N lines contains two different integers A and B (1 ≤ A, B ≤ N) meaning that the link on <br>page A points to page B. <br> </p> 

 
 # 输出格式 
<p>
The first and only line of output should contain a single integer, the minimum number of additional links <br>required to make the website K-reachable. </p> 

 
 # 提示 
<p>
one possible solution is to add the links 1→7, 1→14 and 14→10</p> 
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
<tr><td>14 4 
1 2 
2 3 
3 4 
4 5 
7 5 
5 6 
6 3 
8 10 
10 9 
9 8 
14 13 
13 12 
12 11 
11 14 </td><td>3</td></tr></table>
