
# Content

玩梗小鬼 biss 嗷，立即出警！

可是他们最近却遇到了难题，他们发现 $n$ 座城市里到处都有人顶着臭鼬头走来走去，但是他们一时半会却没办法分清谁是在玩梗换头谁是臭鼬本人，于是他们决定严加监控。

这 $n$ 座城市之间共有 $n-1$ 条道路将他们互相连通，在一个城市驻扎一个梗警察警队需要消耗 $a_i$ 的警力，而驻扎在一座城市内可以完美地监视该城市和与之邻接的所有城市，为了节约警力，梗警察想知道监控全部城市最少需要多少警力，这个问题他们可以轻松运用树形 DP 解决。

可是这还没完，一个城市的居民们有的时候会变得遵纪守法，有的时候又狂妄不堪四处玩烂梗，就是说驻扎所需要的警力是会变的，现在有 $m$ 次变化，每一次变化后，城市 $s$ 中需要驻扎的警力变为了 $t$ ，并且影响一直存在。因为很多梗警察是弱智，高效地进行 $m$ 次运算对于梗警察来说过于困难了，你能帮帮他们回答每次变化后监控全部城市最少需要多少警力吗？

# Standard Input

第一行包括两个数，$n$ 和 $m$ ($1\leq n,~m\leq 10^5$)

第二行包括 $n$ 个数，第 $i$ 个数表示一开始驻扎在 $i$ 城市中需要耗费 $a_i$ 的警力 ($1\leq a_i \leq 10^4$)

接下来 $n-1$ 行，每行两个数 $u$ 和 $v$ 表示 $u$ 和 $v$ 之间存在一条道路使得两座城市邻接。

接下来 $m$ 行，每行两个数字 $s$ 和 $t$ 表示城市 $s$ 需要驻扎的警力变为了 $t$

# Standard Output

输出 $m$ 行，每行一个数，第 $i$ 个行代表发生了前 $i$ 次变化后需要驻扎的警力最小是多少

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
<tr><td>5 1
10 12 10 12 10
1 2
2 3
1 4
4 5
1 1</td><td>21</td></tr></table>


# Constraints



# Note

弱数据警告

# Source


