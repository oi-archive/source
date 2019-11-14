
# Content

Kufeng has bought a big park with $n$ interesting places. He offered all members in UESTC ACM-ICPC team a free visit to the park. 

However, Kufeng has set some special plans for visit, each plan corresponds to a subset of places the visitor can visit. There are $m$ plans in total.

Each team member should choose a plan offered by Kufeng before getting into the park, and only visit those places that are allowed to visit by the plan. Different members might choose the same plan.

There are $p$ members in the team. We are interested to know, how many ways are there for choosing plans, such that each place in the park is visited by at least a member in the team?

Two ways for choosing plans are considered different, if at least one member in the team chooses different visit plans in those two ways.

# Standard Input

The first line of input contains three numbers $n$, $m$ and $p$ ($1\leq n\leq 20, 1\leq m, p\leq 10^5$), they are the number of places in the park, the number of visiting plans, and the number of members in the team.

The following m blocks each with two lines, describing the visiting plans. The first lines come with a number $k$, the number of places this plan can visit. The second line come with $k$ numbers $x_1, x_2, \cdots, x_k$ ($1\leq x_i\leq n$ and all the $x_i$ are different), the id of each place.

# Standard Output

Output the number of ways, in which each member choose a visit plan, that make sure that each place are visited by at least one member? 

Since the number might be large, just output the number module $1000000007(10 ^ 9 + 7)$.

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
<tr><td>4 4 2
2
1 2
3
1 2 3
3
1 3 4
3
2 3 4</td><td>10</td></tr></table>


# Constraints



# Note

Here `module` means `%` operator in both C++ and Java.

There are $10$ ways to choose the plan in example, they are $(1,3), (1,4), (2,3), (2,4), (3,1), (3,2), (3,4), (4,1), (4,2), (4,3)$.

# Source


