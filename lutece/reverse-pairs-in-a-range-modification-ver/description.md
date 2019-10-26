
# Content

For the reason that the problems in the 2017 UESTC Training for Data Structures were too easy, there is another problem for you today!    
You are given a list of n integers a[1], ..., a[n].    
There are two kinds of operations, one of which is to change a number in the list to another number.    
The other is to answer the number of reverse pairs in a given range.    
You need to read a operation and immediately do it.   
You are not permitted to read the whole operations and answer all questions in the end.

# Standard Input

The first line contains one integer n.   
The second line includes n integers a1, ..., an.   
The third line is a integer m: the number of operations.   
Each of the following m lines contains 3 integers:    


0 L R (1<=L<=R<=n): You need to answer the number of reverse pairs in a[L], ..., a[R].  

1 p v (1<=p<=n,1<=v<=n): change a[p] to v.  


However, L, R, p, v are not correct, you can get correct L, R, p, v using the following formula:   
L = L xor lastans, R = R xor lastans,   
p = p xor lastans, v = v xor lastans.   
lastans is the your answer of the previous "0 L R".   
In the beginning, lastans = 0.

# Standard Output

For each "0 L R", you should print a single line, including one number which is your answer.

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
<tr><td>10
1 7 5 6 9 4 9 4 4 7
10
0 4 6
0 5 8
0 1 10
1 25 19
0 19 25
1 14 4
0 12 12
0 2 5
1 8 7
1 1 10
</td><td>2
3
16
13
0
2
</td></tr></table>


# Constraints



# Note

1<=n<=50000,  
1<=ai<=n,   
1<=m<=50000,  
1<=(L xor lastans)<=(R xor lastans)<=n,  
1<=(p xor lastans)<=n,  
1<=(v xor lastans)<=n

# Source


