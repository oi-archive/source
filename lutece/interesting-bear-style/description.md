
# Content

Bearchild finishes his buildings! (You can see Problem C for more details, but believe me, it has no much help for solving this problem!) 

Watching from far away, bearchild finds his n buildings are built in a row. To his surprise,those n buildings all have different heights, from $1$ to $n$. Bearchild is very happy about that, and starts to think more. He wants to find some `Bear-Style` buildings.

A building is `Bear-Style` when it has neighboring buildings at left and right, and is higher or lower than both of the neighbors.
For example, if there are $5$ buildings with heights `1 5 2 3 4`, then the second and the third buildings are `Bear-Style`, but the fourth building is not.

Bearchild is just a big silly bear, so he can only count out the number of `Bear-Style` buildings. But `Silly Bears Have Nice Ideas`, he thinks out a new question: if he can change those buildings’ positions arbitrarily for infinite times, how many of the results, including the original one, will have exactly $K$ `Bear-Style` buildings?

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases. ($T\leq 10000$)

For each case, there are two integers $n$ and $K$, ($1\leq n\leq 1000$, and $K\geq 0$)

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then output the answer for bearchild’s question, mod $1000000007$

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
3 1
4 2
5 4</td><td>Case #1: 4
Case #2: 10
Case #3: 0</td></tr></table>


# Constraints



# Note



# Source


