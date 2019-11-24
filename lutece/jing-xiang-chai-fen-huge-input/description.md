
# Content

lxhgww非常喜欢数字游戏，他发现，很多数都可以表示成两个相互反转的数之和，他把这个现象称为数的“镜像拆分”。比如$66$共有五种镜像拆分方法：
```
66 = 15 + 51
66 = 24 + 42
66 = 33 + 33
66 = 42 + 24
66 = 51 + 15
```

注意，前导$0$是不允许的，所以$66 = 60 + 06$不算做合法的镜像拆分。

现在lxhgww想知道，在$K$进制下，对于在$[A, B]$区间内的数，其镜像拆分的方案数之和是多少？

# Standard Input

输入的第一行是一个数$K$($2\leq K\leq 100000$)。

输入的第二行是一个数$n$($1\leq n\leq 100000$)，表示数字$A$的长度。

接下来$n$行，表示$A$从低位开始的每一位数字。

然后是一个数$m$($1\leq m\leq 100000$)，表示数字$B$的长度。

接下来$m$行，表示$B$从低位开始的每一位数字。

数据保证，$0 < A\leq B$，$A$, $B$的每一位数字都在 $[ 0, K-1 ]$的范围内，没有前导$0$。

# Standard Output

输出一行，包含一个整数，表示镜像拆分的方案数之和。由于这个答案非常大，只需要输出这个答案除以$20110521$的余数。

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
2
6
6
2
6
6</td><td>5</td></tr><tr><td>10
1
1
4
0
0
0
1</td><td>410</td></tr></table>


# Constraints



# Note



# Source


