
# Content

如果$m$和$n$都是整数，求$m$的$n$的次方（即$m^n$）的准确值。

# Standard Input

本题有多组输入数据。第一行是输入数据的组数$T$，每组数据占一行，为两个用空格隔开的整数$m$和$n$，$1\le m\le 100$，$0\le n\le 100$。

# Standard Output

对应每组数据，应输出一行，表示$m^n$的准确结果。

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
2 30</td><td>1073741824</td></tr></table>


# Constraints



# Note

可以考虑以下公式：$m^n=\left\\{\begin{array}{ll}
1 &  n=0  \\\\
(m^k)^2 & n=2k \\\\
m\times m^{2k} & n=2k+1
\end{array}\right.$

# Source


