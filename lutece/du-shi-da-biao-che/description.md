
# Content

一辆车行驶在 m 车道的高速路上,每行驶1公里汽车有$\frac{1}{3}$的概率向左移动一个车道,$\frac{1}{3}$的概率停留在当前车道,$\frac{1}{3}$的概率向右移动一个车道.当然,如果左右没有车道,就不会移动.比如说如果当前汽车在最左边的车道,并且右边有车道,那么它有$\frac{1}{2}$停留,有$\frac{1}{2}$的概率向右移动.如果左右没有车道，当然就不会换道了。


高速路上有 k 个障碍物,车辆撞上就是车毁人亡.
那么车辆安全行驶 n 公里的概率是多少?

请注意车的换道是在整公里之间进行的，不会在整公里处换道。

在第n公里撞上也算车毁人亡。

# Standard Input

第一行三个数 $m,k,n$。 $1\le m\le 3\times 10^4, 0 \le k \le 10^2, 1 \le n \le 10^3$

第二行一个数$p$,表示从左数第$p$道为起始车道。

接下来k行，每行两个数 $a_i, b_i$, 表示左数第$a_i$个车道距离起点$b_i$公里有一个障碍物。

保证$p, a_i, b_i$是合法的 $b_i > 0$。

# Standard Output

一个数，表示车辆安全行驶 n 公里的概率。保留6位小数。

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
<tr><td>3 1 3
2
2 1</td><td>0.666667</td></tr></table>


# Constraints



# Note



# Source


