
# Content

Streets in City Line lie on one line, one by one. Standy wants to take a tour in City Line within $D$ hours. Before visit, Standy got the map. There are $N+1$ crossings connected by $N$ roads. He can start from and end at any crossing. 

![title](/source/lutece/d-hours/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTcwLzIwMTQwODI3MTg0NzM5NDYxMjAuanBn.jpg)

Sightseeing on any road takes ONE hour. After passing each road, Standy gets a happiness score. The more happiness score he gets, the happier he is. It's boring to visit a road more than once. For the $k\_{th}$ time Standy visits the $i\_{th}$ road, the happiness score he gets is

$a\_i-(k-1)\times b\_i$

Now please give Standy a plan to make him be the happiest man on earth.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T \leq 30$) indicating the number of test cases.

For each test case there are two integers $N$ and $D$ ($1 \leq N, D \leq 100$) in a single line, representing the number of roads in City Line and the time of the tour. **For the following $N$ lines, each line lists $a\_i$ and $b\_i$.** $1 \leq a\_i, b\_i \leq 10^6$, $a\_i - (D-1) \times b\_i \geq 0$.

# Standard Output

For each test case, print `Case #t: ` first, in which t is the number of the test case starting from $1$. Then output the maximum happiest score you can get.

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
2 3
2 1
3 1</td><td>Case #1: 7</td></tr></table>


# Constraints



# Note

Route `crossing 1 -> crossing 2 -> crossing 3 -> crossing 2` gets the highest score.

# Source


