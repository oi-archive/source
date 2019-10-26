
# Content

为了测试算法生成的随机数的均匀性，现产生$n$个随机整数，假设随机数的范围为$[0,r]$，把该区间均匀分成$m$个，试统计落在各区间的随机数个数。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\le 1000$），表示测试数据的组数。每一组测试数据只有一行，开始是三个整数$n$、$m$和$r$，表示该行随机整数的个数、划分的区间数和随机数上界，随后是$n$个随机数，该行每个数后均有一个空格。该行没有其它多余的符号。$0<m<200$，$0<n<30000$，$100\le r<32768$。

# Standard Output

对应每组输入，输出一行，共$m$个数，表示落入各区间（从左到右）的随机数个数，每个数后有一个空格。该行不能有其它多余的符号。

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
20 5 20 13 11 14 16 5 4 11 2 13 19 19 12 1 19 3 1 13 9 12 5 
20 5 14 0 10 7 3 11 7 6 2 5 8 4 8 11 9 10 5 12 10 12 6</td><td>4 3 3 6 4 
2 4 6 6 2</td></tr></table>


# Constraints



# Note

当区间不是最后一个时，按左闭右开计算。

# Source


