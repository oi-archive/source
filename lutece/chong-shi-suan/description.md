
# Content

虫食算，是指在一条算式里，有大量的“洞”，要求玩家填上数字的一种趣题。这些洞像虫咬掉的，故名。

现在考虑一种简单的情况$A+B=C$，其中$A$、$B$、$C$都是没有前导零的自然数，被虫啃掉的数字用`?`代替，你能恢复出整个算式吗？

# Standard Input

输入第一行为整数$T$($T\leq 100$)，表示测试数据组数。

以下$T$行每行一个字符串$S$，$S$的长度小于等于$50$，表示待恢复的算式。

算式保证符合$A+B=C$的形式，且$A$、$B$、$C$仅由数字和`?`组成。

# Standard Output

如果有多解，输出其中$C$最大的解

如果还有多解，输出其中$A$最大的解

如果无解，输出`Impossible`

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
<tr><td>2
?+?=?
9+?=?1</td><td>9+0=9
9+2=11</td></tr></table>


# Constraints



# Note



# Source


