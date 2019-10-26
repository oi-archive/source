
# Content

沙耶定义了一个无穷级数Saya infinite series(简称`Saries`)：

$\left\\{\begin{matrix}
A\_0&=&C & (n=0)\\\\ 
A\_n&=&\left\\{\begin{matrix}
A\_{n-1}+d & (n\ mod\ 4=1)\\\\ 
A\_{n-1}\times d & (n\ mod\ 4=2)\\\\ 
A\_{n-1}-d & (n\ mod\ 4=3)\\\\ 
A\_{n-1}\div d & (n\ mod\ 4=0)
\end{matrix}\right. & (n>0)
\end{matrix}\right.$

显然，每个Saries可以用函数$S(C,d)$来描述。

例如：

$S(1,2):1,3,6,4,2,5\cdots$

$S(3,5):3,8,40,35,7,12\cdots$

沙耶基于此又定义了一种序列Saya Sequence(简称`Saquence`)：

`Saquence`是`Saries`中连续的一段序列。

`Saquence`的首项是`Saries`中下标能被$4$整除的项。

例如：

$1,3,6,4$是一个长度为$4$的`Saquence`(因为它是$S(1,2)$从下标$0$开始连续的一段序列)

$7,12,60,55,11$是一个长度为$5$的`Saquence`(因为它是$S(3,5)$从下标$4$开始连续的一段序列)

$8,40,35,7$不是一个`Saquence`(虽然它是$S(3,5)$中连续的一段，但是从$S(3,5)$的$A\_1$开始，$1$不能被$4$整除，并且也不是其他任何一个`Saris`的合法子序列)

沙耶又定义一个`Saquence`的排列为Saya Permutation(简称为`Sarmutation`)。

例如：

$6,3,1,4$是`Saquence` $1,3,6,4$的一个排列，所以$6,3,1,4$是`Sarmutation`。

$12,55,60,7,11$是`Saquence` $7,12,60,55,11$的一个排列，所以$12,55,60,7,11$是`Sarmutation`。

$1,2,3,4,5$不是任何一个`Saquence`的任何一个排列，所以$1,2,3,4,5$不是`Sarmutation`。

求一个整数序列是否为一个`Sarmutation`。

# Standard Input

第一行一个整数$t$($t\leq 100$),表示测试数据的组数。

每组测试数据两行：

第一行一个整数$n$($2\leq n\leq 1000$),表示整数序列的长度。

第二行$n$个整数，表示序列的每个元素(绝对值小于$10^9$)。

# Standard Output

每组数据输出一个串:`YES`或`NO`，表示该序列是否为`Sarmutation`。如果是输出`YES`,如果不是输出`NO`。

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
4
6 3 1 4
5
12 55 60 7 11
5
1 2 3 4 5</td><td>YES
YES
NO</td></tr></table>


# Constraints



# Note



# Source


