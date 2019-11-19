
# Content

Minakami Yuki 很喜欢字符串，作为一个犯中二病的熊孩子，她只喜欢某些特定的小写字母，如果一个字符串包含了多于$K$个她不喜欢的字母，她就认为这是一个“坏串”。有一天她看到了一个只由小写字母组成的字符串，她想知道这个字符串的哪些子串不是“坏串”。因为她还要努力研究奇怪的哲学知识，这个问题就由你来计算了。

注意注意如果一个相同的子串出现在了原串的多个位置，只能算作一次喵~

# Standard Input

本题有多组测试数据，Input的第一行是一个整数$T$($T\leq 100$)，是测试数据的组数。

接下来$T$组数据，每组由三行构成。

第一行是一个字符串$S$，长度不超过$1500$，是Yuki看到的字符串。

第一行是一个长度为$26$的`01`串，代表Yuki喜不喜欢每个字母，从`a`到`z`。`0`代表不喜欢，`1`代表喜欢。

第三行是一个整数$K$，$0\leq K\leq$（$S$的长度），表示子串中最多所能包含的不喜欢的字母个数

# Standard Output

输出$T$行，每行一个整数，即满足条件子串的个数

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
ababab
01000000000000000000000000
1
acbacbacaa
00000000000000000000000000
2</td><td>5
8</td></tr></table>


# Constraints



# Note

子串是字符串中连续的一段，也可以包含原串本身。

# Source


