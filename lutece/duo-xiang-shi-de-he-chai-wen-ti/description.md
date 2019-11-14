
# Content

任给两个多项式，求它们的和与差。本题要求用结构体数组实现。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\le 200$），表示测试数据的组数。每一组测试数据有两行，分别表示第一个和第二个多项式。每一行有多个整数，其写法为（出现两个数为$-1$表示该多项式输入结束）：

系数$1$ 次数$1$ 系数$2$ 次数$2$ …… 系数$k$ 次数$k -1$ $-1$

例如：
`2 3 4 2 -8 1 9 0 -1 -1`
表示多项式：
$2\times x^3+4\times x^2-8\times x+9$

其中，系数的范围为$[-1000,1000]$，次数的范围为$[0, 200]$。

# Standard Output

对应每组输入，输出两行，第一行是两个多项式的和，第二行是第一个多项式减去第二个多项式的差，两个多项式都应该按降幂输出。每组数据输出后应有一个空行。

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
<tr><td>2
3 1 2 2 4 0 -1 -1
3 2 3 1 2 0 -1 -1
4 4 4 2 3 3 2 1 -2 0 -1 -1
-7 5 -6 2 2 0 -2 1 -1 -1</td><td>5*x^2+6*x+6
-x^2+2

-7*x^5+4*x^4+3*x^3-2*x^2
7*x^5+4*x^4+3*x^3+10*x^2+4*x-4</td></tr></table>


# Constraints



# Note



# Source


