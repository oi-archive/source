
# Content

这次的 [鬼畜视频](https://www.bilibili.com/video/BV11x411K7zK) 可以用一个仅包含小写英文字母的字符串 $S$ 来表示。

定义一个字符串 $T$ 的鬼畜度为 $T$ 在 $S$ 中的出现次数除以 $T$ 的长度。

作为一名计数菌，你将进行 $n$ 次计数。每次计数你都会选择两个正整数 $L, R$，并计算 $S$ 的所有子串中字典序在 $[L, R]$ 之间的子串的鬼畜度之和。

# Standard Input

第一行包含一个仅由小写英文字母构成的字符串 $S$。

第二行包含一个正整数 $n$，表示计数的次数。

接下来有 $n$ 行，其中第 $i$ 行包含两个正整数 $L_i, R_i$。

# Standard Output

输出 $n$ 行，第 $i$ 行一个整数 $x_i$，表示第 $i$ 次计数的答案。

设你计算的鬼畜度之和可以用既约分数 $\displaystyle \frac{p}{q}$ 表示，你需要输出它模 $10^9 + 7$ 的结果，即输出 $p \cdot q^{-1} \bmod (10^9 + 7)$，其中 $q^{-1}$ 表示 $q$ 在模 $10^9 + 7$ 意义下的逆元。

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
<tr><td>niconiconi
2
2 3
10 45</td><td>3
92460351</td></tr></table>


# Constraints

$1 \leq |S| \leq 2 \times 10^5$

$1 \leq n \leq 2 \times 10^5$

$\displaystyle 1 \leq L_i \leq R_i \leq \frac{n (n+1)}{2} \ \ (1 \leq i \leq n)$

# Note



# Source


