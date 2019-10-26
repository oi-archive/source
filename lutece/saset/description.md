
# Content

Saya defines a set consists of square numbers($\left \\{ i\mid i=x^2,x\in N \right \\}$ or $\\{0,1,4,9,16\cdots\\}$) called Saya Set(`SaSet` for short). The addition on this set is defined by Saya:

$a+0(a\in SaSet)=a$

$a+1(a\in SaSet)=min(\left \\{x\mid x>a,x\in SaSet\right \\})$

($min(S)$ here is a function which returns the minimum element in the given set $S$. For example, $min(SaSet)=0$.)

Examples:

$0+1=1$, $1+1=4$, $4+1=9\cdots$ 

$a-0(a\in SaSet)=a$

$a-1(a\in SaSet)=max(\left \\{x\mid x<a, x\in SaSet\right \\})$

($max(S)$ here is a function which returns the maximum element in the given set $S$.)

Example:

$1-1=0$, $4-1=1$, $9-1=4\cdots$ 

$a+b(a,b\in SaSet)=a+1+(b-1)$

Example:

$4+4=4+1+(4-1)=9+1=16$

# Standard Input

There is only one integer $T$($1\leq T\leq 50$) in the first line, which denotes the number of test cases.

Then T lines follows, each line will consists of two integers $a$ and $b$($0\leq a+b\leq 400$,$a,b\in SaSet$). You are asked to calculate the answer of $a+b$.

# Standard Output

For each case, output an integer, which denotes the result of $a+b$ according to the definitions above.

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
0 0
4 4</td><td>0
16</td></tr></table>


# Constraints



# Note



# Source


