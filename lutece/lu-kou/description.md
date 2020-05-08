
# Content

Kanade 居住的城市规划得很好，尤其是在街道方面，这令 Kanade 十分自豪 ~~（并没有）~~。

Kanade 居住的城市中共有 $n$ 条街道，如果我们将这个城市抽象成一个二维平面，那么每条街道都可以被描述成一条平行于坐标轴的线段。形式化地，每条街道可以用两个坐标 $(x_{i1},y_{i1}),(x_{i2},y_{i2})$ 表示，其中 $x_{i1}=x_{i2}$ 和 $y_{i1}=y_{i2}$ 两个条件有且只有一个满足。

Yuri 来到了 Kanade 居住的城市观光。她也被这个城市的道路规划吸引了，并且提出了很多问题问 Kanade。每个问题的形式都是一样的：「ねね、教えて、在以 $(-\infty,d)$ 为左下角，$(+\infty,u)$ 为右上角的区域中（包括边界）有多少路口？(✧◡✧)」在 Kanade 居住的城市，只有平行于 $y$ 轴的街道与平行于 $x$ 轴的街道的交点被称作路口，不存在两条以上街道相交于同一路口。

Yuri 问了 $m$ 个这样的问题，因为问题实在太多了 Kanade 回答不过来，于是她请你写一个程序回答这些问题。

# Standard Input

第一行两个整数 $n,m$，表示街道数和询问数。

接下来 $n$ 行，每行四个整数 $x_{i1},y_{i1},x_{i2},y_{i2}$，表示一条街道；

接下来 $m$ 行，每行两个整数 $d,u$，表示一个询问。

# Standard Output

输出 $m$ 行，每行一个整数，表示对对应询问的回答。

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
<tr><td>6 3
1 1 4 1
1 4 5 4
1 1 1 4
4 1 4 4
1 2 3 2
2 2 4 2
3 5
1 3
1 1</td><td>2
4
2</td></tr></table>


# Constraints

$1\le n,m\le 2\times 10^5,1\le x_{i1},x_{i2},y_{i1},y_{i2},u,d\le 10^9$，当 $x_{i1}=x_{i2}$ 时，保证 $y_{i1}<y_{i2}$，当 $y_{i1}=y_{i2}$ 时，保证 $x_{i1}<x_{i2}$，并且保证 $d\le u$。

# Note

![](/source/lutece/lu-kou/img/aHR0cHM6Ly9oZXJhbm8uY29kaW5nLm5ldC9wL1BpY1BsYWNlL2QvUGljUGxhY2UvZ2l0L3Jhdy9tYXN0ZXIvY3Jvc3MucG5n.png)

样例如上图所示，其中只有黄颜色点为路口。

# Source


