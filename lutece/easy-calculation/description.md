
# Content

KO is a Taobao engineer at infrastructure team. He likes thinking, especially about math and algorithm problem. One day a math puzzle comes to his mind.

Let’s define an equation as follow:

$$f\_{1,j} = j, j \geq 1$$
$$f\_{i,1} = 1, i \geq 1$$
$$f\_{i,j} = f\_{i,j-1}\times f\_{i-1,j}, i > 1 and j > 1$$

Given two integers $n$, $m$, how to calculate the value of $f\_{n,m}$ mod $10^9$?

# Standard Input

The first line of the input is an integer $T$ ($T\leq 1000$), which stands for the number of test cases you need to solve.

Every test case are two integers $n$, $m$ ($1\leq n, m\leq 10^9$).

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then the answer $f\_{n,m}\rm\ mod\ 10^9$. See sample for more details.

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
<tr><td>4
1 2
2 2
2 3
3 3</td><td>Case #1: 2
Case #2: 2
Case #3: 6
Case #4: 12</td></tr></table>


# Constraints



# Note



# Source


