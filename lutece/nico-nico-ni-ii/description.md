
# Content

这次的 [鬼畜视频](https://www.bilibili.com/video/BV1ps411Q7FX) 可以用一个仅包含小写英文字母的字符串 $S$ 来表示。

定义一个字符串 $T$ 在 $S$ 中的容错为 $2$ 匹配数为与 $T$ 长度相等且至多有 $2$ 个对应位置的字符不同的 $S$ 的子串个数。

作为一名计数菌，你选择了一个字符串 $T$，并想计算它在 $S$ 中的容错为 $2$ 匹配数。

# Standard Input

第一行一个正整数 $t$，表示有 $t$ 组测试数据。

每组测试数据两行，对于第 $i$ 组测试数据：

第一行包含一个仅由小写英文字母构成的字符串 $S_i$；

第二行包含一个仅由小写英文字母构成的字符串 $T_i$。

# Standard Output

输出 $t$ 行，第 $i$ 行一个整数 $x_i$，表示第 $i$ 组测试数据的答案。

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
<tr><td>1
niconikoriko
nico</td><td>3</td></tr></table>


# Constraints

$1 \leq t \leq 10^6$

$|S_i|, |T_i| \geq 1 \ \ (1 \leq i \leq t)$

$\displaystyle \sum_{i=1}^t (|S_i| + |T_i|) \leq 2 \times 10^6$

# Note

关于 Nico~Nico~Ni~ (Ⅰ)，它在 [这里](https://acm.uestc.edu.cn/problem/nico-nico-ni/description)。

# Source


