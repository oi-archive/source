
# Content

假如在一场比赛中，有$n$个人进入Hack环节，$n$个人编号从0到$n-1$，现在你得到Hack的部分信息，其中包括哪些人尝试过challenge，以及哪些人被成功challenge，如果某个人被成功challenge后，他就会变得很伤心，而不再尝试challenge。假设任意两次challenge都不是同时的，那么从时间顺序上看，Hack环节可以看成一个序列，那么有多少种不同的序列（也就是不同的Hack情景）满足给定的Hack信息？

在Hack环节中，每个人最多尝试一次challenge，且不能challenge自己，每个人可以被多次challenge，challenge结果只有成功和失败，某个人被成功challenge后，该人可以继续被challenge，且只会为失败。

# Standard Input

第一行包含一个整数$n(1<=n<=5000)$，表示Hack环节人数

第二行包含$n$个数，$a0$到$a_{n-1}$，如果$a_i$=0，表示第i个人未尝试过challenge，如果$a_i$=1，表示第$i$个人尝试过challenge

第三行包含$n$个数，$b0$到$b_{n-1}$，如果$b_i$=0，表示第i个人未被成功challenge，如果$b_i$=1，表示第$i$个人被成功challenge

# Standard Output

输入总情况数 mod $1000000007$

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
<tr><td>4
0 0 1 1
1 1 0 0
</td><td>4
</td></tr></table>


# Constraints



# Note

样例为4种情况

1、第2个人成功challenge第0个人，第3个人成功challenge第1个人

2、第2个人成功challenge第1个人，第3个人成功challenge第0个人

3、第3个人成功challenge第0个人，第2个人成功challenge第1个人

4、第3个人成功challenge第1个人，第2个人成功challenge第0个人

# Source


