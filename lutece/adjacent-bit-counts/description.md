
# Content

For a string of n bits $x\_1, x\_2, x\_3, \cdots , x\_n$, the adjacent bit count of the string $\rm AdjBC(x)$ is given by

$$x\_1\times x\_2 + x\_2\times x\_3 + x\_3\times x\_4 + \cdots + x\_{n-1}\times x\_n$$

which counts the number of times a $1$ bit is adjacent to another $1$ bit. For example:
1. $\rm AdjBC(011101101) = 3$
2. $\rm AdjBC(111101101) = 4$
3. $\rm AdjBC(010101010) = 0$

Write a program which takes as input integers $n$ and $k$ and returns the number of bit strings $x$ of $n$ bits (out of $2n$) that satisfy $\rm AdjBC(x) = k$. For example, for $5$ bit strings, there are $6$ ways of getting $\rm AdjBC(x) = 2$: `11100`, `01110`, `00111`, `10111`, `11101`, `11011`

# Standard Input

The first line of input contains a single integer $P$, ($1\leq P\leq 1000$), which is the number of data sets that follow. Each data set is a single line that contains the data set number, followed by a space, followed by a decimal integer giving the number ($n$) of bits in the bit strings, followed by a single space, followed by a decimal integer ($k$) giving the desired adjacent bit count. The number of bits ($n$) will not be greater than $100$ and the parameters $n$ and $k$ will be chosen so that the result will fit in a signed $32$-bit integer.

# Standard Output

For each data set there is one line of output. It contains the data set number followed by a single space, followed by the number of $n$-bit strings with adjacent bit count equal to $k$.

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
<tr><td>10
1 5 2
2 20 8
3 30 17
4 40 24
5 50 37
6 60 52
7 70 59
8 80 73
9 90 84
10 100 90</td><td>1 6
2 63426
3 1861225
4 168212501
5 44874764
6 160916
7 22937308
8 99167
9 15476
10 23076518</td></tr></table>


# Constraints



# Note



# Source


