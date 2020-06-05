
# Content

Vingying 因为偷运快乐水被抓了进去，UESTC_Guest_WiFi 队因为少了一个人没办法去 final 了，于是 HeRaNO 和 ZXyang 决定开展 Vingying 营救计划。

同样还是成电的高速路连通网络，这一网络共有 $n$ 个节点和 $m$ 条双向高速路，一条高速路两端不会是同一个节点，两个节点间最多有一条直接相连的高速路，并且任意两个节点间最多能找出两条没有公共边的简单路径（路径中每个点只经过一次）。更具体来说，对于任意两个节点，如果能找出两点间的三条不同的简单路径，那么肯定有两条路径间有公共边。同时每条高速路长度为 $2$ 的幂次，即第 $i$ 条路长度为 $2^{a_i}$，而且所有 $a_i$ 互不相同。

HeRaNO 和 ZXyang 打听到，有 $q$ 条押运路线，其中有一条就押运着 Vingying，第 $k$ 条押运路线会从 $x_k$ 节点沿第 $w_k$ 长的简单路径到 $y_k$ 节点。HeRaNO 和 ZXyang 打算预先计算出每一条押运路线的长度，以便制定进一步计划。由于 UESTC_Guest_WiFi 队还要准备 final，没时间去算，于是向你进行求助。

# Standard Input

第一行两个正整数 $n,m,q$ ($1\le n ,q\le10^5,n-1\le m \le \frac{3}{2}(n-1)$)，代表节点数、高速路条数、押运路线条数。

接下来 $m$ 行每行三个整数 $u_i,v_i,a_i$ ($1 \le u,v \le n, u \neq v, 0\le a_{i}\le 10^9$)，代表第 $i$ 条高速路两端连接了 $u_i$ 和 $v_i$，这条路的长度为 $2^{a_i}$。保证两个节点间最多有一条直接相连的路，所有 $a_i$ 互不相同。

接下来 $q$ 行每行三个整数 $x_k,y_k,w_k$ ($1 \le x_k,y_k \le n, x_k \neq y_k, 1\le w_{i}\le 10^9$)，代表第 $k$ 条押运路线会从 $x_k$ 节点沿第 $w_k$ 长的简单路径到 $y_k$ 节点。

# Standard Output

输出 $q$ 行，每行一个整数 $ans_k$，代表第 $k$ 条押运路线的长度。由于答案可能过大，请输出答案对 $10^9+7$ 取模后的值。如果不存在这样一条路线，输出 $-1$。

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
<tr><td>4 4 3
1 3 0
4 1 1
2 3 2
2 1 3
1 2 2
1 2 3
3 4 2
</td><td>8
-1
14</td></tr></table>


# Constraints



# Note



# Source


