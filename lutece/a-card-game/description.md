
# Content

There was a popular card game when I was young. The rules are descried below:

First, choose $13$ pieces of cards labeled `A`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`,`10`,`J`,`Q`,`K` respectively and pile these cards, then you are asked to repeat the following operation for $13$ rounds. First take out one card on the top and put it on the bottom of this pile, then pick the card from the top of this new pile out and arrange it in a queue.Can you tell the original order of the pile of cards if the queue which you have arranged is `A`,`2`,`3`,`4`,`5`,`6`,`7`,`8`,`9`,`10`,`J`,`Q`,`K`?

Assume that you are given $N$ pieces of cards labeled $1$ to $N$ and asked to repeat the operation for $N$ rounds. Every round you should firstly remove $K$ pieces of cards from the top to the buttom one by one, then pick the card from the top of this new pile out and arrange it in a queue. Can you tell the original order of the pile of cards if the queue which you have arranged is $1, 2, \cdots N$?

# Standard Input

First a integer $T$ ($T\leq 10$), indicates there are $T$ test cases.
Every test case has two integers $N$, $K$($1\leq N\leq 10^6$, $1\leq K\leq 10$).

# Standard Output

For the $k\_{th}$ case, assume that the original sequence (from top to bottom) is $S\_1, S\_2, \cdots S\_N$. Then you should output `Case #k: ` followed by a single number on a single line, which indicates the number of pairs satisfy that $i < j$ and $S\_i > S\_j$.

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
13 1
13 2</td><td>Case #1: 28
Case #2: 34</td></tr></table>


# Constraints



# Note

in the first case the sequence is: `7 1 12 2 8 3 11 4 9 5 13 6 10`

in the second case the sequence is: `11 5 1 8 10 2 6 12 3 9 7 4 13`

# Source


