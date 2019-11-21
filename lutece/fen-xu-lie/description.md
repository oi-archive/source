
# Content

最近，你的老师给了你一个序列，让你把这个序列划分成若干段小的序列。注意，这个操作不能改变每个数在原来序列中的位置。

对于分开的每个小的序列，都有一个对应的权值，计算方法如下：

假设这个小序列中的数是:$c_1, c_2 \cdots c_k$，则权值为$(\sum_{i=1}^k c_i) ^ 2 + m$，其中，$m$为常数。

现在你要找到一种分法，使得所有小序列的总权值之和最小。

# Standard Input

题目有多组数据。

对于每一组数据，第一行是两个数$n,m$，分别表示的是序列中的数的个数，和公式中出现的常数$m$。

接下来有n个数，其中第$i$个数表示的是序列中的第$i$个数$c_i$。

$0 < n \leq 500000$

$0 \leq c_i$

# Standard Output

对于每一组数据，输出一行，包含一个数，表示最小的权值和。

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
<tr><td>5 5
5 9 5 7 5</td><td>230</td></tr></table>


# Constraints



# Note

保证答案不超过long long 的范围。

# Source


