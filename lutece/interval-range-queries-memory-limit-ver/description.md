
# Content

For the reason that the problems in the 2017 UESTC Training for Data Structures were solved easily by dalaos, there is another problem for you today!     
You are given a list of n integers s[1], …, s[n].      
There are m queries, each of which contains four integers L, R, a, b. You should answer the number of all different s[x] (L <=x <= R && a <= s[x] <=b).    
    
Maybe you can use fast read and output!!!!!!!

# Standard Input

The first line contains two integers n and m, representing the length of the list s and the number of queries.    
The second line includes n integers s[1], …, s[n].    
Each of the following m lines contains 4 integers L, R, a, b.

# Standard Output

For each query, output one single line, including one number which is your answer.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>10 10
4 4 5 1 4 1 5 1 2 1
5 9 1 2
3 4 7 9
4 4 2 5
2 3 4 7
5 10 4 4
3 9 1 1
1 4 5 9
8 9 3 3
2 2 1 6
8 9 1 4
</td><td>2
0
0
2
1
1
1
0
1
2
</td></tr></table>


# Constraints



# Note

1<=n<=100000,    
1<=m<=1000000,   
1<=si<=n,   
1<=l<=r<=n,   
1<=a<=b<=n   
  
  
样例的部分解释：
   
5 9 1 2   
子序列为4 1 5 1 2   
在[1,2]里的权值有1,1,2，有2种，因此答案为2。   
   
3 4 7 9   
子序列为5 1   
在[7,9]里的权值有5，有1种，因此答案为1。   
   
4 4 2 5   
子序列为1   
没有权值在[2,5]中的，因此答案为0。   
   
2 3 4 7   
子序列为4 5   
权值在[4,7]中的有4,5，因此答案为2。

# Source


