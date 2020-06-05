
# Content

人气歌手 PAFF 近日将展开巡回演唱会，作为头号粉丝，NEKO 自然不会错过这次机会。

NEKO 所在地有 $n$ 个城市，PAFF 将在每个城市都展开演唱会，在 $i$ 号城市的演唱会门票价格为 $a_i$。这些城市间有 $m$ 条道路，每条道路双向连接两个城市，且有一定路费。

由于 NEKO 平日经常出去玩，因此她并不知道演唱会期间她会住在哪个城市。因此她想知道，如果她从 $i$ 号城市出发，参与任意一场演唱会，再回到 $i$ 号城市，最少的花费是多少（可以直接留在 $i$ 号城市参与演唱会，此时不花费路费）。

# Standard Input

第一行包含两个整数 $n$ 和 $m$ ($2 \le n \le 2 \times 10^5, 1\le m \le 2 \times 10^5$)，表示城市与道路的数量。

接下来 $m$ 行， 每行三个整数 $u,v,w$ ($1 \le u,v \le n, u \ne v, 1 \le w \le 10^{12}$)，表示一条双向连接 $u$ 号与 $v$ 号城市路费为 $w$ 的道路。数据保证无重边。

接下来一行包含 $n$ 个整数 $a_1,a_2,\dots,a_n$ ($1 \le a_i \le 10^{12}$)，表示各城市的演唱会门票价格。

# Standard Output

一行 $n$ 个整数，用空格隔开，第 $i$ 个整数表示从 $i$ 号城市出发最少的花费。

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
<tr><td>2 1
1 2 1
10 5</td><td>7 5</td></tr></table>


# Constraints



# Note

样例中，如果从 $1$ 号城市出发，有两种方案：

1. 参与 $1$ 号城市的演唱会，路费为 $0$，门票为 $10$，总花费为 $10$。
2. 参与 $2$ 号城市的演唱会，去程的路费为 $1$，门票为 $5$，返程的路费为 $1$，总花费为 $7$。

因此花费最少为 $7$。

# Source


