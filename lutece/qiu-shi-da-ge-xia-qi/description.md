
# Content

胜负胸中料已明，又从堂上出奇兵。秋实大哥是一个下棋好手，独孤求败的他觉得下棋已经无法满足他了，他开始研究一种新的玩法。

在一个$n\times m$的棋盘上，放置了$k$个车，并且他在棋盘上标出了$q$个矩形，表示矩形内部是战略要地。

秋实大哥要求一个矩形内的每一个格子，都至少能被一辆在矩形内的车攻击到，那么这个矩形就是被完整保护的。

现在秋实大哥想知道每一个矩形是否被完整保护。

# Standard Input

第一行包含四个整数$n，m，k，q$，表示棋盘的大小，车的数量以及矩形的数量。

接来下$k$行，每行包含两个整数$x，y$，表示有一辆车位于从左往右第$x$列，从下往上第$y$行。

接下来$q$行，每行包含四个整数$x1，y1，x2，y2$，表示一个矩形的左下角和右上角坐标。

$1\leq n，m\leq 10^5$，$1\leq k，q\leq 2\cdot 10^5$，$1\leq x1\leq x2\leq 10^5$，$1\leq y1\leq y2\leq 10^5$，$1\leq x\leq 10^5$，$1\leq y\leq 10^5$。

# Standard Output

输出$q$行，对于每一次询问，这个矩形若被完整保护了输出"YES"，否则输出"NO"。

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
<tr><td>4 3 3 3
1 1
3 2
2 3
2 3 2 3
2 1 3 3
1 2 2 3</td><td>YES
YES
NO</td></tr></table>


# Constraints



# Note

样例的图形如下：

![title](/source/lutece/qiu-shi-da-ge-xia-qi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTA3MS8yMDE1MDQxMTIyNDQ0NDA5MTkucG5n.png)

# Source


