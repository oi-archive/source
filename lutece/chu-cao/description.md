
# Content

有 $n$ 棵草，起始高度均为 0，每棵草每天长高 $v_i$。有 $m$ 个除草计划 ($d_i$, $h_i$)：在第 $d_i$ 天结束后，将所有草超过 $h_i$ 的部分除掉，输出除掉部分的总高度和。$n,m \leq 5\cdot 10^5$, $v_i \leq 10^6$, $d_i, h_i \leq 10^{12}$，保证 $d_i$ 递增。

# Standard Input

第一行两个数 n, m。第二行 n 个数表示每棵草的生长速度。接下来 m 行，每行两个数，表示计划日和计划高度。

# Standard Output

输出 m 行，每行一个数，每个计划的除草量。

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
<tr><td>4 4
1 2 4 3
1 1
2 2
3 0
4 3
</td><td>6
6
18
1
</td></tr></table>


# Constraints



# Note

|Day|除草前|除草后|除草量|
|:-:|:-:|:-:|:-:|
|1| [1, 2, 4, 3] | [1, 1, 1, 1] |6|
|2| [2, 3, 5, 4] | [2, 2, 2, 2] |6|
|3| [3, 4, 6, 5] | [0, 0, 0, 0] |18|
|4| [1, 2, 4, 3] | [1, 2, 3, 3] |1|

# Source


