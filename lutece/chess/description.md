
# Content

***NOTICE: The SPJ program is missing now, if you want submit this problem, please write a SPJ and contact the staff (muziriyun@gmail.com)***

In chess the bishop is the chessman, which can only move diagonal. It is well known that bishops can
reach only fields of one color but all of them in some number of moves (assuming no other figures
are on the field). You are given two coordinates on a chess-field and should determine, if a bishop
can reach the one field from the other and how. Coordinates in chess are given by a letter (`A` to
`H`) and a number ($1$ to $8$). The letter specifies the column, the number the row on the chessboard.

![201308010022324891.png](/source/lutece/chess/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTQvMjAxMzEyMjkwMDM4MDAwNDkyLnBuZw==.png)

*Chessboard, bishop and fields the bishop can reach in one move*

# Standard Input

The input starts with the number of test cases. Each test case consists of one line, containing the
start position $X$ and end position $Y$ . Each position is given by two space separated characters. A
letter for the column and a number for the row. There are no duplicate test cases in one input.

# Standard Output

Output one line for every test case. If it's not possible to move a bishop from $X$ to $Y$ in any number
of moves output `Impossible`. Otherwise output one possible move sequence from $X$ to $Y$ . Output
the number $n$ of moves first (allowed to be $4$ at most). Followed by $n + 1$ positions, which describe
the path the bishop has to go. Every character is separated by one space. There are many possible
solutions. Any with at most $4$ moves will be accepted. Remember that in a chess move one chessman
(the bishop in this case) has to change his position to be a valid move (i.e. two consecutive positions
in the output must differ).

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
E 2 E 3
F 1 E 8
A 3 A 3</td><td>Impossible
2 F 1 B 5 E 8
0 A 3</td></tr></table>


# Constraints



# Note



# Source


