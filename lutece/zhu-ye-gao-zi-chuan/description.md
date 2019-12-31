
# Content

柱爷有一个字符串$S$，对于其中的每一个不同子串$S^*$，柱爷都能$O(1)$的得到这些字符串的所有匹配位置

即能知道所有的$[L,R]$区间使得 $S[L,R] = S^*$，然后柱爷会把这些$[L,R]$区间的每个位置做上标记，如果最后这些标记位置形成了$K$个连通块，那么它对答案的贡献就是$1$

柱爷早就知道了答案，但他现在想问你知道吗？

# Standard Input

输入第一行一个字符串$S$，只有小写字母，保证$|S|  \leq 10^5$

接下来一行一个$K$，保证$1 \leq K \leq |S|$

# Standard Output

输出一行表示答案

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
<tr><td>abaab
2
</td><td>3
</td></tr></table>


# Constraints



# Note

$3$个不同的子串分别是: $a$ , $ab$ , $b$

# Source


