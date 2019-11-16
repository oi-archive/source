
# Content

If you have ever learned $\\underline{Z \, Algorithm}$, you may know that for a string $S$, $\\underline{Z \, Algorithm}$ can gain an integer array $Z$, which $Z_i$ indicates the LCP(longest-common-prefix) between $S_{[i:n)}$ and $S_{[0:n)}$. 

Besides, we explicitly define $Z_0 = 0$ as exception.

Now consider all the strings as set $\Re$ with the length $N$ and the charset size $M$, calculate
$\sum_{S \in \Re} \max(Z_0,Z_1,...,Z_{n-1})^2 \mod 10^9 + 7$

# Standard Input

Only one line contains two integers $N$ $( 1 \leq N \leq 100 )$ and $M$ $( 1 \leq M \leq 666666666 )$.

# Standard Output

Print the corresponding answer in a single line.

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
<tr><td>1 772002</td><td>0</td></tr><tr><td>2 772002</td><td>772002</td></tr><tr><td>3 772002</td><td>975711675</td></tr></table>


# Constraints



# Note



# Source


