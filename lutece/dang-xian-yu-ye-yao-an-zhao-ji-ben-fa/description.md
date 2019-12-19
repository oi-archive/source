
# Content

众所周知zhu是一个大厨，zhu一直有自己独特的咸鱼制作技巧.

tang是一个咸鱼供应商，他告诉zhu在他那里面有$N$条咸鱼（标号从1到N）可以被用来制作.

每条咸鱼都有一个咸鱼值$K_{i}$，初始时所有$K_i$都是$0$.

zhu是一个特别的人，他有$M$个咸数（咸鱼数字）, 对于每个咸数$x$，他都会让所有满足标号是$x$倍数的咸鱼的咸鱼值异或上$1$.

zhu现在想知道经过了这$M$个咸数的筛选之后，最终有多少条的咸鱼的咸鱼值是$1$?

# Standard Input

输入的第一行包含一个整数$T$，表示有$T$组数据.

对于每组数据：

输入第一行只有两个整数$N$,$M$.

接下来一行有$M$个整数，依次对应zhu的每个咸数 $a_i$.

数据保证：

* $1 \leq T \leq 1000$

* $1 \leq N \leq 10^9$

* $1 \leq M  \leq 15$

* $1 \leq a_i \leq 2 \ast 10^5$

# Standard Output

对于每组数据，输出一行表示答案

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
<tr><td>1
10 2
5 8</td><td>3</td></tr><tr><td>2
10 1
3
10 1
1</td><td>3
10
</td></tr></table>


# Constraints



# Note

Prepared by xiper

# Source


