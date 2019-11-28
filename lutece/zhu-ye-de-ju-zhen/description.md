
# Content

柱爷能干这么多大事，与他喜爱玩弄矩阵是分不开的。

有一天柱爷创造了一个$N$行$M$列的的矩阵A，因为一个个造数据太麻烦，所以柱爷只搞了第一列的数据$A\_{i,1},1 \leq i \leq N$，其他数据由$A\_{i,j}=max(A\_{i,j-1}-B_i,0),1 \leq i \leq N,2 \leq j \leq M$ 生成。

那么问题来了，柱爷想每行每列取**不超过1个**数，请问最大的和是多少。

# Standard Input

输入包括3行

第一行 2个数$N,M$

第二行 N个数$A\_{i,1}$

第三行 N个数$B\_i$

数据保证：

* $1 \leq M \leq N \leq 1000$

* $1 \leq A\_{i,1} \leq 10^6$

* $1 \leq B\_i \leq A\_{i,1}$

# Standard Output

输出一个数，即答案

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
<tr><td>2 1
6 8 
1 5 </td><td>8</td></tr><tr><td>4 3
5 9 10 3 
1 6 7 3 </td><td>16</td></tr></table>


# Constraints



# Note

对于**样例2**

矩阵A为

**	5	4	`3`**

**	9	`3`	0**

**	`10` 	3	0**

**	3  	0	0**

**10+3+3=16**

# Source


