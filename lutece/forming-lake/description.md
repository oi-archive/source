
# Content

There is a mountain standing on a rectangle with lower left corner $(0,0)$ and upper right corner $(N,M)$.

If it is rainy for a long time, and the surface of mountain can't absorb water, there will be lakes on the mountain finally.

To simplify this problem, the mountain can be described as a $N*M$ matrix $H$, which $H_{i,j}$ is the altitude of the flat square with lower left corner $(i-1,j-1)$ and upper right corner $(i,j)$.

Now you should determine the final depth of water on the square with lower left corner $(i-1,j-1)$ and upper right corner $(i,j)$ for every $1\leq i\leq N$ and $1\leq j\leq M$.

# Standard Input

The first line contains two integers $N$ and $M$.

Then $N$ lines follow, each with $M$ integers split by spaces, where the $j^{th}$ integer in $i^{th}$ line indicate $H_{i,j}$.

$1\leq N, M\leq 1000$

$1\leq H_{i,j}\leq 10^9$

# Standard Output

Print the final depth of water on the square with lower left corner $(i-1,j-1)$ and upper right corner $(i,j)$ for every $1\leq i\leq N$ and $1\leq j\leq M$, using the same format as input.

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
<tr><td>4 4
4 4 4 4
4 1 4 4
4 1 1 4
4 4 4 4</td><td>0 0 0 0
0 3 0 0
0 3 3 0
0 0 0 0</td></tr><tr><td>5 5
2 4 4 4 2
4 2 1 2 4
4 1 2 1 4
4 2 1 2 4
2 4 3 4 2</td><td>0 0 0 0 0
0 1 2 1 0
0 2 1 2 0
0 1 2 1 0
0 0 0 0 0</td></tr></table>


# Constraints



# Note

![title](/source/lutece/forming-lake/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTMxMi8yMDE2MDQwMjEwNDUzNzU3ODUucG5n.png)

A picture for sample 2.

# Source


