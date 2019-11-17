
# Content

UDK和RU在一个白色的方格棋盘上玩游戏，棋盘有$N$行$M$列，由$N\times M$个小方格组成。两人轮流进行游戏，UDK先开始，然后是RU。在每一轮游戏中，当前一方需要在棋盘上选择一个$1\times k$或$k\times 1$的全白矩形，并将里面的$k$个小格子全部染成黑色（每轮$k$的大小都可以由当前玩家自己决定），将最后一个格子染色的一方获得游戏胜利。

现在假设两人都采取最佳的策略，给定棋盘大小，请问谁将获得胜利？

# Standard Input

数据的第一行是一个整数$T$($0\leq T\leq 10000$)，代表一共有$T$组测试数据。

接下来$T$行，每行由两个整数$N$和$M$组成($1\leq N, M\leq 100$)，表示了每组数据中棋盘的大小。

# Standard Output

请严格输出$T$行，每行仅包括一个字符串`UDK` 或者 `RU`，代表每组测试数据对应的胜利一方的姓名。

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
<tr><td>2
1 2
2 2</td><td>UDK
RU</td></tr></table>


# Constraints



# Note

Sample Input中共有两组数据，其中第一组数据棋盘的大小是$1\times 2$，即$1$行$2$列，UDK先手，可以直接选择涂$1\times 2$的矩阵，把棋盘完全染色从而直接获得胜利。

请严格按照输出规则输出，行末不允许有多余的空格，最后一组数据行末同样需要换行。

# Source


