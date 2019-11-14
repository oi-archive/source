
# Content

小埋有一个steam愿望单，上面记载着她想买的游戏！现在小埋有以下 $n$ 个操作：

$1\ x\ y$     添加一个价格为 $y$ 名字为 $x$ 的游戏加入愿望单

$2\ x$       删除名字为 $x$ 的游戏

$3\ x\ y$     名字为 $x$ 的游戏价格调整为 $y$

$4\ x$  $x$ 为 $1$ 输出最便宜的游戏的名字(如果有多个同价格游戏输出字典序最小的)，$x$ 为 $2$ 输出最贵的游戏(如果有多个同价格游戏输出字典序最大的)

**不合法的情况请忽略该操作**

**不合法的情况请忽略该操作**

**不合法的情况请忽略该操作**

# Standard Input

第一行一个$n(1\le n \le 1e5)$
接下来 $n$ 行 每行一个 $p$ 表示操作类型 接下来根据操作类型跟一个或两个数字（ $x$ 只包括大小写字母和下划线并不超过25个字符，$1\le y\le 1e9$）

# Standard Output

对于每个查询，输出一行对应游戏的名字

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
<tr><td>8
1 slay_the_spire 60
1 dark_soul_III 118
1 The_Binding_of_Isaac 58
1 Age_of_Empires_II 88
4 1
3 dark_soul_III 57
4 1
4 2</td><td>The_Binding_of_Isaac
dark_soul_III
Age_of_Empires_II</td></tr><tr><td>7
4 1
1 I 100
1 II 150
1 I 200
4 1
2 III
3 IV 600
</td><td>I</td></tr></table>


# Constraints



# Note



# Source


