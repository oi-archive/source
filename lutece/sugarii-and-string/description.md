
# Content

![pic](/source/lutece/sugarii-and-string/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMTEvMjMvUE4xUXRWcVk2UjdUZTR1LmpwZw==.jpg)

Sugarii is very good at solving string problems. One day, a string $S$ suddenly comes to his mind. It is a string with $n$ digits and consists of only $0$ and $1$. Then he figures out a way to make it longer with the following steps:  

1. Copy $S$ to a new string $T$.
2. Reverse every digit in $T$. That is, for every digit in $T$, if it's $0$, change it to $1$; if it's $1$, change it to $0$.
3. Append $T$ to the end of $S$.
4. Go back to step 1.  

For example, if $S$ is initially $110$, then it becomes $110001$, and then $110001001110$, and then $110001001110001110110001$... The final string can be as long as you want. Sugarii wants to know whether the $k$-th digit of the final string is $0$ or $1$.

# Standard Input

The first line contains two integers $n$ and $k$ ($1 \le n \le 10^5$, $1 \le k \le {10}^{18}$) — the length of string $S$ and the digit Sugarii wants to know.

The second line contains a string $S$, consisting of $0$ and $1$.

# Standard Output

Print the $k$-th digit of the final string ($0$ or $1$).

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
<tr><td>3 5
110
</td><td>0</td></tr><tr><td>1 10
1
</td><td>1</td></tr></table>


# Constraints



# Note

In the fisrt sample, the final string is $110001001110001110110001$... , the 5th digit is $0$.

In the second sample, the final string is $1001011001101001$... , the 10th digit is $1$.

# Source


