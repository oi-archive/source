# 

 
 # 题目描述 
给定一个N*N的矩阵，要求支持3种操作：<br>R&nbsp;a&nbsp;b：交换第a行和第b行的所有元素；<br>C&nbsp;a&nbsp;b：交换第a列和第b列的所有元素；<br>A&nbsp;a&nbsp;b：询问第a行第b列元素的值。<br> 

 
 # 输入格式 
第一行两个整数N，K,表示矩阵大小和操作个数<br>接下来N行，每行N个整数，表示初始的矩阵。<br>接下来K行每行一个操作，格式如题目所述。<br> 

 
 # 输出格式 
对于每个询问，输出一行作为答案。<br> 

 
 # 提示 
对于30%数据，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;100，1&nbsp;&lt;=&nbsp;K&nbsp;&lt;=&nbsp;20000<br>对于另外30%数据，没有C操作<br>对于100%数据，1&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;700，1&nbsp;&lt;=&nbsp;K&nbsp;&lt;=&nbsp;100000，0&nbsp;&lt;=&nbsp;初始矩阵中的所有数值&lt;=10^9<br>kAc(wwwaaannngggrs)&nbsp;Tyvj三周年邀请赛&nbsp;第二题<br> 
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
<tr><td>3 5
1 2 3
4 5 6
7 8 9
A 3 2
R 3 2
C 2 3
A 2 2
A 3 2
</td><td>8
9
6
</td></tr></table>
