
# Content

有一天，`天才钱`和`学霸周`闲的无聊玩起了游戏，游戏内容是这样的，现在有$n$个城堡
$m$个不同的桥，每一个桥连接着两个不同的城堡，并且已知这$m$个桥可以使$n$个城堡连通，此外每一个桥都有重量$v$。两位大爷需要给出选择桥的方案使得所有城堡被连通，注意两位大爷的方案不能完全相同（至少存在一个桥不相同），已知`周大爷`优先给出方案（因此`钱大爷`的方案必须不同于`周大爷`）。规则很诡异，如果`钱大爷`的方案中桥的重量之和$\le$`周大爷`的方案中桥的重量之和，那么`钱大爷`获胜，反之`周大爷`获胜。两位大爷都很聪明，他们会给出最优方案。现在你需要计算谁会赢。

# Standard Input

第一行输入两个值$n$（$2\le n\le 2000$）,$m$ ($n \le m \le 200000$)
接下来$m$行，每一行输入三个值$ a$ ($1\le a\le n$)，$b$($1\le b\le n$)，$v$($1\le v\le 10^{18}$),其中$a\neq b$

# Standard Output

如果`钱大爷`获胜输出“`zin`”，反之输出“`ogisosetsuna`” 。

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
<tr><td>2 2
1 2 1
1 2 1</td><td>zin</td></tr></table>


# Constraints



# Note

样例和test1不同

# Source


