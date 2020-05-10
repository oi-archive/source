
# Content

![pic](https://media.st.dl.bscstorage.net/steam/apps/481510/ss_bd44bf56857f765ab0498bdbfb2946ff32935c83.600x338.jpg?t=1555401946)

朋友，你走过夜路吗？

某天晚上，michaelshuoliu 结束了在图书馆的学习，踏上幽静的小道，准备回寝室接着学。这条小道长为 $n$ 格，宽为 $2$ 格。一开始，michaelshuoliu 在小道最左上角的格子，他想要走到小道底部。每一步他会从以下三种策略中选择一种：

1. 向下走一格。  
![向下1.png](/source/lutece/ye-lu/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMDUvQnVwWEZyN2x2MmNKOGl3LnBuZw==.png)
![向下2.png](/source/lutece/ye-lu/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMDUvWmxMUFVubW9pamcycXZ0LnBuZw==.png)
2. 向左下走一格（如果他在道路左侧则不能选择这一种）。  
![向左下.png](/source/lutece/ye-lu/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMDUveUxjS0NxenZmd1VJMjVYLnBuZw==.png)
3. 向右下走一格（如果他在道路右侧则不能选择这一种）。  
![向右下.png](/source/lutece/ye-lu/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMDUvMVNBZUNrdEZ5TkpCRW05LnBuZw==.png)

然而，求学的道路并不总是一帆风顺的，小道上的一些格子可能会停放汽车，汽车会占用 $1$ 格。这给他的行动带来了一定的限制（黑色格子表示该位置停放了汽车）：

1. 他不能走到有汽车的格子上。  
![不准1.png](/source/lutece/ye-lu/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMDUvZmxTbWNBM2E4UFlqOUdNLnBuZw==.png)
![不准2.png](/source/lutece/ye-lu/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMDUvWWl4RkFPS3ZWMUcyeWJQLnBuZw==.png)
2. 当他向左下或右下走时，遇到以下情况会被挡住。  
![不准3.png](/source/lutece/ye-lu/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMDUvQ3BIWklzOHd4cXlrY2E1LnBuZw==.png)
![不准4.png](/source/lutece/ye-lu/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMDUvUU9hWHdtZXlTNERCSzZiLnBuZw==.png)

作为他的朋友，OrangeRain 十分担心他的安全。不够聪明的 OrangeRain 想知道 michaelshuoliu 能否到达小道底部，如果能够到达，则可能的路线有多少种。你能帮帮他吗？

我们认为两条路线是不相同的当且仅当两条路线所走过的格子不完全相同。

# Standard Input

第一行包含整数 $n$ ($1 \leq n \leq 50$)，代表小道的长度。

接下来的 $n$ 行，每行包含一个长度为 $2$ 的字符串代表路况，其中 `.` 表示道路通畅， `x` 表示该处有车。michaelshuoliu 的起点为第一行第一列，输入保证这个位置为 `.` 。

# Standard Output

如果 michaelshuoliu 不能走到小道底部，输出 `NO`。否则输出 `YES`，然后另起一行输出一个整数，表示可能的路线种数。

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
..
.x
x.
..</td><td>NO</td></tr><tr><td>1
..</td><td>YES
1</td></tr><tr><td>2
.x
..</td><td>YES
2</td></tr></table>


# Constraints



# Note



# Source


