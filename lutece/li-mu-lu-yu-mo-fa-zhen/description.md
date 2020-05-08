
# Content

利姆露遇到了一个魔法阵，其由 $n$ 个魔法节点构成，每个魔法节点拥有自己的魔力强度。魔法节点间通过共计 $n-1$ 条通道相互连通使魔法阵正常运行。
现在利姆露发现只要向两个不同魔法节点同时注入同样的魔力，那么这两个魔法节点之间最短路径上的节点的魔力强度会同样地增强。
现在利姆露想知道在注入魔力后魔法阵的魔力强度情况会如何，她的操作和询问如下表示：
- $\texttt{1 x y z}$：向 $x,y$ 节点同时注入强度为 $z$ 的魔力（保证 $x,y$ 不相同）；
- $\texttt{2 x y}$：询问 $x,y$ 节点最短通路上魔力强度之和（包括 $x,y$ 节点，由于数值过大只需输出模 $170001$ 的结果即可）。

# Standard Input

第一行两个非负整数 $n,m$，分别表示结点个数，操作和询问个数。
接下来一行包含 $n$ 个非负整数，分别依次表示各个节点上初始的魔法强度。
接下来 $n-1$ 行每行包含两个整数 $a,b$，表示点 $a$ 和点 $b$ 之间连有一条边（保证无环且连通）。
接下来 $m$ 行每行表示一个操作或询问，格式如前述。

# Standard Output

输出为若干行，依次表示每个询问的结果（对 $170001$ 取模）。

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
7 3 2 5 6 
1 4
4 3
2 5
4 2
1 1 3 9
2 2 5
1 5 1 1
2 4 3
</td><td>9
26
</td></tr></table>


# Constraints

$1<n\le10^5,1<m\le10^5$，初始魔力强度和注入魔力强度在 int 范围内。

# Note



# Source


