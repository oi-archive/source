
# Content

![无标题.png](/source/lutece/afezeria/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMjAvMDYvMTMvd05qeVNla2QyVGZtbFA0LnBuZw==.png)
——*[霜月はるか - EXEC_ViiBaCi_MjiiRa/.](https://music.163.com/#/song?id=26377627)*

---

Alice 和 Bob 玩游戏。现在有一个 $1\times n$ 的棋盘，一共有 $k$ 个黑棋和 $k$ 个白棋。游戏刚开始，从左往右黑白棋子交替着放在棋盘中（先放黑棋），之后 Alice 先手，她可以选择最多 $d$ 个黑棋并且每个棋子可以移动任意步；Bob 可以选择最多 $d$ 个白棋并且每个棋子可以移动任意步。每人至少选择一个棋子并移动一步，否则这一方输掉游戏。移动过程中，棋子不可与其他棋子在同一格子内或者跨过任何一个棋子。

如果两人足够聪明，Alice 想知道：有多少种摆法可以使她一定能获胜？答案对 $10^9+7$ 取模。

# Standard Input

第一行一个正整数 $T$，表示有 $T$ 组数据；
接下来对于每一组数据输入一行三个正整数 $n,k,d$.

# Standard Output

对于每一组数据输出一行表示答案对 $10^9+7$ 取模后的值。

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
2 1 1
3 1 1
7 2 2
7 2 1</td><td>0
1
25
22</td></tr></table>


# Constraints

$1\le T \le 100,1\le n\le 10000,1\le d\le k \le \min(\lfloor\frac{n}{2}\rfloor,50)$

# Note



# Source


