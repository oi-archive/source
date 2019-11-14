
# Content

The "Biology Operator-X" (BOX) is a new system developed by scientists, 
to help them learn the characteristics of a special kind of cell.

The BOX has $H$ rows, each row contain exactly $W$ squares, forming a $H\times W$ rectangle. 
At first scientists choose $N$ squares from the first row, and for each of them, they put a single cell in it.

The BOX will not look beautiful if $H$ is too large, 
so $H$ will always be no more than $100\times W$.

The cell will grow following some rules:

For a square at row $A$, column $B$, as $(A,B)$, 
each cell in that square will split into three cells, 
one will move to the square below, as $(A+1,B)$, 
one will move to the square at lower-left $(A+1,B-1)$, 
and one will move to the square at lower-right $(A+1,B+1)$. 
So, after moving, there will be no cell in the original square.

Some cells may move out of the BOX, 
those cells will die immediately, 
and will not grow any more.

Scientist chooses a single square at the bottom of the BOX. 
Any cells moving into that square will be collected, 
and will not split and move anymore.

Given the position of that square, 
how many cell will they collect in the end?

The answer may be large, 
please output the number module a prime number given in the input.

# Standard Input

The first line contains two integers $H$, $W$, $(1\leq H, W\leq 10^9, \frac{H}{W} \leq 100)$, 
describing the size(height and width) of BOX.

Next line has a single integer $N$ ($1\leq N\leq 10$), 
it is the number of squares chosen by the scientists to put cells at the very beginning.

The third line contains $N$ integers $A\_1,A\_2\cdots A\_N$, seperated by space. 
They are the $N$ squares chosen by the scientists to put cells in the first row. 
In other words, those squares will locate at $(1,A\_1), (1,A\_2), \cdots , (1,A\_N)$.  $(1\leq Ai\leq W, 1\leq i\leq N)$

Then two integers $P$ and $Mod$ are given in the fourth line. 
Scientists will collect cells from the square $(H,P)$ $(1\leq P\leq W)$, and $Mod$ is the module number. 
($1\leq Mod\leq 1000$, $Mod$ is a prime number).

# Standard Output

Output the answer module $Mod$.

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
<tr><td>5 5 
5
1 2 3 4 5
3 11</td><td>3</td></tr></table>


# Constraints



# Note

The example is shown in the picture below.

![title](/source/lutece/everywhere/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODA5LzIwMTQwNDA1MDYwNjM0Mjc0MS5wbmc=.png)

# Source


