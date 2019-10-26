
# Content

Harriet T. Emmel is selling `real estate` on her web site in the form of $10$-by-$10$ square blocks of pixels.
She has divided her web page into a rectangular grid, with grid lines $10$ pixels apart. Anyone may rent
$10$-pixel-by-$10$-pixel blocks in this grid for posting artwork, advertising, or anything else.

Harriet expected that most customers would want to purchase rectangular regions of blocks, but a few
want to be more creative. For instance, an optician wanted to purchase blocks in the shape of a pair
of eyeglasses and a bow-and-arrow company wanted to rent space in the shape of a bullseye (in the
following, each square is a $10$-pixel-by-$10$-pixel block):

<p class="text-center">
<img src="/source/lutece/rent-a-pixel/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODcwLzIwMTQwNTEwMTgyMTQ4MjIyMjYucG5n.png" alt="title">
<h5 class="text-center">Figure $1$</h5>
</p>

Harriet has decided that, in the interests of simplicity, each purchase must be a single `orthogonally
convex` region of blocks. This simply means that any row or column of pixels, when intersected with
the region, must consist of either zero or one connected segments. For the two examples above, the
smallest orthogonally convex regions containing the desired blocks are:

<p class="text-center">
<img src="/source/lutece/rent-a-pixel/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODcwLzIwMTQwNTEwMTgyNTE5NjE5MjcucG5n.png" alt="title">
<h5 class="text-center">Figure $2$</h5>
</p>

As a service to her customers, H. T. Emmel lets them choose any set of blocks, then she calculates
the smallest orthogonally convex region containing them. Although, in general, this calculated region
might be disconnected, we assume, for simplicity, that it is connected, i.e., that there is an orthogonal
path of pixels connecting any pair of pixels in the region. Write the program that does this smallest
region calculation.

# Standard Input

Each test case will consist of a line containing a positive integer $n$, $n\leq 10000$, indicating the number of $10$-pixel-by-$10$-pixel blocks requested by the user, followed by one or more lines containing a total of $2n$ integers $r\_0\ c\_0\ r\_1\ c\_1\ \cdots r\_{n-1}\ c\_{n-1}$, $0\leq r\_i, c\_i\leq 10^9$. Each $r\_i\ c\_i$ pair gives the row and column number of the upper left pixel of one of these blocks. All of these coordinates will be multiples of $10$ and no
coordinate pair will be repeated withing a test case. Each test case is guaranteed to be covered by a
single, connected, minimal, orthogonally convex polygon. A line containing a single $0$ will terminate
input.

# Standard Output

For each test case, print the case number followed by the (row, column) pixel coordinates of the vertices
of the smallest orthogonally convex polygon containing the blocks described by the input. The first
coordinate should be for the block with the lowest row number and, among those, the lowest column
number. The coordinates should describe a clockwise traversal of the polygon.

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
<tr><td>30
20 20 20 30 20 40 20 50 20 60 20 70 20 80 20 90 20 100
20 110 20 120 20 130 20 140 20 150
30 20 30 70 30 100 30 150
40 20 40 70 40 100 40 150
50 30 50 40 50 50 50 60 50 110 50 120 50 130 50 140
28
80 60 80 70 80 80 80 90
90 50 90 100
100 40 100 70 100 80 100 110
110 40 110 60 110 90 110 110
120 40 120 60 120 90 120 110
130 40 130 70 130 80 130 110
140 50 140 100
150 60 150 70 150 80 150 90
0</td><td>Case 1: 20 20 20 159 49 159 49 149 59 149 59 30 49 30 49 20
Case 2: 80 60 80 99 90 99 90 109 100 109 100 119 139 119 139 109 149 109 149 99 159 99
159 60 149 60 149 50 139 50 139 40 100 40 100 50 90 50 90 60</td></tr></table>


# Constraints



# Note

Because of space limitation, the output for Case $2$ is shown over multiple lines. In actuality, it
would all be on a single line.

# Source


