
# Content

时间是最难以捉摸的东西，光是测量它们就已经很难了。一般而言，测量时间用一个可重复等时长发生的事件来定义最小的时间可测单位。于是Krolia想到了一个测量时间的好方法。
Krolia有一盒火柴，如果把火柴的头去掉火柴就会变成一样长的木棍。Krolia知道一根（没有火柴头）木棍一端点燃后，整个燃烧会持续$x$时间。Krolia还可以从两端同时点燃木棍，这样燃烧会持续$\frac{x}{2}$时间。现在Krolia想用这堆火柴来计时，问什么样的时间可以被完全精确地计算出。

# Standard Input

第一行一个整数$T$($T\leq 1000$)，表示有$T$组测试数据，每组测试数据行三个整数$a,b,x$($1\leq a,b,x\leq 10^9$)表示要测量$\frac{a}{b}$，一根火柴的燃烧时长是$x$时间。

# Standard Output

一个字符串，`YES`或者`NO`表示能或者不能被精确计算。

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
1 1 1
1 2 1
1 4 1
1 5 1</td><td>YES
YES
YES
NO</td></tr></table>


# Constraints



# Note

1. 从一端点燃一根木棍。
2. 从两端同时点燃一根木棍。
3. 从两端同时点燃一根木棍的同时，从一端点燃一根木棍。当第一根木棍燃烧殆尽的时候，把剩下的那根木棍的火熄灭。最后把剩下的木棍的两端同时点燃。

# Source


