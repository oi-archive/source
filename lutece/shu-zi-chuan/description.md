
# Content

你有一个矩形，上面有一些（1-9）范围内的数字

你需要找一个路径，使路径上数字连成串后，数值最大

# Standard Input

多组数据，不超过 $30$ 组。

每组数据第一行是两个整数 $N,M$ 分别表示矩阵的行数和列数，$N,M \leq 30$，$N\times M \leq 30$。

之后是 $N$ 行，每行 $M$ 个字符，字符只有 1-9 与 # 十种情况，# 号表示此处不可通过。

![说明](/source/lutece/shu-zi-chuan/img/aHR0cHM6Ly9oZXJhbm8uZ2l0aHViLmlvL2ltYWdlcy9MdXRlY2UvMTcwOC5wbmc=.png)

如图所示，`34863568` 为一个可行的字符串，同样 `34358` 也是一种可能的字符串。题目要求一个数值最大的字符串。

输入数据以一行 `0 0` 结尾。

# Standard Output

最大的数值（数字字符串）

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
<tr><td>3 7
##9784#
##123##
##45###
0 0</td><td>791452384</td></tr></table>


# Constraints



# Note

大力出奇迹，数据随机生成

# Source


