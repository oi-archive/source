
# Content

Bear has a large, empty ground for him to build a home. He decides to build a row of houses, one after another, say $n$ in total.

The houses are designed with different height. Bear has $m$ workers in total, and the workers must work side by side. So at a time bear can choose some continuous houses, no more than $m$, and add their heights by one, this takes one day to finish.

Given the designed height for each house, what is the minimum number of days after which all the houses’ heights are no less than the original design?

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases. ($T\leq 50$)

For each case, the first line contains two integers $n$ and $m$: the number of houses and the number of workers. The next line comes with $n$ non-negative numbers, they are the heights of the houses from left to right. ($1\leq n, m\leq 100,000$, each number will be less than $1,000,000,000$)

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then output the days when bear’s home can be built.

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
3 3
1 2 3
3 3
3 2 1</td><td>Case #1: 3
Case #2: 3</td></tr></table>


# Constraints



# Note



# Source


