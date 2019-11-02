# 

 
 # 题目描述 
<p>
An array of size n ≤ 1000000 is given to you. There is a sliding window of size k which is moving from the very left of the array to the very right. You can only see the k numbers in the window. Each time the sliding window moves rightwards by one position. Following is an example:<br>The array is [1 3 -1 -3 5 3 6 7], and k is 3.<br>Window position	Minimum value	Maximum value<br>[1  3  -1] -3  5  3  6  7 	-1	3<br> 1 [3  -1  -3] 5  3  6  7 	-3	3<br> 1  3 [-1  -3  5] 3  6  7 	-3	5<br> 1  3  -1 [-3  5  3] 6  7 	-3	5<br> 1  3  -1  -3 [5  3  6] 7 	3	6<br> 1  3  -1  -3  5 [3  6  7]	3	7<br><br>Your task is to determine the maximum and minimum values in the sliding window at each position. </p> 

 
 # 输入格式 
<p>
The input consists of two lines. The first line contains two integers n and k which are the lengths of the array and the sliding window. There are n integers in the second line. </p> 

 
 # 输出格式 
<p>
There are two lines in the output. The first line gives the minimum values in the window at each position, from left to right, respectively. The second line gives the maximum values. </p> 

 
 # 提示 
<p>
原创数据贡献者：<a href="http://10.153.3.180/JudgeOnline/userstatus?user_id=2010HSH">黄少豪</a><br>AC后请到POJ2823提交：<a href="http://poj.org/problem?id=2823">http://poj.org/problem?id=2823</a></p> 
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
<tr><td>8 3
1 3 -1 -3 5 3 6 7</td><td>-1 -3 -3 -3 3 3
3 3 5 5 6 7</td></tr></table>
