
# Content

Bob is playing a game with $n$ rounds.

He has $s$ points initially, and for every round, he will add $a$ points if he win, or subtract $b$ points if he lose.

If his score is less than zero after a round, the score will be changed to zero.

Bob is not honest always, so he may use a cheater to get an abnormal score.

Now you are given his final score $t$, and you should determine whether Bob cheat in the game.

If it is impossible to get $t$ points, print `CHEATED`.

Otherwise, print any possible sequence of game process.

# Standard Input

Five integers $n,s,t,a,b$.

$1\leq n\leq 10^6$

$0\leq s, t\leq 10^9$

$1\leq a, b\leq 10^9$

# Standard Output

If it is impossible to get $t$ points, print `CHEATED`.

Otherwise, print a string with $n$ characters, consisting of `O` and `X`. If $i^{th}$ character is `O`, Bob win in $i^{th}$ round; if $i^{th}$ character is `X`, Bob lose in $i^{th}$ round.

There may be multiple solutions, you can print any one of them.

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
<tr><td>4 2 3 3 3</td><td>XOXO</td></tr><tr><td>2 1 100 2 2</td><td>CHEATED</td></tr></table>


# Constraints



# Note



# Source


