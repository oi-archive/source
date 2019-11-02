# 

 
 # 题目描述 
<p>
FJ is surveying his herd to find the most average cow.  He wants<br>to know how much milk this 'median' cow gives: half of the cows<br>give as much or more than the median; half give as much or less.<br><br>Given an odd number of cows N (1 <= N < 10,000) and their milk output<br>(1..1,000,000), find the median amount of milk given such that at least<br>half the cows give the same amount of milk or more and at least half give<br>the same or less.<br><br>输入N个数,输出升序排列后中间那个数.<br></p> 

 
 # 输入格式 
<p>
* Line 1: A single integer N<br><br>* Lines 2..N+1: Each line contains a single integer that is the milk<br>        output of one cow.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: A single integer that is the median milk output.<br><br></p> 
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
<tr><td>5
2
4
1
3
5

INPUT DETAILS:

Five cows with milk outputs of 1..5

</td><td>3

OUTPUT DETAILS:

1 and 2 are below 3; 4 and 5 are above 3.</td></tr></table>
