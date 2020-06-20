
# Content

这次的 [万恶之源](https://www.bilibili.com/bangumi/play/ep79883)（坐标 15:00）可以用 $n$ 个仅包含小写英文字母的字符串 $S_1, S_2, S_3, \ldots , S_n$ 来表示。

定义一个字符串 $T$ 蕴含在 $S$ 中，当且仅当 $T$ 经过循环移位后能与 $S$ 的某个子串相同。

作为一名计数菌，对于给出的每个字符串 $S_i$，你都想计算出它蕴含在这 $n$ 个字符串里除自身外的多少个字符串中。

# Standard Input

第一行一个正整数 $n$。

接下来有 $n$ 行，其中第 $i$ 行包含一个仅由小写英文字母构成的字符串 $S_i$。

# Standard Output

输出 $n$ 行，第 $i$ 行一个整数 $x_i$，表示第 $i$ 个字符串的答案。

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
<tr><td>3
niconiconi
nico
coi</td><td>0
1
2</td></tr></table>


# Constraints

$1 \leq n \leq 2 \times 10^5$

$|S_i| \geq 1 \ \ (1 \leq i \leq n)$

$\displaystyle \sum_{i=1}^n |S_i| \leq 2 \times 10^5$

# Note



# Source


