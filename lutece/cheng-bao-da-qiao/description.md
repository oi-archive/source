
# Content

咸鱼无意间看到了天才钱与学霸周玩的第一个游戏，但是并不会算谁会赢，为了让这只咸鱼不再去找咕咕的麻烦，现在又给咸鱼出了一个新问题，现在有$n$个城堡
$m$个不同的桥，每一个桥连接着两个不同的城堡，此外每一个桥都有重量$v$，当然了由于黑心的商人，一些桥是劣质的，现在咸鱼需要判断能否选择一些非劣质的桥使得所有城堡被连通，如果不行输出 `no`，反之输出 `yes`，令换一行输出所有合法方案中权值之和的最小值。

# Standard Input

第一行输入两个值$n$（$2\le n\le 2000$）,$m$ ($n\le m\le 2\times 10^5$)
接下来$m$行，每一行输入四个值 $a$ $(1\le a\le n)$，$b(1\le b\le n)$，$v(1\le v\le 10^9)$,$p$（$p=0$或$p=1$，分别表示劣质和不劣质）其中$a\neq b$

# Standard Output

如果不行输出 `no`，反之输出 `yes`，令换一行输出所有合法方案中权值之和的最小值。注意区别大小写。

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
1 2 1 0
1 2 2 0</td><td>no</td></tr></table>


# Constraints



# Note

样例不同于test1

# Source


