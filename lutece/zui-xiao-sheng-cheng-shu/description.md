
# Content

坐标平面上有$n$个点，现在我们想要把这些点连成一棵有向树。但是不幸的是，树的边只能向右或者向上长。下面是一张示意图。

![title](/source/lutece/zui-xiao-sheng-cheng-shu/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTY1My8yMDE3MDUyNDE5MTkxMTU5NTguanBlZw==.jpeg)

现在我们想知道，这棵树总边长的最小值是多少。

# Standard Input

有多组测试数据，对于每一组数据:

第一行有一个数，$n$

接下来$n$行，每一行有两个数。第$i$行的两个数分别是$x_i$和$j_i$。

$0 < n \leq 10^3$

$0 \leq x_i,y_i \leq 10^4$

数据保证对于所有的$x_i \leq x_j$，有$y_i \geq y_j$。

# Standard Output

对于每一组数据，输出一个整数，表示最小的，树的总边长

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
<tr><td>5
1 5
2 4
3 3
4 2
5 1
1
10000 0</td><td>12
0</td></tr></table>


# Constraints



# Note

最小生成树?

# Source


