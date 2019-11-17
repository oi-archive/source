
# Content

An exam will begin in ten minutes, and bearchild is very, very angry, he finds many students are not sit in the right place!

Before talking anything, we will have a deep look at the classroom. The classroom has $n$ rows of desks with n ones in each row. And there are exactly $n\times n$ students, one for a desk. Bearchild has already set positions for each student, but they underestimated his ability – They think they can find a way to cheat under bear’s eyes! What a young, simple and naive idea!

So they are forces to move back to their own positions. As the classroom is narrow, they can only move horizontally or vertically, but they can move at the same time without collision. A student needs one step to move for one row, or one column further. Suppose all the students choose the shortest road. They get unhappy when walking, the unhappiness of a student can be valued by the **square of the steps** he walks, i.e. $step\times step$.

Bearchild wonders, if at first the students chose their positions randomly, what is the expected **sum of unhappiness of all the students**?

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases. ($T\leq 10,000$)

For each case, there are a single number $n$. ($1\leq n\leq 100,000,000$)

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). If the answer is not a integer, output `not integer`, otherwise output the answer, mod $1000000007$.

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
1
2
3
4</td><td>Case #1: 0
Case #2: 6
Case #3: not integer
Case #4: 130</td></tr></table>


# Constraints



# Note



# Source


