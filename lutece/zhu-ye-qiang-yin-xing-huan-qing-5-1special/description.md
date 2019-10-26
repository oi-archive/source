
# Content

柱爷抢银行的手段日益熟练。为了欢庆5.1，柱爷准备再花式抢一波银行。

![title](/source/lutece/zhu-ye-qiang-yin-xing-huan-qing-5-1special/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTM1Ni8yMDE2MDQyMjE0MTkzNjU2NzE1LmpwZw==.jpg)

喵哈哈城是一个大的矩形方阵，而这方阵是由$N*M$个矩形方格组成，方阵中的每个格子都有一家银行，柱爷抢这家银行能得到$a\_{ij}$的钱，当$a\_{ij}<0$柱爷会损失$-a\_{ij}$的钱。

柱爷最近练成了飞天螺旋大草，所以他决定要抢的银行要形成$k$阶顺时针螺旋状，其中$k为\geq 3$的**任意**奇数。下面是$k=3,5,7$的图形，其中黑色方块是柱爷要抢钱的银行。

![title](/source/lutece/zhu-ye-qiang-yin-xing-huan-qing-5-1special/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTM1Ni8yMDE2MDQyMjE0MjEzMTg3OTE3LnBuZw==.png)

请问柱爷最多能抢多少钱?

# Standard Input

第一行两个数$N,M$。

之后$N$行每行$M$个数，表示$a\_{ij}$。

数据保证：

* $3\leq N,M\leq 500$。

* $-1000\leq a_{ij}\leq 1000$。

# Standard Output

输出一行一个数，即答案。

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
<tr><td>6 5
0 0 0 0 0
1 1 1 1 1
0 0 0 0 1
1 1 1 0 1
1 0 0 0 1
1 1 1 1 1</td><td>17</td></tr><tr><td>3 3
1 1 1
1 0 0
1 1 1</td><td>6</td></tr><tr><td>6 6
-3 2 0 1 5 -1
4 -1 2 -3 0 1
-5 1 2 4 1 -2
0 -2 1 3 -1 2
3 1 4 -3 -2 0
-1 2 -1 3 1 2</td><td>13</td></tr></table>


# Constraints



# Note

**请注意柱爷不是临阵退缩的人，既然来了，就至少要选择一个格子！(尽管可能会亏钱)**

# Source


