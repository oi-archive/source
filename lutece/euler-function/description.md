
# Content

Given $m$ and $n$, please calculate the following expression.

$\displaystyle{\sum_{k=m}^{n} \lfloor\frac{n}{k}\rfloor euler[k]}$

**where $ \lfloor x \rfloor $ is the maximum integer that is less than or equal to $x$.**

   * $euler[k]$ is defined as the number of $x$ in $[1,k]$, satisfying $gcd(x,k)=1$.
   * $gcd(x,k)$ is the greatest common divisor of $x$ and  $k$.

If you know nothing about euler function, you can visit the following link to learn some useful information.

http://en.wikipedia.org/wiki/Euler%27s_totient_function

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases. $(T \leq 500)$

For each case, the first line contains two integers $m$ and $n$. $(1 \leq m \leq n \leq 10^9, 1 \leq m \leq 10^6)$

# Standard Output

For each case, output the answer in one line.

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
2 2
2 3
</td><td>1
3
</td></tr></table>


# Constraints



# Note

Because the answer is so large, please use long long instead of int. Correspondingly, please use `%lld` instead of `%d` to scanf and printf.

# Source


