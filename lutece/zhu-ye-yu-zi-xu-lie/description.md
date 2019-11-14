
# Content

柱爷是个爱思考的人。这天，柱爷在思考子序列的问题。

所谓数列$A\_1，A\_2，…，A\_n$的子序列，是指$A\_{b1}， A\_{b2}，…，A\_{bm}$，满足$1\le b_1<b_2<...<b_m \le n$。

当然，这样的子序列有很多。但柱爷要找的是完美子序列！

#### 所谓完美子序列，还需满足以下条件：
* #### $m \ge 2$
* #### $|A\_{b\_i} - A\_{b\_{i+1}} | \le k, 1 \le i < m$

现在问你，数列中一共有多少完美子序列。

答案可能很大，输出对1000000009取模。

# Standard Input

第一行输入两个数$n,k$。

第二行输入$n$个数，表示$A_i$的值。

数据保证：

* $2 \leq n \leq 100000，1 \leq k \leq 100000000$

* $1 \leq A_i \leq 100000000$

# Standard Output

输出仅一个数，完美子序列的数量。答案可能很大，输出对1000000009取模。

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
<tr><td>4 2
1 3 7 5
</td><td>4
</td></tr></table>


# Constraints



# Note

对于样例，存在以下4个完美子序列：
* $1,3$
* $1,3,5$
* $3,5$
* $7,5$

# Source


