
# Content

四元数是由实数加上三个元素i,j,k组成，而且它们有如下的关系：

$i^2=j^2=k^2=-1$

$i \times  j=-j\times   i=k$

$j\times k=-k\times j=i$

$k\times i=-i\times k=j$

显然，四元数不满足交换律。现在给你一个长度为$N$的四元数乘法表达式(只包含$i,j,k$)，为了使它的结果等于$1$，你可以选取表达式中的任意两个数进行交换，但交换次数不能大于$M$次。

若可能使结果为$1$，输出交换的最少步数。

否则，输出$-1$。

# Standard Input

第一行包含两个数$N(1<=N<=1000), M(0<=M<=1000),$ 和一个长度为$N$的字符串表示表达式，保证表达式只包含i,j,k。

# Standard Output

对于每组数据，若有解，输出最少交换次数；否则输出-1。

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
<tr><td>3 2 ijk
</td><td>1</td></tr><tr><td>3 1000 iij</td><td>-1</td></tr></table>


# Constraints



# Note

第一组样例：若不进行交换，$i\times j\times k=((i \times j)\times k)=(k\times k)=-1$，显然不合法。

最优的一种策略是，只交换i与k，表达式变为$k\times j\times i=((k\times j)\times i)=(-i\times i)=1$。

第二组样例：不管怎么交换，结果都不可能为$1$。

# Source


