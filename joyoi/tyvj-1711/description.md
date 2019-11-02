# 

 
 # 题目描述 
对于一个数字序列A，并且有若干询问。对于每个询问，要求求出一段在序列A中非空的连续段使得这一段数字的总和的绝对值尽量接近P。 

 
 # 输入格式 
第一行2个数N、T，表示序列的长度和询问的个数。<BR>接下来一行N个整数，表示A序列。<BR>接下来T行，每行一个数P表示询问。 

 
 # 输出格式 
共输出T行，每行对应一个询问的答案。输出3个数：第一个数为能够实现的最接近P的数，后面两个数L、R表示A序列中的L到R这一段数能实现这个答案。如果存在多解，输出L最小的解；如果还有多解，输出R最小的解。 

 
 # 提示 
30%的数据&nbsp;1&lt;=N&lt;=1,000。<BR>60%的数据&nbsp;1&lt;=N&lt;=10,000。<BR>100%的数据&nbsp;1&lt;=N&lt;=100,000，A&nbsp;序列中数字绝对值&lt;=10,000，T&lt;=100，询问的数字&lt;=10^9。 
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
<tr><td>Sample Input 1:
5 1
-10 -5 0 5 10
3

Sample Input 2:
6 2
-2 5 3 0 -3 -4
1
6

Sample Input 3:
7 2
-2 -1 -2 4 1 -3 7
0
6</td><td>Sample Output 1:
5 2 2

Sample Output 2:
1 1 6
6 1 3

Sample Output 3:
0 1 5
6 2 7</td></tr></table>
