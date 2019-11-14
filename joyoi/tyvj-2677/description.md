# 

 
 # 题目描述 
<p>
给出一张N个点M条边的无向简单图，其中N≤100000，M≤100000。定义一个有效的“行程”为一个点数为奇数的简单圈，即所有点在圈上只能出现一次。如果一个点至少处于一个“行程”中，那么它被称为“幸运的”，要求求出图中幸运点的数目。</p> 

 
 # 输入格式 
<p>
The first line of input contains a single integer T – a number of <br>test cases. Every test case starts with a line containing two integers <br>separated by a single space –  N and  M. Each of the next  M lines will <br>contain two integers ai and bi separated by a single space – the labels <br>of cities that i-th road connects. <br> </p> 

 
 # 输出格式 
<p>
Output should contain T lines – answers for each of the test cases. <br> </p> 

 
 # 提示 
<p>
3</p> 
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
<tr><td>1 ≤ T ≤ 77, 
0 ≤ N, M ≤ 100000 (105
), 
1 ≤ ai < bi ≤ N. </td><td>1 
7 7 
1 5 
3 5 
3 7 
1 7 
6 7 
4 7 
4 6 </td></tr></table>
