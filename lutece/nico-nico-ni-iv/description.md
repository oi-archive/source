
# Content

这次的 [鬼畜视频](https://www.bilibili.com/video/BV1cs411m71i) 正在直播！它可以用一个初始为空的字符串 $S$ 来表示，字符将被逐个添加到 $S$ 的末尾。

作为一名经验丰富的计数菌，每添加一个字符后，你都会选择 $S$ 的一个子串 $S[l..r]$，并计算它的出现次数。

# Standard Input

第一行一个正整数 $n$，表示一共添加了 $n$ 个字符到 $S$ 的末尾。

这次你需要在线计数，因此之后的输入将被加密。设 $x_i$ 为添加第 $i$ 个字符后你计算的答案，并规定 $x_0 = 0$。

接下来有 $n$ 行，其中第 $i$ 行包含三个整数 $c_i',\ l_i',\ r_i'$，表示加密后的输入。

真实的输入为 $c_i = c_i' \oplus x_{i-1}$，$l_i = l_i' \oplus x_{i-1}$，$r_i = r_i' \oplus x_{i-1}$，其中 $\oplus$ 表示按位异或运算。

$c_i$ 为第 $i$ 个要添加的字符对应的 ASCII 码，保证它表示一个小写英文字母。

# Standard Output

输出 $n$ 行，第 $i$ 行一个整数 $x_i$，表示添加第 $i$ 个字符后你计算的答案。

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
<tr><td>6
110 1 1
104 3 3
98 3 2
110 0 5
111 0 0
107 7 4</td><td>1
1
1
1
2
2</td></tr></table>


# Constraints

$1 \leq n \leq 2 \times 10^5$

$1 \leq l_i \leq r_i \leq i \leq n$

$97 \leq c_i \leq 122$

# Note

样例对应的真实输入为：

```
6
110 1 1
105 2 2
99 2 3
111 1 4
110 1 1
105 5 6
```

# Source


