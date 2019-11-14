
# Content

Given a string S[0,...n-1],and the length of each palindrome substring in S is less than 20.

Define special string of a palindrome string STR[0,...,n-1] is STR[floor(n/2),...,n-1]

Given L,R and a string T, Query the number of palindrome strings, whose the prefix of special string is T, in S[L,...,R]   

ps:floor means the function in C++ language
(No relation between statement and title)

# Standard Input

There are severval cases,please process until EOF.  
The first line contains string S.(1<=|S|<=1e5)  
The second line is a number q means the number of querys.(1<=q<=1e5)  
The next q lines,each line contains two numbers L,R and a string T.(1<=L<=R<=|S|,1<=|T|<=10)  
All strings only contain 'a','b','c','d' and 'e'.

# Standard Output

For each query,you should output the number of palindrome strings which satisfied previous condition in a line.

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
<tr><td>bceaeedde
5
5 8 e
3 5 e
1 2 a
5 9 d
5 9 de</td><td>3
2
0
4
1</td></tr></table>


# Constraints



# Note



# Source


