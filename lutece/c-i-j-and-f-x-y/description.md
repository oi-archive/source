
# Content

There are tow function, $C$ and $F$;
````
Fuction C(i,j)=[j*(j-1)*(j-2)*....*(j-i+1)]/[1*2*3....*i].
Fuction F(x,y)can be caculator by following code
int F(long long x,long long y)
{
    int tot=0;
    while(x%y==0)
    {
       tot++;
       x=x/y;
    }
    return tot;
}
````
Please find out answer of following function:

$max((F(C(1,m), t),  F(C(2,m), t),F(C(3,m), t),\cdots,F(C(m-1,m), t),F(C(m,m),t))$

Since the answer could be very large. you just need to find $n$,that $F(C(n,m),t)$ is the largest one.

# Standard Input

tow nunmber $t，m(0 < t \leq m \leq 1000000000)$

It is guranteed that $t$ is a prime number, and $m$ can be divided by $t$ with no remainder.

# Standard Output

One number $n$, (If there are mutiple solution, just output the larget one)

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
<tr><td>3 6</td><td>5</td></tr><tr><td>37 62123</td><td>50652</td></tr></table>


# Constraints



# Note



# Source


