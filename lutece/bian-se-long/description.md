
# Content

`FoolishMe`最近正在玩一个游戏，游戏的具体内容如下：  

- 游戏地图是一个有n个点m条边的无向图，每条边都拥有一个颜色，并双向连接了两个点。  
- 每局游戏的目标是控制一只`变色龙`从$1$号点走到$n$号点，当站在某个点时，可以选择将`变色龙`身上的颜色变成任意颜色或保持原来的颜色不变，若选择改变颜色则要消耗$1$点体力值。
- 当要走某条边时，当且仅当此时`变色龙`身上的颜色与该边的颜色相同时才可以通过。   
- 初始时候(一开始站在$1$号点)`变色龙`身上没有颜色，必须消耗$1$点体力值来获得一种初始颜色，同样地，这个初始颜色可以任意选择。  

现在`FoolishMe`又开了一局游戏，他想知道为了完成游戏目标所需花费的体力值最少是多少。

# Standard Input

第一行两个数$n$和$m$表示n个点和m条边。$(2 \leq n \leq 10^5, 1 \leq m \leq 2 \times 10^5)$  
接下来m行，每行3个数 $u,v,c$ 表示有一条连接$u$和$v$且颜色为$c$的边$(1 \leq u,v \leq n, 1 \leq c \leq 10^6)$

# Standard Output

输出一个数，表示完成目标所需花费的最少体力值。如果无法完成游戏目标则输出-1。

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
<tr><td>6 7  
1 2 1  
2 3 2  
3 5 3   
3 6 3  
4 5 3   
4 1 2  
5 6 1  </td><td>2</td></tr></table>


# Constraints



# Note

样例解释：  
路径为1->4->5->3->6，其中在1号点时变成2号颜色，在4号点时变成3号颜色。共消耗2点体力。      
任意时刻变色龙只能拥有一种颜色。

# Source


