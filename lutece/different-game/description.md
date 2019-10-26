
# Content

Alice is playing a new game recently. In this game, there are $n$ different kinds of cards. We assume that Alice have $c\_i$ pieces of cards for $i\_{th}$ kind.

Alice is asked to divide them into $m$ piles and then arrange each pile in one line. After that, Alice will get $m$ sequences. For convenience, the sequences are labeled $S\_1, S\_2, \cdots , S\_m$. ** For each $i < j$ **,  Alice will get some points, equal to the length of the LCS(longest common subsequence) of $S\_i$ and $S\_j$. The total points is the sum of points for all $i < j$.

Now Alice is wondering the maximum points she can get.

As is known to everyone of you, Bob loves Alice very much. Could you tell Bob the answer to help Bob leave a good impression on Alice.

# Standard Input

The first line contains $2$ integers $m$ and $n$, indicating the number of sequences and the number of different kinds of card.

The second line contains $n$ integers $c\_i$, indicating the number of $i\_{th}$ card.

It is guaranteed that $1 \leq n, m \leq 100000, 0 \leq c\_i \leq 100000$.

# Standard Output

Print the answer module 1000000007 in one line.

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
<tr><td>2 2
2 3</td><td>2</td></tr></table>


# Constraints



# Note



# Source


