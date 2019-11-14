
# Content

There is a country with $N$ cities, there are roads between some pairs of cities.

For every pair of cities, there is exactly one path between them, on which there are no cities passed more than once.

So it is obvious that there are $N-1$ roads and $\frac{N(N-1)}{2}$ paths.

The cities number from $1$ to $N$, and the $i^{th}$ city has one number $A\_i$.

A path is Bono if and only if the numbers $A\_i$ on the path are **non-strictly** increasing or decreasing.

i.e., if the numbers are $A\_{b\_1}, A\_{b\_2}, \dots, A\_{b\_m}$, $A\_{b\_i}\leq A\_{b\_{i+1}}\ , \forall 1\leq i\lt m$ or $A\_{b\_i}\geq A\_{b\_{i+1}}\ , \forall 1\leq i\lt m$ should be satisfied.

How many Bono paths in the country?

# Standard Input

The first line contains one integer $N$.

The second line contains $N$ integers, where the $i^{th}$ indicates $A_i$.

For the next $N-1$ lines, each line contains two integers $u, v$, meaning that there is a road between $u^{th}$ city and $v^{th}$ city.

$1\leq N\leq 10^5, 1\leq u, v\leq N, 1\leq A_i \leq 10^9$

# Standard Output

One integer indicating the number of bono paths in the country.

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
1 7 1 9
1 3
1 4
2 1</td><td>5</td></tr><tr><td>6
1 1 2 2 3 3
1 2
2 3
3 4
4 5
5 6</td><td>15</td></tr></table>


# Constraints



# Note

For sample 1:

![sample1](/source/lutece/b0n0-path/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTU1OS8yMDE3MDMyMTIxMTU1NTc5MjcucG5n.png)

The format of the text on $i^{th}$ node is $(i:A_i)$.

There are 5 bono paths: $(1, 2), (1, 3), (1, 4), (2, 1, 3), (3, 1, 4)$, while path $(2, 1, 4)$ is not bono path.

For sample 2:

![title](/source/lutece/b0n0-path/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTU1OS8yMDE3MDMyMTIxMjQwNzA4NzgucG5n.png)

All path are bono paths.

# Source


