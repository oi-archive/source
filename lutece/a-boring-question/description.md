
# Content

There are an equation.

$\sum\_{0\leq k\_{1},k\_{2},\cdots k\_{m} \leq n} \prod\_{1\leqslant j <m}\binom{k\_{j+1}}{k\_{j}} \% 1000000007=?$

We define that $\binom{k\_{j+1}}{k\_{j}}=\frac{k\_{j+1}!}{k\_{j}!\left ( k\_{j+1}-k\_{j} \right )!}$ . And $\binom{k\_{j+1}}{k\_{j}}=0$ while $k\_{j+1}<k\_{j}$.

You have to get the answer for each $n$ and $m$ that given to you.

For example,if $n=1$,$m=3$,

When $k\_{1}=0,k\_{2} = 0,k\_{3} = 0,\binom{k\_{2}}{k\_{1}}\binom{k\_{3}}{k\_{2}}=1$;

When$k\_{1}=0,k\_{2} = 1,k\_{3} = 0,\binom{k\_{2}}{k\_{1}}\binom{k\_{3}}{k\_{2}}=0$;

When$k\_{1}=1,k\_{2} = 0,k\_{3} = 0,\binom{k\_{2}}{k\_{1}}\binom{k\_{3}}{k\_{2}}=0$;

When$k\_{1}=1,k\_{2} = 1,k\_{3} = 0,\binom{k\_{2}}{k\_{1}}\binom{k\_{3}}{k\_{2}}=0$;

When$k\_{1}=0,k\_{2} = 0,k\_{3} = 1,\binom{k\_{2}}{k\_{1}}\binom{k\_{3}}{k\_{2}}=1$;

When$k\_{1}=0,k\_{2} = 1,k\_{3} = 1,\binom{k\_{2}}{k\_{1}}\binom{k\_{3}}{k\_{2}}=1$;

When$k\_{1}=1,k\_{2} = 0,k\_{3} = 1,\binom{k\_{2}}{k\_{1}}\binom{k\_{3}}{k\_{2}}=0$;

When$k\_{1}=1,k\_{2} = 1,k\_{3} = 1,\binom{k\_{2}}{k\_{1}}\binom{k\_{3}}{k\_{2}}=1$.

So the answer is 4.

# Standard Input

The first line of the input contains the only integer $T$,$(1\le T\le 10000)$
Then $T$ lines follow,the i-th line contains two integers $n$,$m$,$(0\le n\le 10^9,2\le m\le 10^9)$

# Standard Output

For each $n$ and $m$,output the answer in a single line.

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
1 2
2 3
</td><td>3
13</td></tr></table>


# Constraints



# Note



# Source


