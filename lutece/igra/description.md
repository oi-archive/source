
# Content

Having solved the tedious assignment, Mirko decided to play a game with his good friend Slavko. 

They have written a sequence of $N$ letters on a piece of paper. Each one of them is trying to put 
together a word using letters from the sequence. They alternate taking turns consisting of removing a 
single letter from the sequence and appending it to the end of their word. Mirko has the first turn. The 
game ends when no letters are remaining in the sequence. 

We define a word to be more beautiful than another word if it comes first alphabetically. The player 
who has the more beautiful word at the end of the game wins. If both players have equal words, they 
both lose. 

Mirko is a much better player than Slavko, so he has decided to make it easier for Slavko by always 
selecting the rightmost remaining letter in the sequence. Knowing this, Slavko wants to find out if it is 
possible for him to win and which is the most beautiful word he can end the game with.

# Standard Input

The first line of input contains an even positive integer $N$ ($2 \leq N \leq 100 000$). 

The second line of input contains $N$ characters, the starting letter sequence. All characters are lower 
case letters from the English alphabet.

# Standard Output

The first line of output must contain `DA` if it is possible for Slavko to win, and `NE` otherwise. 

The second line of output must contain the most beautiful word that Slavko can have at the end of the 
game.

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
ne</td><td>NE 
n</td></tr><tr><td>4 
kava</td><td>DA 
ak</td></tr><tr><td>8 
cokolada</td><td>DA 
acko</td></tr></table>


# Constraints



# Note

In test cases worth $50\%$ of total points the number $N$ will not exceed $1000$.

# Source


