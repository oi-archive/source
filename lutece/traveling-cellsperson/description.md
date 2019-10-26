
# Content

You have solved every problem from Project Euler in your head. Now it is time for a problem you might have heard of,namely The Traveling Salesperson, whose decision version is NP-complete. We consider the Traveling Salesperson problem in a 2D rectangular grid where every cell can be reached from their neighboring cells (up,down, left and right) and you can visit a cell as many times as you like (though, most of the cells aren't that interesting, so you might prefer not to visit them a lot).

![title](/source/lutece/traveling-cellsperson/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzE3LzIwMTQwOTAxMTgzMjM2OTc2MzMucG5n.png)

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. Then follow two integers $X$ and $Y$ , marking the width and height of the grid, respectively. Then follow $Y$ lines with $X$ characters, where the character `C` is a cell and the character `S` is the starting point.

$0 < T \le 50$

$0 < X \le 100$

$0 < Y \le 100$

All characters in a test case are `C`, except for exactly one, which is `S`.

# Standard Output

For each test case, output the minimum number of steps required to make a full roundtrip of the grid, starting and ending at $S$, and visiting each cell at least once.

Since you realize that this won't lead anywhere, finish off the output with `LOL`(without quotes) on a line of its own (**one per run, not per test case**).

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
4 4
CCCC
CCCC
CSCC
CCCC</td><td>16
LOL</td></tr></table>


# Constraints



# Note



# Source


