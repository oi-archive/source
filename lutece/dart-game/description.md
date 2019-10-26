
# Content

Darts originated in Australia. Australia's aborigines initially for hunting and hit the enemy's weapon. 

A game of darts in which the players attempt to score points by throwing the darts at a target.

![title](/source/lutece/dart-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vOTI3LzIwMTQwNjAzMjAwMDA1NzI4My5qcGc=.jpg)

Darts movement rules of the game is very simple, the target is $1$-$20$ points and the central circle is $50$ small zoning, edge is $25$ division, the rough circle line of fan-shaped covered area is $1$-$20$ points and three times the corresponding division. This game is generally played by two people but can be played by teams. Each player starts with N points. The goal for each player is to reach zero by subtracting the amount they score from the amount they had left,but final throwing must be double division. And the first to reduce his/her score to zero wins.

So the task is : 

Given a dart scores $N$ that a player starts with, you are required to calculate how many different ways to reach zero. One is different way to another means at least one dart hits different division.Ways which have different orders and same divisions are the same way. For example,if $N=4$,there are $4$ different ways reach to zero:the first is double $2$, the second is $2$ and double $1$, the third is twice of double $1$,the fourth is twice of $1$ and double $1$ .

The answer may be very large,you have to module it by $2011$.

# Standard Input

The input contains several test cases.

Each test case contains an integer $N ( 0 < N \leq 1001 )$ in a line.

$N=0$ means end of input and need not to process.

# Standard Output

For each test case, output how many different ways to reach zero.

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
<tr><td>5
4
3
2
1
0</td><td>6
4
1
1
0</td></tr></table>


# Constraints



# Note

$5=1+1 \times 2+1 \times 2$

$5=1+1+1+1 \times 2$

$5=3+1 \times 2$

$5=1 \times 3+1 \times 2$

$5=1+2+1 \times 2$

$5=1+2 \times 2$

$4=2 \times 2$

$4=1+1+1 \times 2$

$4=2+1 \times 2$

$4=1 \times 2+1 \times 2$

$3=1+1 \times 2$

$2=1 \times 2$

$1$: no way

# Source


