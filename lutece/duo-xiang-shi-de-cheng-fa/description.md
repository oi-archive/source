
# Content

任给两个多项式，求它们的乘积。本题要求用链表实现。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\le 200$），表示测试数据的组数。每一组测试数据有两行，分别表示第一个和第二个多项式，每一行有多个整数，其写法为（出现两个数为$-1$表示该多项式输入结束）：

系数$1$ 次数$1$ 系数$2$ 次数$2$ …… 系数$k$ 次数$k -1$ $-1$

例如：
`2 3 4 2 -8 1 9 0 -1 -1`
表示多项式：
$2\times x^3+4\times x^2-8\times x+9$

其中，系数的范围为$[-1000,1000]$，次数的范围为$[0，100]$。

# Standard Output

对应每组输入，输出多项式的积，要求按降幂输出，占一行。

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
3 1 2 2 4 0 -1 -1
3 2 3 1 2 0 -1 -1
4 4 4 2 3 3 2 1 -2 0 -1 -1
-7 5 -6 2 2 0 -2 1 -1 -1
3 3 6 0 -1 -1
-7 0 -1 -1</td><td>6*x^4+15*x^3+25*x^2+18*x+8
-28*x^9-21*x^8-28*x^7-38*x^6-12*x^5-22*x^4-14*x^3+16*x^2+8*x-4
-21*x^3-42</td></tr></table>


# Constraints



# Note



# Source


