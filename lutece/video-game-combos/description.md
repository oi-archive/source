
# Content

Bessie is playing a video game! In the game, the three letters `A`, `B`, and `C` are the only valid buttons. Bessie may press the buttons in any order she likes; however, there are only $N$ distinct combos possible ($1 \leq N \leq 20$). Combo $i$ is represented as a string $S\_i$ which has a length between $1$ and $15$ and contains only the letters `A`, `B`, and `C`.

Whenever Bessie presses a combination of letters that matches with a combo, she gets one point for the combo. Combos may overlap with each other or even finish at the same time! For example if $N = 3$ and the three possible combos are `ABA`, `CB`, and `ABACB`, and Bessie presses `ABACB`, she will end with $3$ points. Bessie may score points for a single combo more than once.

Bessie of course wants to earn points as quickly as possible. If she presses exactly $K$ buttons ($1 \leq K \leq 1,000$), what is the maximum number of points she can earn?

# Standard Input

* Line $1$: Two space-separated integers: $N$ and $K$.
* Lines $2\cdots N+1$: Line $i+1$ contains only the string $S\_i$, representing
combo $i$.

# Standard Output

* Line $1$: A single integer, the maximum number of points Bessie can
obtain.

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
<tr><td>3 7
ABA
CB
ABACB</td><td>4</td></tr></table>


# Constraints



# Note

The optimal sequence of buttons in this case is `ABACBCB`, which gives $4$
points--$1$ from `ABA`, $1$ from `ABACB`, and $2$ from `CB`.

# Source


