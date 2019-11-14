
# Content

Even though he has found all the most amusing rides, Mirko’s enthusiasm still isn’t fading. He opened 
his graph paper notebook and started colouring squares, and a new, even harder problem dawned on 
him. 

You are given a square table consisting of $N$ rows by $N$ columns. Each cell is either black or white. 

A set of cells forming a rectangle, with horizontal and vertical edges following cell borders, shall be 
called a **black rectangle** if all cells inside the rectangle are black and it consists of **at least two** cells. 

![title](/source/lutece/crni/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNTAzLzIwMTQwODI0MjMxNDAwNjE3MzMucG5n.png)

The left image shows two rectangles which **are not** black rectangles. The rectangle labelled 1 is not a 
black rectangle because it contains a white cell, and the rectangle labelled 2 is not a black rectangle 
because it consists of only one cell. On the other hand, the right image shows three valid black 
rectangles. 

Calculate the number of possible selections of two black rectangles that have **no common cells**. As the 
required number can be extremely large, you should output the remainder of dividing that number by 
**10 007**.

# Standard Input

The first line of input contains the integer $N$ ($2 \leq N \leq 1000$).
 
Each of the next $N$ lines contains a single row of the table, consisting of $N$ symbols. The symbol `C` 
represents a black cell, while `B` represents a white cell.

# Standard Output

The first and only line of output must contain the remainder of dividing the required number by $10007$.

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
CC 
CC</td><td>2</td></tr><tr><td>3 
CCB 
CCB 
CBB</td><td>5</td></tr><tr><td>5 
BCCBB 
BBCBB 
BCCBB 
BBBBB 
CCBBB</td><td>8</td></tr></table>


# Constraints



# Note



# Source


