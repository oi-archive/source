
# Content

小E听说牛大爷从CTR那得到一块蛋糕，蛋糕糕形状是由n个节点组成的不规则多边形，保证多边形内任意一点都可以经由多边形内部的相邻点互相到达，多边形边上的点可以经由多边形边上相邻的点互相到达，多边形边上任意相邻的顶点p1(x1,y1)和p2(x2,y2)均保证:x1==x2 或者 y1==y2。现在小E非常想吃那块蛋糕，但牛大爷只允许小E获得以s(xs,ys)和t(xt,yt)为对角点的矩形内的蛋糕，由于小E是一口吃类型，所以他想知道，在牛大爷划分区域内，他最多可以吃多少口（每口蛋糕不允许有相邻公共边，允许顶点重合）。如下图：

![image](/source/lutece/xiao-eyi-kou-chi/img/aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL2VtZW5nZGVhdGgvbWFya2Rvd25waG90by9tYXN0ZXIvMTIzLnBuZw==.png)

黑色区域代表蛋糕，红色代表可吃区域，则小E最多可以吃2口。

# Standard Input

第一行：4个整数x1,y1,x2,y2（x1<x2,y2<y1），表示牛大爷划分的区域。
第二行：1个整数n（4<=n<=200）表示蛋糕的顶点数
接下来n行描述蛋糕的顶点坐标（保证，顶点按照同一时针方向连续给定）
所有点（蛋糕顶点和牛大爷划分区域的顶点）的坐标均为非负整数，且不超过15000

# Standard Output

一行：1个整数表示小E能吃的最大口数

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
<tr><td>5 7 16 3
16
0 0
18 0
18 6
16 6
16 1
10 1
10 4
7 4
7 2
2 2
2 6
12 6
12 12
10 12
10 8
0 8</td><td>2</td></tr></table>


# Constraints



# Note

提示：该样例就是上面的那幅图。

题外話：大家可以假设CTRsb，数据非常水（CTR只出到了200以内的，其实标程是n=15000的数据可以轻松跑过，那就算是div1送道sb题给大家娱乐了）

# Source


