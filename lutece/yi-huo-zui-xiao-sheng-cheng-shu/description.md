
# Content

给出n个点，其标号分别为0到n-1，任意两个点之间都有一条边相连，边的权值是这两个点的标号的异或。
问这样的一个图的最小生成树的边权和为多少。

# Standard Input

一个整数n (1<= n <= 10^12 ) ( 注意要使用 long long 类型来存储)

# Standard Output

最小生成树的边权和

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
<tr><td>4</td><td>4</td></tr></table>


# Constraints



# Note

样例解释
连接 (0,1) ,( 1,3 ) ( 3, 2)这三条边，其边权分别为 1  , 2 , 1 可以得到最小生成树的边权和为 4

# Source


