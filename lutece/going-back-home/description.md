
# Content

Finally, finally this semester is over. QiQi plans to go back home.

QiQi lives in a world consist of n cities. He is currently at city S for school and about to go to city D where his home is. QiQi’s world is a little bit different from ours. In his world, one-way road collect two cities and each road is associated with a string. The time QiQi need to travel that road is the length of that string. QiQi doesn’t want to get back home too late because he missed his family so much, but not too early because he really enjoys the scenery along his trip. So he decided to go back home during the period $T\_1$ to $T\_2$.(both inclusive). As QiQi is not good at routing, he asks you to help him to come up with a perfect plan for him. You may wonder what perfect means? Because he’s too shy to say it, he lets me tell you that a perfect plan is a route that the strings along this route form a lexicographically smallest one among all legal routes, but it may not be the shortest one.

![title](/source/lutece/going-back-home/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzY2LzIwMTQwNDExMTQxMDU0Njg5MzQucG5n.png)

# Standard Input

The first line of the input is an integer $T$ ($T\leq 30$), which stands for the number of test cases you need to solve.

Every test case begins with six integers $N$, $M$, $S$, $D$, $T\_1$, $T\_2$ ($2\leq N\leq 50$, $1\leq M\leq 200$, $0\leq S, D < N$, $S\neq D$ , $0\leq T\_1\leq T\_2\leq 2000$), where $N$ is the number of cities, $M$ is the number of edges. $S$ is the city which QiQi is present in, $D$ is the city QiQi tries to reach. $T\_1$, $T\_2$ are the earliest and the latest time QiQi wants to reach his destination.

Then $M$ lines follow. Each line contains two integers $u$, $v$ and a string $s$ which is at most $6$ letters long(only lowercase latin letters). Means that there is a direct road from $u$ to $v$ associated with string $s$.($0\leq u, v < N$).

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and starts at $1$. Then if it’s impossible to reach city $D$ during the period $T\_1$ to $T\_2$ (both inclusive), output `Impossible`, otherwise output the route. See sample for more details.

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

4 4 0 3 4 4
0 1 abc
0 2 aaaa
1 3 d
2 3 d

2 1 0 1 1 4
0 1 abcde</td><td>Case #1: abcd
Case #2: Impossible</td></tr></table>


# Constraints



# Note



# Source


