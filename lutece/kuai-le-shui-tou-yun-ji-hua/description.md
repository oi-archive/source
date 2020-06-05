
# Content

成电竟然修了一个错综复杂的高速路连通网络！

这一网络共有 $n$ 个节点和 $m$ 条双向高速路，每条高速路正中央设置了一个安检站。由于学校预算毕竟有限，一条高速路两端不会是同一个节点，两个节点间最多有一条直接相连的高速路，并且任意两个节点间最多能找出两条没有公共边的简单路径（路径中每个点只经过一次）。更具体来说，对于任意两个节点，如果能找出两点间的三条不同的简单路径，那么肯定有两条路径间有公共边。

Vingying 想要利用这些路偷运快乐水。他打听到，第 $i$ 个安检站由于技术原因，每天前 $w_i$ 升被偷运的液体不会被查出。于是 Vingying 决定，每天选择一个没选过的点对 $u,v$ ($1\le u< v\le n$)，从 $u$ 号节点获取快乐水，并向 $v$ 号节点偷运快乐水。Vingying 跑得足够快，他一天内可以在高速路网内任意移动，并且可以从 $u$ 号节点获取任意次数、任意数量的快乐水。每天 Vingying 都会尽力偷运尽可能多的快乐水。假设某天他偷运成功了 $x$ 升快乐水，那他这天的收益为 $x⊕u⊕v$ （⊕ 表示按位异或）。

最终，在选完所有点对，功成身退许多年后，Vingying 还是被抓了，但确定犯罪金额数目的时候遇到了难题。你能求出他的收益和是多少么？

# Standard Input

第一行两个正整数 $n,m$ ($1\le n \le 10^5, n-1\le m \le \frac{3}{2}(n-1)$)，代表节点数和高速路条数。

接下来 $m$ 行每行三个整数 $u_i,v_i,w_i$ ($1 \le u_i,v_i \le n, 0 \le w_i \le 10^9$)，代表第 $i$ 条高速路两端连接了 $u_i$ 和 $v_i$，这条路的检查站每天前 $w_i$ 升被偷运的液体不会被查出。保证所给图联通。

# Standard Output

输出一个整数代表答案。

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
<tr><td>5 6
1 2 1
1 3 0
2 3 3
3 4 2
4 5 4
5 3 1</td><td>38</td></tr></table>


# Constraints



# Note

样例解释:

- 当选的点对是 $1,2$ 时，经过 $1 \rightarrow 2$ 可获得最多为 $1$ 升的快乐水，收益为 $1⊕2⊕1=2$。
- 当选的点对是 $1,3$ 时，经过 $1 \rightarrow 2 \rightarrow 3$ 可获得最多为 $1$ 升的快乐水，收益为 $1⊕3⊕1=3$。
- 当选的点对是 $1,4$ 时，经过 $1  \rightarrow 2  \rightarrow 3  \rightarrow 4$ 可获得最多为 $1$ 升的快乐水，收益为 $1⊕4⊕1=4$。
- 当选的点对是 $1,5$ 时，经过 $1  \rightarrow 2  \rightarrow 3  \rightarrow 5$ 可获得最多为 $1$ 升的快乐水，收益为 $1⊕5⊕1=5$。
- 当选的点对是 $2,3$ 时，经过 $2  \rightarrow 3$ 可获得最多为 $3$ 升的快乐水，收益为 $2⊕3⊕3=2$。
- 当选的点对是 $2,4$ 时，经过 $2 \rightarrow 3 \rightarrow 4$ 可获得 $2$ 升快乐水，再经过 $2\rightarrow3\rightarrow5\rightarrow4$ 可获得 $1$ 升快乐水，收益为 $2⊕4⊕(2+1)=5$。
- 当选的点对是 $2,5$ 时，经过 $2\rightarrow3\rightarrow5$ 可获得 $1$ 升快乐水，再经过 $2\rightarrow3\rightarrow4\rightarrow5$ 可获得 $2$ 升快乐水，收益为 $2⊕5⊕(1+2)=4$。
- 当选的点对是 $3,4$ 时，经过 $3\rightarrow4$ 可获得 $2$ 升快乐水，再经过 $3\rightarrow5\rightarrow4$ 可获得 $1$ 升快乐水，收益为 $3⊕4⊕(2+1)=4$。
- 当选的点对是 $3,5$ 时，经过 $3\rightarrow5$ 可获得 $1$ 升快乐水，再经过 $3\rightarrow4\rightarrow5$ 可获得 $2$ 升快乐水，收益为 $3⊕5⊕(1+2)=5$。
- 当选的点对是 $4,5$ 时，经过 $4\rightarrow5$ 可获得 $4$ 升快乐水，再经过 $4\rightarrow3\rightarrow5$ 可获得 $2$ 升快乐水，收益为 $4⊕5⊕(4+1)=4$。

Vingying 的收益和为 $2+3+4+5+2+5+4+4+5+4=38$。

# Source


