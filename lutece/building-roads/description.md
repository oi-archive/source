
# Content

After the war between Country $X$ and Country $Y$, all the roads in Country $X$ have been destroyed. Qiqi, the king of Country $X$ wants to build some roads to connect all cities (it means that starting from every city, we can go to any other cities through roads Qiqi built) as soon as possible. 

Every road takes one day to build and every day Qiqi can build only one road. Building the road between city $i$ and city $j$ costs $|p\_i - p\_j|$ units money, where $p\_i$ and $p\_j$ are the population of city $i$ and city $j$. What is the maximum and minimum cost if Qiqi wants to connect all cities in the shortest time?

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T \leq 50$) indicating the number of test cases.

For each test case there is an integer $N$ ($1 \leq N \leq 1000$) in a single line, representing the number of cities in Country $X$. The next line lists $N$ integers describing the population of each city.

All cities' population are between $1$ and $10000$(inclusive).

# Standard Output

For each test case, print `Case #t: ` first, in which $t$ is the number of the test case starting from $1$. Then output the minimum and maximum cost.

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
<tr><td>1
3
1 2 3</td><td>Case #1: 2 3</td></tr></table>


# Constraints



# Note

**Huge input/output. Please use `scanf/printf` for `C/C++`.**

For the first sample, we can build the roads between $1$ and $2$, $2$ and $3$ to get the minimum cost of $2$. And build the roads between $1$ and $2$, $1$ and $3$ to get the maximum cost of $3$.

# Source


