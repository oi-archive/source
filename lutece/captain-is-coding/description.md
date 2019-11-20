
# Content

To improve players’ coding skill, FJ collects a variety of problems and order the players to solve them. In order to ensure they can complete the task, FJ divides the problems into two collections and issues a deadline for each one. He announces that anyone who cannot complete all the problems in both two collections before the deadline will be downgraded to be an alternative member. 

Now we focus on Captain Chen. The coding skill can be qualified as an integer, which indicates the level of his coding skill. The higher the level is, the faster and the more accurately Captain Chen codes. To solve the $i\_{th}$ problem, at least $C\_i$ level of coding skill is needed. But after getting Accepted on it, Captain Chen will improve his coding skill by $D\_i$.

In each hour, Captain Chen can either try to solve one problem, or just to practice typing. If he practices typing for one hour, his coding skill will be increased by $Z$. Please notice that if he gets Accepted on the same problem twice, the second Accepted won’t benefit him anymore. What’s more, if Captain Chen decides to practice, he will keep practicing for a whole hour.

Now, he wonders if he is able to solve all the problems on time. If so, he also wonders the minimum time needed to accomplish this task.

Can you help Captain Chen?

# Standard Input

The first line of input contains a single integer $T$, indicating there are $T$ cases.

In each case, the first line contains five integers: $N$, the numbers of problems; $X$, the deadline of collection $A$; $Y$, the deadline of collection $B$; $W$, the initial level of Captain Chen; and $Z$, which was mentioned above. Next there are $N$ lines, each of which describes one problem and contains two integers $C\_i$ and $D\_i$. Following the $C\_i$ and $D\_i$, there is a character at the end of each line. The character is either `A` or `B`, indicating which collection the problem belongs to.

We guarantee that $0 < N\leq 10^3$, $0 < X,Y\leq 10^6$, $0 < Z\leq 10^3$, $0\leq W\leq 10^9$, $0\leq C\_i\leq 10^9$, $0\leq D\_i\leq 10^3$.Note that if the deadline of a collection is $X$, you can solve it in $X$ hours but not in $X+1$ hours.

# Standard Output

The output of each test case contains a single line. If Captain Chen can solve all the problems before their deadlines, the output should be the minimum time needed to complete it, measured in hour. Otherwise just output `Poor Captain Chen`

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
2 10 30 5 1
10 5 A
30 5 B
2 10 20 5 1
10 5 A
30 5 B</td><td>22
Poor Captain Chen</td></tr></table>


# Constraints



# Note



# Source


