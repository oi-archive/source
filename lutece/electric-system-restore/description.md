
# Content

After building and improving the traffic system of Country X, Qiqi wants to restore the electric system. Every City in Country X can be supplied by the base station or itself. The cost of transportation between base station and a city is the distance between them, i.e. if their coordinates are $(x\_1, y\_1)$ and $(x\_2, y\_2)$, their distance equals to $|x\_1 - x\_2| + |y\_1 - y\_2|$. Also, it costs $C\_i$ to power itself for the $i\_{th}$ city. 

Due to some reasons, the number of cities powering themselves should be no more than $K$. As the chief designer of Country X, it's your job to place the base station and assign the cities powering themselves to minimize the total cost. Note that you can place the base station at any integer point.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T \leq 20$) indicating the number of test cases. 

For each test case there are two integers $N$ and $K$ ($1 \leq N \leq 1000$, $0 \leq K \leq 20$, $K \leq N$) in a single line, representing the number of cities in Country X and Qiqi allows at most $K$ cities power itself. The next line lists $N$ integers, $C\_i$, describing the cost of power itself of each city. Then $N$ lines follow, each contains two integers $X\_i$ and $Y\_i$, indicating the coordinate of the $i\_{th}$ city. $0 \leq X\_i, Y\_i, C\_i \leq 10^6$ for $1 \leq i \leq N$.

# Standard Output

For each test case, print `Case #t: ` first, in which $t$ is the number of the test case starting from $1$. Then output the minimum costs.

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
4 1
2 2 2 2
1 1
1 2
2 1
2 3</td><td>Case #1: 4</td></tr></table>


# Constraints



# Note

For the first sample, we should build the base station at $(1,1)$ and make the $4\_{th}$ city power itself.

# Source


