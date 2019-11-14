
# Content

给你$N$个限制条件$Limit[i]$，表示第$i$个数的取值范围在$[0,Limit[i]]$内，现在柱爷想知道有多少种取值方法能使这些数异或起来等于$K$

当然柱爷早就知道了答案，柱爷现在想问你知道吗

# Standard Input

输入第一行有两个整数$N$和$K$.$( 1 \leq N \leq 10^5 , 0 \leq K \leq 10^9 )$

第二行有$N$个整数，表示$Limit[i]$.$( 0 \leq Limit[i] \leq 10^9 )$

# Standard Output

输出一行表示答案对$10^9+7$取模后的值

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
<tr><td>3 0
1 2 3</td><td>6
</td></tr></table>


# Constraints



# Note

柱爷：你能很轻易的设计出复杂度为$O(\prod_{i=1}^n(Limit[i]+1))$的算法

# Source


