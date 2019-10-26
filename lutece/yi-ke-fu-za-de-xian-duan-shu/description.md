
# Content

秦怼长是一个爱钦定的人，
一年一度的集训队选拔又来了，
秦怼决定钦定一些人品特别好的人进入集训队.

秦怼先是给出了一个数组 $A[1..n]$，
初始元素为 $a_1, a_2, ..., a_n$ 是 $1 \sim n$ 的一个排列.
然后秦怼迅速地对数组施以了 $m$ 个操作.
每个操作针对一个区间 $[l, r]\ (1 \le l \le r \le n)$，
秦怼将区间内的元素从小到大排序或者从大到小排序.

如果你能猜出最终数组中第 $k$ 个元素 $A[k]$ 的值，
就能钦定进队啦(误

# Standard Input

输入第一行为两个整数 $n (1 \le n \le 10^5)$ 和 $k (1 \le k \le n)$，
表示数组的大小和需要猜的数的下标.

第二行有 $n$ 个整数 $a_1, a_2, ..., a_n$，
表示数组中初始的元素，且是 $1 \sim n$ 的一个排列.

第三行一个整数 $m (1 \le m \le 10^5)$，
表示操作的个数.

接下来有 $m$ 行，每行三个整数 $o\ l\ r (1 \le l \le r \le n)$，表示一个操作.
如果 $o = 0$，表示对区间 $[l,r]$ 从小到大排序.
如果 $o = 1$，表示对区间 $[l,r]$ 从大到小排序.

# Standard Output

输出包含一个整数的一行，
为最终数组中 $A[k]$ 的值.

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
<tr><td>5 3
1 2 3 4 5
3
1 1 3
0 2 4
1 3 5</td><td>5</td></tr></table>


# Constraints



# Note



# Source


