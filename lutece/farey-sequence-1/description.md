
# Content

The Farey Sequence $F\_n$ for any integer $n$ with $n \geq 2$ is the set of irreducible rational numbers $\frac{a}{b}$ with $0 < a < b \leq n$ and $gcd(a,b) = 1$ arranged in increasing order. The first few are 

$F\_2 =$ {$\frac{1}{2}$} 

$F\_3 =$ {$\frac{1}{3}, \frac{1}{2}, \frac{2}{3}$}
 
$F\_4 =$ {$\frac{1}{4}, \frac{1}{3}, \frac{1}{2}, \frac{2}{3}, \frac{3}{4}$} 

$F\_5 =$ {$\frac{1}{5}, \frac{1}{4}, \frac{1}{3}, \frac{2}{5}, \frac{1}{2}, \frac{3}{5}, \frac{2}{3}, \frac{3}{4}, \frac{4}{5}$} 

You task is to calculate the number of terms in the Farey sequence $F\_n$.

# Standard Input

There are several test cases. Each test case has only one line, which contains a positive integer $n (2 \leq n \leq 10^6)$. There are no blank lines between cases. A line with a single $0$ terminates the input.

# Standard Output

For each test case, you should output one line, which contains $N(n)$ ---- the number of terms in the Farey sequence $F\_n$.

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
3
4
5
0</td><td>1
3
5
9</td></tr></table>


# Constraints



# Note

The answer may exceed $32$-bit integer. Please use long long int.

The data used in this problem is unofficial data prepared by YellowWall. So any mistake here does not imply mistake in the offcial judge data.

# Source


