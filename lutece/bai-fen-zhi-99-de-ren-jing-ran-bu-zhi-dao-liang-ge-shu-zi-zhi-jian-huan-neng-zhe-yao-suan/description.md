
# Content

异或是一种位运算是怎么回事呢？异或相信大家都很熟悉，但是异或是一种位运算是怎么回事呢，下面就让小编带大家一起了解吧。
异或是一种位运算，其实就是运算法则相当于不带进位的二进制加法，大家可能会很惊讶异或怎么会是一种位运算呢？但事实就是这样，小编也感到非常惊讶。
这就是关于异或是一种位运算的事情了，大家有什么想法呢，快来通过这道题分享一下你的做法吧！
有一棵 $n$ 个节点有点权的树，节点编号 $1$ 到 $n$，问存在多少对 $1\le i<j\le n$，使得 $i$ 到 $j$ 的最短路径上点权异或和在 $[l,r]$ 之间。

# Standard Input

第一行三个整数 $n,l,r$，意义同上所述。
第二行 $n$ 个整数 $a_i$ 依次为节点 $1$ 到 $n$ 的点权。
第三到 $n+1$ 行每行两个正整数 $u,v$，表示 $u,v$ 之间有一条边。

# Standard Output

一个整数代表答案。

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
<tr><td>5 1 5
4 2 4 2 5 
1 2
1 3
2 4
3 5</td><td>5</td></tr></table>


# Constraints

$1\le n\le 10^5,0\le l\le r\le 10^9,0\le a_i\le 10^9$，保证给的图构成一棵树。

# Note



# Source


