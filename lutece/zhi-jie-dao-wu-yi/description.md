
# Content

五一？你还想放假？你搞我的吧，亲。回来训练吧，乖，你跑不掉的哟...... 

于是又到一天集训时，为了让大家更加熟悉位运算，beap首先在黑板上写下$n$个整数数字:$x\_1,x\_2\cdots x\_n$，

接下来beap进行了$m$次操作，每次操作满足下述两种情况之一：
1. `C i j`表示beap把数字$x\_i$改写成$j$。
2. `Q i j`表示beap询问$x\_i$^$x\_{i+1}$^$\cdots$^$x\_j$的值是多少（其中^表示XOR，也就是异或运算）

作为一个优秀的acmer，beap知道你一定能正确回答他提出的每一个问题。

# Standard Input

单组测试数据

第一行是两个整数$n,m$($0 < n,m \leq 500000$)。

接下来的一行，有$n$个数字，第$i$个数字表示整数$x\_i$($0 < x\_i < 2^{31}$)的初始值

接下来的$m$行，每行是两种操作之一，格式如上文所述。

对于`C i j`，满足$0 < i \leq n$, $0 < j < 2^{31}$

对于`Q i j`，满足$0 < i \leq j \leq n$

# Standard Output

对于每个询问，输出相应的答案。

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
<tr><td>5 6
5 3 4 9 2 
Q 1 1
Q 1 5
C 1 6
Q 1 1
Q 1 5
Q 2 3</td><td>5
9
6
10
7</td></tr></table>


# Constraints



# Note



# Source


