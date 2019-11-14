
# Content

A *Young diagram* is an arrangement of boxes in rows and columns
conforming to the following rules:
* the boxes in each row and each column are
contiguous,
* the left borders of all rows are aligned, and
* each row is not longer than the one above.

Here are some examples of Young diagrams:

<p class="text-center"><img src="/source/lutece/diagrams-tableaux/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODkxLzIwMTQwNTIzMTIzNjUzNDk3MTEucG5n.png" alt="title"></p>

A *semi-standard Young tableau* for a given number $N$ is a Young diagram that has its boxes
filled according to the following rules:
* Each box contains a single integer
between $1$ and $N$, inclusive,
* each integer is greater than or equal to the integer in the box to its left, and
* each integer is strictly greater than the integer in the box above.

Here is a list of all semi-standard Young
tableaux for $N=3$, based on a particular Young diagram:

<p class="text-center"><img src="/source/lutece/diagrams-tableaux/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODkxLzIwMTQwNTIzMTIzODA4NTUxMTIucG5n.png" alt="title"></p>

Your task is to count how many semi-standard Young tableaux are possible, based on
a given Young diagram, with a given $N$.

# Standard Input

Each test case consists of two lines. The first line of each test case specifies the Young diagram. This line starts with the number $k$ satisfying $1\le{}k \le{}7$, the number of rows, followed by $k$ positive integers $l\_1,l\_2,\ldots,l\_k$. These integers specify the number of
boxes on each row of the Young diagram, and they satisfy $7\ge{}l\_1\ge{}l\_2\ge\cdots\ge{}l\_k\ge{}1$.
The second line contains the integer $N$,
satisfying $k\le{}N\le{}7$.

# Standard Output

For each test case, print one line containing the number of
semi-standard Young tableaux based on the given Young diagram, with the
given $N$.

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
<tr><td>1 1
1
1 1
2
2 2 1
4
4 3 2 1 1
4</td><td>1
2
20
20</td></tr></table>


# Constraints



# Note



# Source


