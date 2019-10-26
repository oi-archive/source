
# Content

给定一个长度为$N$的序列${A}$，序列元素一开始均为0。

需要你设计数据结构并实现两种操作：

1.给出$L,R,a,k,p$五个数。在区间$[L,R]$上，对于区间第i个元素

若$1 \leq i \leq p - L + 1$，加上$a + （i - 1） \times k$。

若$p  - L + 1< i$，加上$a + (p - L + p - L + 1 - i) \times k$。

例如$L,R,a,k,p$ 分别为 3 7 2 2 4，则

$A_3=A_3+2 , A_4=A_4+4 , A_5=A_5+2 , A_6=A_6+ 0 , A_7=A_7-2$

即 $A_3=A_3 + a , A_4=A_4 + a + k , A_5=A_5+a , A_6=A_6 + a - k , A_7=A_7 + a - 2 \times k$

（简单来说就是加了个山峰形

2.给出一个区间$[L,R]$，你需要输出这个区间中最长连续等差数列的长度。

# Standard Input

第一行有两个数$N$，$M$。代表序列长度与操作次数。

接下来M行，每行最开始有一个数$op$。

如果$op=0$，则后面有5个数$L,R,a,k,p$，即第一种操作

如果$op=1$，则后面有2个数$L,R$，即第二种操作

# Standard Output

对于每一个op == 1，输出一个数，表示最长连续等差序列长度。

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
0 1 5 2 2 2
0 3 5 4 2 4
1 1 5</td><td>3
</td></tr></table>


# Constraints

$3\leq M,N \leq 10^5$

对于op == 0 : $1 \leq L < p < R \leq n$ ; $|a| \leq 10000$ ; $|k| \leq 200$

对于op == 1 : $1 \leq L \leq R \leq n$

# Note

感觉我们学校oj跑的有点快啊，到时候如果你暴过去了但是题解里写的复杂度分析出来过大的话，过了最后也不给分的哦。

# Source


