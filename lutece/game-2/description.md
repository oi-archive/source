
# Content

Consider the following two-player game played with a sequence of N positive integers $(2 \leq N \leq 1000)$ laid onto a game board. Player $1$ starts the game. The players move alternately by selecting a number from either the left or the right end of the sequence. That number is then deleted from the board, and its value is added to the score of the player who selected it. A player wins if his sum is greater than his opponents.

Write a program that implements the optimal strategy. The optimal strategy yields maximum points when playing against the `best possible` opponent. Your program must further implement an optimal strategy for player $2$.

# Standard Input

In the first line is one integer $T(T \leq 100)$

$T$ cases follow. For each case, the first line contains one integer $n$, the size of the board. Then the second line give you $n$ integers (no more than $1000$) that are the contents of the game board, from left to right.

# Standard Output

For each case print one line with two integer $v\_1$ and $v\_2$ means the maximum points player $1$ and player $2$ can get.

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
6
4 7 2 9 5 2</td><td>18 11</td></tr></table>


# Constraints



# Note



# Source


