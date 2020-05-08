
# Content

是以膜糖。

这道题十分简单，给出一个数列 $\{a_n\}$，你只需要先找到 $[l,r]$ 中第一个大于等于 $k$ 的数，若不存在则输出 $-1$，否则输出这个数的位置，之后将这个数减 $k$ 即可。

只处理一次太简单了，糖哥要你处理 $m$ 次这样的操作。

# Standard Input

第一行一个正整数 $T$，表示数据组数。

接下来 $T$ 组数据，对于每组数据：

第一行两个正整数 $n,m$；

第二行 $n$ 个正整数 $a_1,a_2,\ldots ,a_n$；

接下来 $m$ 行，每行三个正整数 $l,r,k$。

# Standard Output

输出 $\sum m$ 行，表示所求答案。

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
6 3
1 1 4 5 1 4
1 3 4
3 5 1
1 6 2</td><td>3
4
4</td></tr></table>


# Constraints

$1\le T\le 10^6,1\le n,m\le 10^6,1\le l\le r\le n,1\le k,a_i\le 10^9$，保证 $\sum n,\sum m\le 10^6$。

# Note



# Source


