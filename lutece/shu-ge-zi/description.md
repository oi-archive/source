
# Content

最近HS很寂寞，路过教学楼时看见一块块的地砖顿时感觉很无聊，就开始数了起来。你作为一个好心的路人甲决定帮助HS数地砖，以尽快完成这项浩大的工程。

学校的地砖由黄色的网格线和红色的正方形组成（样式如下图）。设所有砖块大小都是$1\times 1$的，黄色直线宽度为$W$，红色正方形边长为$L$。HS正在数一个矩形$(x\_1,y\_1)\rightarrow(x\_2,y\_2)$(矩形的左下角和右上角坐标)里有多少块黄色的地砖，请帮他尽快数完。（坐标原点在红色正方形的左下角，即$(0,0)\rightarrow(L,L)$的正方形为红色）

下面是地砖的局部(第二组样例，绿色框住部分为选定的矩形）

![.*](/source/lutece/shu-ge-zi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTU1LzIwMTQwMjAyMjE1NDU2NDY3MTcuanBn.jpg)

# Standard Input

第一行有一个整数$T$（$T\leq 10,000$），表示数据组数

之后有$T$行，每行一组数据，包含$6$个整数：$W$，$L$，$x\_1$，$y\_1$，$x\_2$，$y\_2$，($0\leq W, L, x\_1, y\_1, x\_2, y\_2\leq 10,000$，$W+L>0$，$x\_1<x\_2$，$y\_1<y\_2$)。

# Standard Output

每一组数据输出一行，包含一个整数，表示给定矩形中有多少个黄色地砖

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
2 3 0 0 3 3
2 3 0 0 4 4
2 3 3 3 5 5</td><td>0
7
4</td></tr></table>


# Constraints



# Note



# Source


