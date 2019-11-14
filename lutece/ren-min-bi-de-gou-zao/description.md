
# Content

我们都知道人民币的面值是$1、2、5、10$，为什么是这个数值呢，我们分析了下发现，从$1-10$的每个数字都可以由每种面值选出至多一张通过加法和减法（找钱）来构成，（比如：$1+2=3，5-1=4，5+1=6，5+2=7，1+2+5=8，10-1=9$）

但是实际上，我们只需要$1、2、7$三种面值就可以组成$1-10$的每一个数字了

（$1+2=3，7-1-2=4，7-2=5，7-1=6，7+1=8，7+2=9，7+1+2=10$）

那么现在问题来了，给一个数$n$，请问最少需要多少种不同的面值就可以构成从$1-n$的所有数字，注意在构成每一个数字时同种面值不能超过$1$张。

# Standard Input

一个数字$n$（1<=$n$<=100000）

# Standard Output

一个数字，代表最少需要多少种不同的面值可以构成从$1-n$的所有数字。

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
<tr><td>10</td><td>3</td></tr></table>


# Constraints



# Note



# Source


