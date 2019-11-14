
# Content

沙耶定义了一个无穷级数Saya infinite series(简称`Saries`)

显然，每个`Saries`可以用函数$S(C,d)$来描述。

$\left\\{\begin{matrix}
A\_0&=&C & (n=0)\\\\ 
A\_n&=&\left\\{\begin{matrix}
A\_{n-1}+d & (n\ mod\ 4=1)\\\\ 
A\_{n-1}\times d & (n\ mod\ 4=2)\\\\ 
A\_{n-1}-d & (n\ mod\ 4=3)\\\\ 
A\_{n-1}\div d & (n\ mod\ 4=0)
\end{matrix}\right. & (n>0)
\end{matrix}\right.$

例如：

$S(1,2):1,3,6,4,2,4\cdots$

$S(3,5):3,8,40,35,7,12\cdots$

问数$X$是否在$S(c,d)$中出现过，如果出现了，求该数最早出现的位置（第一个数记为位置$0$）。

# Standard Input

第一行一个整数$t$($t\leq 200$),表示测试数据的组数。

每组测试数据一行：三个整数$C,d,X$($1\leq C,d,X\leq 10^8$)。

# Standard Output

每组数据输出一个数，如果该数出现过则是该数最早出现的位置，否则输出$-1$

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
1 2 1
1 2 3
3 5 1</td><td>0
1
-1</td></tr></table>


# Constraints



# Note



# Source


