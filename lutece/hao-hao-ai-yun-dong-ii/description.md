
# Content

昊昊喜欢运动

他$N$天内会参加$M$种运动(每种运动用一个$[1, m]$的整数表示)

现在有$Q$个操作，操作描述如下
- 昊昊把第$l$天到第$r$天的运动全部换成了$x$($x \in [1, m]$)
- 问昊昊第$l$天到第$r$天参加了多少种不同的运动

# Standard Input

输入两个数$N$, $M$ ($1\leq N\leq 10^5$, $1\leq M \leq 100$);

输入$N$个数$a_i$($a_i \in [1, m]$)表示在第i天昊昊做了第$a_i$类型的运动;

输入一个数$Q$($1\leq Q \leq 10^5$);

输入$Q$行 每行描述以下两种操作
- 形如`M l r x`，表示昊昊把第$l$天到第$r$天的运动全部换成了$x$($x \in [1, m]$)
- 形如`Q l r`，表示昊昊想知道他第$l$天到第$r$天参加了多少种不同的运动

# Standard Output

对于所有的Q操作，每一行输出一个数 表示昊昊在第$l$天到第$r$天一共做了多少种活动

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
<tr><td>5 3
1 2 3 2 3
4
Q 1 4
Q 2 4
M 5 5 2
Q 1 5
</td><td>3
2
3
</td></tr></table>


# Constraints



# Note



# Source


