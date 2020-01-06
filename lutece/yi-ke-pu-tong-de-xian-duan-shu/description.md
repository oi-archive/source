
# Content

![](/source/lutece/yi-ke-pu-tong-de-xian-duan-shu/img/aHR0cHM6Ly9naXRodWIuY29tL0FicmV0by9pbWcvcmF3L21hc3Rlci9tYXh3ZWxsLmpwZw==.jpg)

出题人明天就要半期考试了，课程是《火葬场与波》.
出题人倒在血泊中，一双有力的手摇晃着出题人的肩膀：
“同志，醒醒，你还有题没出完呢”.
以下是他的遗言：

给你一个数组 $A[1..n]$，初始值全为 0.
你需要写一棵裸的区间修改、区间查询的线段树，
以支持两个操作.
第一个操作是对区间 $[L, R]$ 内的数每个数加上 $v$.
第二个操作是给出区间 $[L, R]$ 内所有数的和.

# Standard Input

第一行包含两个整数 $n (1 \le n \le 10^6)$ 和 $m (1 \le m \le 10^6)$，
分别是数组的大小和操作的个数.

接下来 $m$ 行，每行四个用空格分隔的整数 $o\ l\ r\ v\ (1 \le l \le r \le n, |v| \le 10^3)$.
如果 $o = 0$，则表示对区间 $[l,r]$ 内每个数都加上 $v$.
否则，请给出区间 $[l,r]$ 内所有数的和，此时 $v \equiv 0$.

# Standard Output

对于每个 $o \ne 0$ 的操作，
输出包含一个整数的一行，表示对应区间内所有数的和.

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
<tr><td>5 4
0 2 4 5
1 3 5 0
0 1 3 -2
1 1 5 0</td><td>10
9</td></tr></table>


# Constraints



# Note



# Source


