
# Content

吴神对于数的研究已经达到登峰造极的境界了，一般的数论问题都是直接秒杀！最近他自己定义了一种吴神数，吴神数N满足三个条件：
1. 本身为无平方因子数（无平方因子数即对于任意一个素数$p$，$p^2$都不会整除那个数，如$1$ , $5=5$ , $15=3\times 5$都是无平方因子数，而$20=2^2\times 5$不是)。
2. 含有$3$个或$3$个以上的素因子。
3. 对于每个素因子 $p$ ，满足 $(N-1)\ mod\ (p-1)=0$;

比如 $561=3\times 11\times 17$ 即为一个吴神数。

给定一个区间$[A,B]$，$1\leq A\leq B<2^{31}$ ,$B-A<10^6$ ，求此区间吴神数的个数。

# Standard Input

第一行有个整数$T$，代表数据组数 ($T\leq 15$)

每组数据包含$2$个整数，$A$，$B$。

# Standard Output

对于每组数据，输出区间$[A,B]$内吴神数的个数

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
10 2000
20000 21000</td><td>3
0</td></tr></table>


# Constraints



# Note



# Source


