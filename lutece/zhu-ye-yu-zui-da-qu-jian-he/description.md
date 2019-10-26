
# Content

柱爷爱思考，凡事喜欢举一反三，常常能想到别人没想过的问题。

比如最大区间和这个问题：在一数列上选出一段区间，使得这段区间和最大。

柱爷想：如果选出两段区间（不相邻）会怎样呢？

柱爷很快想到了答案，你呢？

# Standard Input

第一行输入一个数$N$，表示数组的长度。

第二行输入$N$个数，表示各元素的值。

数据保证：

* $3 \le N \le 500000$

* $ -100 < A_i < 100$

# Standard Output

输出一个数，表示数组的两段区间（不相邻）之和的最大值。

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
2 3 -3 3 -2 4
</td><td>10
</td></tr></table>


# Constraints



# Note

对于样例，选择$2,3$和$3,-2,4$这两个区间，和为$10$.

PS.区间不相邻是指**前一个区间的最后一个数和后一个区间的第一个数不相邻**

# Source


