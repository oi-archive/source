
# Content

A Mountain number is defined as continuous digits {$D\_0, D\_1\cdots D\_{n-1}$} ($D\_0 > 0$ and $n \geq 3$),which exist $D\_m$ ($0 < m < n - 1$) satisfied $D\_{i-1} < D\_i$ ($0 < i\leq m$) and $D\_i > D\_{i+1}$ ($m\leq i < n - 1$).Such as $121$, $12341$ and so on.

Now,BlinKer is facing a problem.He wants to calculate the number of mountain numbers in the closed interva $[A,B]$. Could you help him?

# Standard Input

First line is a integer $T$ ,which means the number of test cases.

Each case has two integers $A,B$ ($0\leq A\leq B<2^{63}$) in a single line.

# Standard Output

For each case,first output `Case #x: `($x$ start from $1$),then output a single num which is the answer.

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
<tr><td>3
121 121
100 101
12341 12344</td><td>Case #1: 1
Case #2: 0
Case #3: 3</td></tr></table>


# Constraints



# Note



# Source


