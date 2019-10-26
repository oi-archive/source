
# Content

蒟蒻`forgottencsc`这学期有一门叫做计算机网络的课。

某天上课时，老师讲到了一个叫做吞吐量的概念。

然而`forgottencsc`昨天晚上没睡好，所以他前半节课都在摸鱼，什么都没听进去。

老师发现了正在摸鱼的`forgottencsc`，把他点起来回答问题。

老师在黑板上画了一个树形网络，并标出了每条链路（即树上的每条边）上的带宽。

热心的徐大爷`Bananatech`悄悄的告诉了他吞吐量的定义：整条链路上的最低带宽。

老师连着问了`forgottencsc`很多形如“节点$u$到节点$v$的最短链路的吞吐量是多少”问题，然而`forgottencsc`并不能理解吞吐量的定义，更不知道什么是树，这时候他低头看了一眼TIM发现了正在水群的你，并把问题抛给了你。

# Standard Input

第一行有两个数$N,Q$，代表老师画出的树有$N$个节点，并对`forgottencsc`进行了$Q$次灵魂拷问。

接下来$N-1$行，每行有三个数$u,v,w$，代表存在一条从节点$u$直接连向节点$v$的双向链路，且吞吐量为$w$。

接下来$Q$行，每行有两个数$u,v(u\neq v)$，代表老师的灵魂拷问。

# Standard Output

对于每个灵魂拷问，输出对应的答案，即节点$u$到节点$v$的最短链路的吞吐量。

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
<tr><td>6 5
1 2 7
2 3 10
2 4 8
4 6 9
4 5 11
1 6
2 4
3 5
1 3
6 5</td><td>7
8
8
7
9
</td></tr></table>


# Constraints

$2 \leq N, Q \leq 10^5$

$1 \leq w_i \leq 10^9$

$1 \leq u, v \leq N$，且保证 $u \neq v$

# Note

关于树的定义可以参考 [维基百科](https://en.wikipedia.org/wiki/Tree_(graph_theory))

你以为我是图论题，其实我是数据结构哒！

# Source


