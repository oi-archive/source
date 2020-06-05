
# Content

$A$ 国有 $n$ 座城市，$m$ 条双向道路，$B$ 国在 $A$ 国的第 $i$ 座城市安排了 $p_i$ 名间谍。$B$ 国首领打听到 $A$ 国首领近日的出行有一定规律，他会选择三座彼此间有道路直接相连的城市 $x,y,z$，出行路线为 $x \rightarrow y \rightarrow z \rightarrow x$。

$B$ 国首领想知道，$A$ 国首领有多少种可能的出行路线。同时他还想知道，在所有可能路线经过的城市中，安排有 $B$ 国间谍数量最少的城市的间谍数量是多少。

# Standard Input

第一行两个正整数 $n,m$ ($1\le n \le10^5,1\le m \le 2.5\times10^5$)，代表城市数与道路条数。

接下来一行 $n$ 个整数 $p_1,p_2,\dots,p_n$ ($1\le p_{i}\le 10^6$)，$p_i$代表第 $i$ 座城市中的间谍数量。

接下来 $m$ 行每行两个个整数 $u,v$ ($1 \le u,v \le n$)，代表一条连接了 $u$ 和 $v$ 的道路。保证没有自环和重边。

# Standard Output

输出一行两个整数，分别代表可能的出行路线的数量和所有可能路线经过的城市中间谍数量最小的城市的间谍数量。当可能出行路线数量为 $0$ 时，第二个整数输出 $-1$。

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
<tr><td>5 5
1 2 3 4 5
1 2
2 3
3 4
4 5
3 1</td><td>6 1</td></tr></table>


# Constraints



# Note



# Source


