
# Content

王老板养了两只仓鼠，zhizhi和yueyue。某一天zhizhi觉得很无聊，于是和yueyue玩一个游戏。首先，给两个数$a、b$，他们轮流进行以下操作,zhizhi先手：

1、如果$a>b$，则交换$a、b$。

2、如果$a$等于0，则操作者失败，游戏结束。

3、将$b$替换成$b$%$a$，或者将$b$减掉$a^{k}$,$(k>0且b-a^{k}\geq 0)$。

失败者最终会被胜利者咬死，现在假如zhizhi和yueyue绝对聪明，谁会活下来？

# Standard Input

第一行包含一个整数$T(T\leq 10000)$，表示数据的组数

接下来$T$行，每行包含两个整数$a(0\leq a\leq 1e18)，b(0\leq b\leq 1e18)$。

# Standard Output

输出$T$行，对于每一行，如果zhizhi活下来，输出“zhizhitaidiaola”，否则输出“zhizhitaicanla”。

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
10 21
31 10
0 1
10 30
</td><td>zhizhitaidiaola
zhizhitaicanla
zhizhitaicanla
zhizhitaidiaola
</td></tr></table>


# Constraints



# Note



# Source


