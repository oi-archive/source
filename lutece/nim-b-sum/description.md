
# Content

The game of NIM is played with any number of piles of objects with any number of objects in each pile. At each turn, a player takes one or more (up to all) objects from one pile. In the normal form of the game, the player who takes the last object is the winner. There is a well-known strategy for this game based on the nim-$2$ sum.

The Nim-$B$ sum (nim sum base $B$) of two non-negative integers $X$ and $Y$ (written $NimSum(B, X, Y)$) is computed as follows:
1. Write each of $X$ and $Y$ in base $B$.
2. Each digit in base $B$ of the Nim-$B$ sum is the sum modulo $B$ of the corresponding digits in the base $B$ representation of $X$ and $Y$.

For example:
* $NimSum(2, 123, 456) = 1111011 ¤111001000 = 110110011 = 435$
* $NimSum(3, 123, 456) = 11120 ¤121220 = 102010 = 300$
* $NimSum(4, 123, 456) = 1323 ¤13020 = 10303 = 307$

The strategy for normal form Nim is to compute the Nim-$2$ sum $T$ of the sizes of all piles. If at any time, you end your turn with $T = 0$, you are guaranteed a WIN. Any opponent move must leave $T$ not $0$ and there is always a move to get $T$ back to $0$. This is done by computing $NimSum(2, T, PS)$for each pile; if this is less than the pile size ($PS$), compute the difference between the $PS$ and the Nim-$2$ sum and remove it from that pile as your next move.

Write a program to compute $NimSum(B, X, Y)$.

# Standard Input

The first line of input contains a single integer $P$, ($1\leq P\leq 1000$), which is the number of data sets that follow. Each data set is a single line that contains the data set number, followed by a space, followed by three space separated decimal integers, $B$, $X$ and $Y$. $2\leq B\leq 2000000$, $0\leq X\leq 2000000$, $0\leq Y\leq 2000000$.

# Standard Output

For each data set there is one line of output. It contains the data set number allowed by a single space, followed by $N$, the decimal representation of the Nim sum in base $B$ of $X$ and $Y$.

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
<tr><td>4
1 2 123 456
2 3 123 456
3 4 123 456
4 5 123 456</td><td>1 435
2 300
3 307
4 429</td></tr></table>


# Constraints



# Note



# Source


