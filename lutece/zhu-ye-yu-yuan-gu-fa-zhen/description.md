
# Content

众所周知，柱爷的数学非常好，尤其擅长概率论！

某日柱爷在喵哈哈村散步，无意间踏入了远古法阵！

法阵很奇怪，是一个长度为 $N$ 的走廊，初始时柱爷在最左边，现在柱爷要到最右边去！

柱爷的行动方式如下:

*  每个回合柱爷会投一次骰子，根据骰子上的点数 $X$，柱爷会相应的往右边移动 $X$ 步；

*  骰子的数值是 $1$ 到 $6$，取到每面的概率相同；

*  在某些位置可能有传送门，一旦柱爷在该回合结束后在这个位置上，会被强制传送到传送门的另外一边

*  传送门是单向的，同时每个位置不会有超过 $1$ 个传送门，同时不会存在 $a \rightarrow b,b \rightarrow c$ 这种情况；

*  在任意时刻柱爷都必须保证在法阵内，也就说如果在这一回合结束后柱爷的位置在法阵外，那么这回合柱爷将什么都不做.

那么请问柱爷到达最右边的期望回合数是多少呢？或者是永远都无法到达？

# Standard Input

第一行两个整数 $N,M$，分别表示法阵的长度和传送门的数量。

接下来 $M$ 行，每行两个整数 $u,v$，表示从 $u$ 到 $v$ 有一扇传送门。

数据保证:

*  $1 \leq N \leq 300$

*  $0 \leq M \leq [{N-2 \over 2}]$

*  $1 < u < N ，1 \leq v \leq N，u \neq v$

# Standard Output

输出仅一行，表示期望的回合数，如果永远不能到达，输出 $-1$。

答案误差在 $10^{-6}$ 以内将被忽略。

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
<tr><td>100 0
</td><td>33.0476190476</td></tr><tr><td>100 2
2 3
99 100
</td><td>29.8571428571</td></tr></table>


# Constraints



# Note

你可能需要一些概率论 & 线性代数的知识才能解决本题！

# Source


