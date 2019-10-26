
# Content

Mirko has a home library consisting of $N$ books arranged one on top of the other in a narrow cabinet. 
Since being well trained in the secrets of alphabet in the previous task, he now wishes to arrange the
books alphabetically, so that the book whose title comes first alphabetically ends up on top, and the 
alphabetically last one at the bottom of the pile. 

Mirko can easily **pull** a book **out** of the cabinet, but it is difficult to push it back into the pile, so the 
book can only be returned to the **top** of the pile. Thus, the only available method of sorting the books 
is repeatedly pulling a book out of the pile and placing it on top of the pile. 

The books are labelled with integers from $1$ to $N$, in alphabetical order. Therefore, Mirko wants them 
to be ordered as ($1, 2, \cdots, N$), counting from the top. For example, if $N = 3$ and the starting order is $(3, 
2, 1)$, two moves are sufficient. First, he pulls out the book number $2$ and places it on top, so the pile 
becomes $(2, 3, 1)$. After that, he does the same with book number $1$, thus the pile becomes $(1, 2, 3)$. 

Help Mirko by calculating the minimum number of moves needed to sort a given starting order.

# Standard Input

The first line of input contains the integer $N$ ($N \leq 300 000$).
 
Each of the next $N$ lines contains a single positive integer. These $N$ integers represent the order of 
Mirko’s books from top to bottom of the cabinet. Each of the integers $1, 2, \cdots, N$ appears exactly once.

# Standard Output

The first and only line of output must contain the required minimum number of moves.

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
<tr><td>3 
3 
2 
1</td><td>2</td></tr><tr><td>4 
1 
3 
4 
2</td><td>2</td></tr></table>


# Constraints



# Note



# Source


