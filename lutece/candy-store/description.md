
# Content

Little Anne loves candy and she wants to buy candy at the local candy store. Fortunately, she also happens to be extremely rich, which enables her to buy all the candy she could ever want. She wants to buy candy for at least $C$ kroner, and she also wants to buy at most one of each type.

There are many ways to buy candy for at least $C$ kroner,so she wants to consider the possibilities before buying.Since her parents think she is too young to use a computer,she has asked you to write a program that calculates the number of possibilities.

Anne doesn't like large numbers like $1,000,000,007$, so you instead calculate the number of possibilities modulo $65537$, a less intimidating number.

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. Each test case begins with a line containing two integers $N$ and $C$, the number of available candy types and the least amount of money Anne wants to spend. The next line contains $N$ space-separated integers $a\_i$, the cost of candy type $i$ in kroner.

# Standard Output

For each test case, output on its own line the number of ways Anne can buy candy for at least $C$ kroner, modulo $65537$.

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
5 10
5 6 7 8 9
10 100
10 10 10 10 10 10 10 10 11 9</td><td>26
1</td></tr></table>


# Constraints



# Note

$0 < T \leq 100$

$0 < N \leq 200$

$0 < C \leq 10000$

$0 < a\_i \leq 200$

# Source


