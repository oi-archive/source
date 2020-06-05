
# Content

星际旅行中的 Cjj 来到了一个新的星球。这个星球上有 $n$ 个城市，编号为 $1$ 到 $n$。从一个城市去往另一个城市需要利用传送门。已知 $i$ 号城市有 $m_i$ 个传送门，分别能到达 $v_i[0],v_i[1],\ldots,v_i[m_i-1]$ 号城市。能使用哪一个传送门是由能量值决定的。具体地说，如果你身上有 $c$ 点能量值，那么你可以到达 $v_i[x]$ 号城市，$x$ 满足 $0\le x \le m_i-1$ 且 $x \equiv c \pmod{m_i}$。

通过查找资料，Cjj 了解到到达这些城市后能量值会发生什么样的变化。具体地说，当你到达 $i$ 号城市后，你的能量值会变化 $k_i$，$k_i$ 为正表示能量值增加 $|k_i|$，为负表示减少 $|k_i|$。能量值可以是负数。

Cjj 发现，如果他以某个能量值为初始值降落在某个城市，那么他通过传送门进行旅行的路线是固定的。同时，因为每个城市至少有一个传送门，所以如果他不中止旅行的话，他可以无限地旅行下去。为了优化行程安排，Cjj 想知道，如果他以 $y$ 点能量值为初始值降落在 $x$ 号城市，有多少城市可以被他访问无限多次。要注意的是，当他降落到 $x$ 号城市后，他的能量值就会变化 $k_x$。

# Standard Input

第一行包含一个整数 $n$ ($1 \le n \le 1000$)，表示城市数量。

第二行包含 $n$ 个整数，第 $i$ 个整数为 $k_i$ ($-10^9 \le k_i\le 10^9$)，表示到达 $i$ 号城市后能量值的变化量。

接下来 $2n$ 行表示每个城市的传送门情况。第 $(2i+1)$ 行包含一个整数 $m_i$ ($1 \le m_i \le 10$)，表示 $i$ 号城市的传送门数量。第 $(2i+2)$ 行包含 $m_i$ 个整数 $v_i[0],v_i[1],\ldots,v_i[m_i-1]$ ($1 \le v_i[j] \le n$)，表示传送门分别到达哪个城市。

接下来一行包含一个整数 $q$ ($1 \le q \le 10^5$)，表示询问次数。

接下来 $q$ 行，每行包含两个整数 $x$ 和 $y$ ($1 \le x \le n, -10^9 \le y \le 10^9$)，表示他以 $y$ 点能量为初始值降落在 $x$ 号城市。

# Standard Output

输出 $q$ 行，对于每次询问，输出有多少城市可以被访问无限多次。

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
<tr><td>4
4 -5 -3 -1
2
2 3
1
2
3
2 4 1
4
3 1 2 1
6
1 0
2 0
3 -1
4 -2
1 1
1 5</td><td>1
1
1
3
1
1</td></tr></table>


# Constraints



# Note

样例中路线分别如下（括号内为能量值）：

- $1(4) \rightarrow 2(−1) \rightarrow 2(−6) \rightarrow \ldots$
- $2(−5) \rightarrow 2(−10) \rightarrow \ldots$
- $3(−4) \rightarrow 1(0) \rightarrow 2(−5) \rightarrow 2(−10) \rightarrow \ldots$
- $4(−3) \rightarrow 1(1) \rightarrow 3(−2) \rightarrow 4(−3) \rightarrow \ldots$
- $1(5) \rightarrow 3(2) \rightarrow 1(6) \rightarrow 2(1) \rightarrow 2(−4) \rightarrow \ldots$
- $1(9) \rightarrow 3(6) \rightarrow 2(1) \rightarrow 2(−4) \rightarrow \ldots$

# Source


