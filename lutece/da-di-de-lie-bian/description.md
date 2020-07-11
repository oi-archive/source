
# Content

![pic](/source/lutece/da-di-de-lie-bian/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMTcvdFBIVm43bFU4NE9lSTZiLmpwZw==.jpg)

山无棱，天地合。ZXyang 和 HeRaNO 一起从 wf （winterfall）启程，准备修复灾难对大地带来的创伤。大地在经历了冷和热的双重打击（热胀冷缩）之后，出现了很多裂缝，可以看作 $n$ 条相互不重合的直线。然而这个世界的大地是有灵守护的，灵会担负起修复大地的工作。ZXyang 的工作就是找到大地上的奇异点，并且根据奇异点裂开的程度选择合适的魔法修复药剂（胶水）修复奇异点。神奇的是，这片土地上的奇异点刚好位于地图上坐标轴的整点处。所以 ZXyang 决定以大陆的左下角为参考点（大陆向右上无限延伸），修复地图上整点处的奇异点。现在他的工作就是知道这些点的数量，用以对症下药。

定义一个点为 $t$ 直线交点，当且仅当该点的横纵坐标为非负整数且刚好有 $t$ 条直线经过该点。给出平面上 $n$ 条相互不重合直线的斜截式 $y=kx+b$，询问对于 $2 \leq t \leq n$，$t$ 直线交点的数量。

# Standard Input

第一行一个整数 $n$，表示一共有 $n$ 条直线 ($2\leq n\leq 10^4$)。

接下来$n$行，每行包括两个整数 $k_i$ 和 $b_i$，表示第 $i$ 条直线的斜率和截距 ($0\leq k,b\leq 10^2$)。数据保证直线相互不重合。

# Standard Output

一行输出 $n-1$ 个数，第一个数表示平面上两直线交点的数目，第二个数表示平面上三直线交点的数目，以此类推。每两个数之间用一个空格隔开。

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
<tr><td>3
1 1
3 0
0 3</td><td>2 0</td></tr></table>


# Constraints



# Note

样例解释：

![pic.jpg](/source/lutece/da-di-de-lie-bian/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTAvMjgvb09DZTY5NExNdm51M2htLmpwZw==.jpg)

对于这种情况，可以看到三条线虽有三个交点，但是红线与绿线的交点没有在整数坐标处。所以两直线交点有两个，三直线交点为零个。

# Source


