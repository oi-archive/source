# 

 
 # 题目描述 
<p>
Farmer John knows that an intellectually satisfied cow is a happy

 
 # 输入格式 
<p>
* Line 1: Two space-separated integers: M and N

 
 # 输出格式 
<p>
* Lines 1..M: Each line contains N space-separated integers, each
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
<tr><td>4 4
1 0 0 1
0 1 1 0
0 1 1 0
1 0 0 1


</td><td>
0 0 0 0
1 0 0 1
1 0 0 1
0 0 0 0

OUTPUT DETAILS:

After flipping at row 2 column 1, the board will look like:
0 0 0 1
1 0 1 0
1 1 1 0
1 0 0 1

After flipping at row 2 column 4, the board will look like:
0 0 0 0
1 0 0 1
1 1 1 1
1 0 0 1

After flipping at row 3 column 1, the board will look like:
0 0 0 0
0 0 0 1
0 0 1 1
0 0 0 1

After flipping at row 3 column 4, the board will look like:
0 0 0 0
0 0 0 0
0 0 0 0
0 0 0 0

Another solution might be:
0 1 1 0
0 0 0 0
0 0 0 0
0 1 1 0
but this solution is lexicographically higher than the solution above.