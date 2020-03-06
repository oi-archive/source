
# Content

我们给出一个奇怪的公式：$f(a)=\sum_{i=1}^{n}\sum_{j=1}^{n} \min(a_i,a_j)$

其中$\min(x,y)$ 表示$x,y$中的较小值。如果你对求和符号不太熟悉，我们也可以写成程序语言的形式：
```
int f = 0;
  for (int i = 1; i <= n; ++i)
    for ( int j = 1; j <= n ; ++j)
      f = f + min (a[i], a[j]);
```
注意到这里$a$是一个数组，下标从$1$到$n$，我们要求$a$数组满足以下条件：
1. $a$中所有元素都是正整数。
2. $a$中所有元素互不相同。

给定$n$和$f(a)$的值，请构造出合法的$a$数组，如果有多个$a$数组满足条件，输出字典序最小的答案。关于字典序的进一步说明请看Hint。

如果满足条件的数组不存在，输出$-1$。

# Standard Input

第一行是一个数$T$（$T\leq 100$），表示测试数据的组数。

每组测试数据包括一行，两个数$n$和$F$，代表数列元素个数以及$f(a)$的值。($1\leq n\leq 100, 1\leq F\leq 10^9$)

# Standard Output

对于每一组测试数据，输出一行。

如果有解，输出$n$个数，数之间用空格隔开，否则输出$-1$。

行末不允许有多余的空格，最后一个元素（如果有解）后面没有空格。

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
2 10
2 2</td><td>1 7
-1</td></tr></table>


# Constraints



# Note

对于两个长度均为$N$，下标从$1$到$N$的数组$A$和$B$，我们称$A$的字典序严格小于$B$，当且仅当存在下标$X\leq N$，使得对于所有$1\leq i < x$，均有$A_i$和$B_i$相等，同时满足$A_x < B_x$。

例如，长度为$4$的数组$A= [1,2,3,4]$ 的字典序小于数组$B=[1,2,4,3]$，因为存在下标$3$，有 $A_3 < B_3$, 而且$A_1=B_1, A_2=B_2$。

# Source


