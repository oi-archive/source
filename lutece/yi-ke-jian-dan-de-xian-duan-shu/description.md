
# Content

人生已如此艰难，让我们活得轻松一点.

给你一个数组 $A[1..n]$，初始时每个元素都为零.

我会请你帮我对数组完成一些操作.

第一种可能，我会给你两个数 $p$ 和 $x$（$1 \le p \le n$），
请你帮我把数组的第 $p$ 个元素替换为 $x$，
即 $A[p] \leftarrow x$.

第二种可能，我会给你两个数 $L$ 和 $R$（$1 \le L < R \le n$），
请你告诉我 $A[L], A[L+1], \dots, A[R]$
这几个数中去掉一个最大值和一个最小值后剩下的数的和是多少.

好了，现在锅都丢给你了，我可以活得轻松一点了.

# Standard Input

输入第一行为一个整数 $n\ (2 \le n \le 10^6)$，表示数组的大小.

第二行有一个整数 $m\ (1 \le m \le 10^6)$，表示我需要你帮我完成的任务的个数.

第 $3$ 到 $m+2$ 行每行有 3 个整数 $o\ x\ y$.
如果 $o = 0$，代表我需要使 $A[x] \leftarrow y$，
此时 $1 \le x \le n,\ |y| \le 10^9$.
如果 $o = 1$，代表我想知道 $A[x], A[x+1], \dots, A[y]$
去掉一个最大值和一个最小值后剩下的数的和为多少，
此时 $1 \le x < y \le n$.

# Standard Output

对每个 $o = 1$ 的任务，
输出只有一个整数的一行，
该整数表示区间 $[x, y]$ 中的数
去掉一个最大值和一个最小值后剩下的数的和.

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
<tr><td>5
5
0 2 1
0 4 -2
1 1 5
0 1 5
1 1 4</td><td>0
1</td></tr></table>


# Constraints



# Note



# Source


