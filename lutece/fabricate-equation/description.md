
# Content

Given an integer $Y$, you need to find the minimal integer $K$ so that there exists a $X$ satisfying $X - Y = Z (Z \geq 0)$ and the number of different digit between $X$ and $Z$ is $K$ under decimal system.

For example: $Y = 1$, you can find a $X = 100$ so that $Z =99$ and $K$ is $3$ due to $1 \neq 0$ and $0 \neq 9$. But for minimization, we should let $X = 1$ so that $Z = 0$ and $K$ can just be $1$.

# Standard Input

Only one integer $Y (0 \leq  Y \leq 10^{18}).$

# Standard Output

The minimal $K$.

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
<tr><td>1</td><td>1</td></tr><tr><td>191</td><td>2</td></tr></table>


# Constraints



# Note



# Source


