
# Content

Totalfrank has fall in love with JoyZhang for a long time. But Totalfrank is from Mars and JoyZhang is from Venus. You know it’s hard to keep the subtle relationship for a long distance. Recently, Totalfrank misses her so much and can’t wait to date her. But JoyZhang thinks that she would only date clever guys. So she decides to play an interesting checkers with him. And if he wins, she will date him.

They play checkers in a board with $N$ rows and $2$ columns. Each player has exactly one piece in every column. Every round, Totalfrank must move one but only one of his two pieces upwards by a grid first, and then JoyZhang moves one of her two pieces downwards by a gird. When a piece meets another player’s piece, it must jump it, meaning that you should move it by two grids. Every piece can’t move out of board. The one who can’t move loses the game.

Now give you a situation and Totalfrank moves first, can you tell Totalfrank who will win. You may assume that they are all clever enough.

![title](/source/lutece/interesting-checkers/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzY4LzIwMTQwNDExMTg1NDM1Nzc5MzcucG5n.png)

Pictures above are corresponding with sample inputs.

# Standard Input

The first line of input contains an integer $T$ ($T\leq 2000$), which is the number of data sets that follow.

Every data set contains only one line with $5$ integers $N$, $x\_1$, $x\_2$, $y\_1$, $y\_2$, ($2\leq N\leq 10^{18}, 0\leq x\_1,x\_2,y\_1,y\_2 < N$)indicating the number of rows, the distances from bottom to Totalfrank’s piece in $1\_{st}$ column and $2\_{nd}$ column and the distances from top to JoyZhang’s piece in $1\_{st}$ column and $2\_{nd}$ column. You can assume that no $2$ pieces are in the same grid at the beginning.

# Standard Output

For every test case, you should output `Case #k:` first in a single line, where $k$ indicates the case number and starts at $1$. Then output the `Totalfrank` if Totalfrank wins or `JoyZhang` if JoyZhang wins.

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
3 0 0 0 1
3 0 0 1 1
3 1 0 0 0</td><td>Case #1:
Totalfrank
Case #2:
JoyZhang
Case #3:
Totalfrank</td></tr></table>


# Constraints



# Note



# Source


