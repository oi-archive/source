
# Content

Mirko has grown tired of all the books, so he decided to go to the amusement park with his friends, 
despite not liking roller coasters. While his friends are having the time of their lives riding the coasters, 
Mirko is sitting on a bench, waiting and thinking about the possible paths of the coasters. 

The amusement park’s area can be represented as a table of $R$ rows by $C$ columns. A roller coaster has 
to start from the upper left corner and end at the lower right corner of the table. Each cell can be 
visited at most once, but not all cells need to be visited. It can continue its path from the current cell to 
the adjacent one above, below, to the left, or to the right of it. 

Each cell has a positive integer value associated with it, specifying how amusing that cell is to visitors. 
The total amusement value of the coaster is the sum of amusement values of all cells that the coaster 
visits. Help Mirko determine any one of the most amusing coasters (ones with the maximum sum).

# Standard Input

The first line of input contains two integers $R$ and $C$ ($2 \leq R, C \leq 1000$), the dimensions of the table. 

Each of the next $R$ lines contains $C$ positive integers smaller than $1000$, specifying the amusement 
values of the respective table cells.

# Standard Output

The first and only line of output must contain a sequence of letters with no blanks. The letters specify 
the sequence of directions that the coaster follows, starting from the upper left and ending at the lower 
right corner. The directions up, right, down, left are marked by letters `U`, `R`, `D`, `L`, respectively. 

**Note**: The solution isn’t guaranteed to be unique.

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
<tr><td>3 3 
5 1 3 
2 4 8 
1 1 2</td><td>RRDLLDRR</td></tr><tr><td>2 2 
2 1 
3 4</td><td>DR</td></tr></table>


# Constraints



# Note

Test cases worth $70\%$ of total points the numbers $R$ and $C$ will not exceed $30$.

# Source


