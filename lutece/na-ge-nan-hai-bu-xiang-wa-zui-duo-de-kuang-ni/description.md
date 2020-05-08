
# Content

矿里有家的 whfym 家后院整整齐齐摆放着 $n\times m$ 个矿坑，这些矿坑恰好 $n$ 行 $m$ 列，同时每个矿坑都有一个开采系数 $a_{ij}$。这天 whfym 闲来无聊打算略微开采一下自家的矿，他会先选定一个起始点来安装采矿机，并且以起始点为中心以一个平行坐标轴的正方形向四周开采。由于机器专为起始点设计，只有当矿坑的开采系数是起始点开采系数的倍数时，这一矿坑才能被开采。又由于 whfym 有轻微强迫症，他不想让开采的正方形区域中有不能开采的矿坑，他想知道他这次最多能开采多少个矿坑？有多少合适的起始点？

# Standard Input

第一行两个正整数 $n,m$，意义如上所示。
接下来 $n$ 行每行 $m$ 个整数，第 $i$ 行第 $j$ 个整数代表 $i$ 行 $j$ 列的矿坑的开采系数 $a_{ij}$。

# Standard Output

第一行输出一个整数代表一次能够开采矿坑的最大数目。
第二行输出一个整数代表合适起始点的个数。

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
<tr><td>5 5
4 6 2 4 7 
2 2 4 3 8 
6 8 2 4 1 
1 5 4 1 9 
6 7 7 4 2 </td><td>9
2</td></tr></table>


# Constraints

$1\le n,m \le 500,1\le a_{ij}\le 10^9$

# Note

对于样例，合适的起始点为第 $2$ 行第 $2$ 列及第 $4$ 行第 $4$ 列两个点，以这两个点为中心的 $3\times 3$ 正方形中所有数字都是起始点数字的倍数，所以一次可开采的最大矿坑数为 $9$。

本题做法很多,欢迎不喜欢写数据结构的同学思考其他做法。

# Source


