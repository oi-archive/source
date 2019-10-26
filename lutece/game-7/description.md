
# Content

One day,Tpkey has nothing to do when he glances at some kids playing games on grid area.Saddenly he gets an idea , 
inventing a new maze game.First he draws a big grid area consisting of $n\times n$ small grid. The grid area has a compeletly center.

The player will stand at the center,then he or she was given a hand of directional order,indicading that the player should jump to the neighbouring grid successively in this ordered direction.But some of this order is replaced by `?`, so that the player can jump at any direction.The winer will be the one who is the closest to the grid area boundary in the process of jumping.Then a kid is playing the game,but he stop,then he give a thought to guarantee he will be the winer.He feel so confused,but he know you are a good coder.He needs your help.

# Standard Input

The first of input is an integer $t$ ($0 < t < 50$) which stands for the number of test cases.

for each case will include two lnes, a number (int) and a string ($length<1000$) ,
the number's means is that Tpkey will draw a square area which has $n\times n$ small square.
and the string will include five letters `E` `W` `S` `N` `？` which stands for `EAST` `WEST` `SOUTH` `NORTH` and `Undetermined` 
and the string length at most $1000$.

# Standard Output

for each case ,the output should contain a single real number,on a single line:
the minimum distance from the square border when he jumped by the instructions.

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
15
?????
15
EE?WWW
29
WS?W?S?W?SES</td><td>2
4
6</td></tr></table>


# Constraints



# Note



# Source


