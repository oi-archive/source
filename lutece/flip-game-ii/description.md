
# Content

Flip game is played on a rectangular $4\times 4$ field with two-sided pieces placed on each of its $16$ squares. One side of each piece is white and the other one is black and each piece is lying either it's black or white side up. Each round you flip $3$ to $5$ pieces, thus changing the color of their upper side from black to white and vice versa. The pieces to be flipped are chosen every round according to the following rules:
1. Choose any one of the $16$ pieces.
2. Flip the chosen piece and also all adjacent pieces to the left, to the right, to the top, and to the bottom of the chosen piece (if there are any).

![title](/source/lutece/flip-game-ii/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDc5LzIwMTQwODIyMjIyMzI0MTMyMjgucG5n.png)

Consider the following position as an example:
```
1010
0000
1101
1001
```

Here `1` denotes pieces lying their black side up and `0` denotes pieces lying their white side up. If we choose to flip the $1\_{st}$ piece from the $3\_{rd}$ row (this choice is shown at the picture), then the field will become:
```
1010
1000
0001
0001
```

The goal of the game is to flip all pieces white side up. To make the game more hard , we expand the rectangular to $20\times 20$,and keep the rules unchanged. 

Note : If a piece is fliped a second time, it exactly cancels the effect of the first flip, so no piece ever need be fliped more than once.

For each piece ,you need to determine whether it should be fliped or not.

# Standard Input

The first line of the input is a positive integer $n$($n\leq 100$) which is the number of cases that follow. Each case will be $20$ lines, each of which has $20$ nunbers `0` or `1` separated by one space. A `0` indicates that the piece is white side up, while a `1` indicates that the piece is black side up initially.

# Standard Output

For each case, output a $20\times 20$ rectangular contain `0` or `1`(in the same format as the input), In each case, `1`'s indicate pieces that must be fliped, while `0`'s indicate pieces which are not fliped. There should be exactly one space between each `0` or `1` in the output.You can assume that the answer is unique.

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
1 1 0 0 1 0 0 0 0 0 1 1 1 1 1 1 1 0 1 0
1 0 0 1 0 0 1 0 0 1 1 0 1 0 1 0 1 1 1 0
1 1 0 1 1 0 1 1 1 0 1 0 0 1 1 1 1 1 1 0
0 1 0 0 0 0 0 0 0 0 0 1 0 1 0 0 0 1 1 0
1 1 0 0 0 0 0 0 1 0 0 1 0 1 1 0 0 0 1 1
1 1 1 0 0 0 1 0 1 0 1 1 0 0 0 1 1 1 1 0
0 0 1 0 1 1 1 0 1 0 0 0 1 0 0 0 1 1 1 1
1 1 1 1 1 1 1 0 1 0 0 0 0 0 1 0 0 1 0 1
0 1 0 1 0 1 1 1 0 0 1 0 0 0 0 1 0 1 0 0
1 0 1 1 0 0 0 0 1 1 0 1 0 1 1 1 0 1 1 0
1 0 1 1 0 1 1 0 0 1 0 0 0 1 1 0 1 1 1 1
1 1 0 1 0 0 0 0 0 0 0 1 1 0 1 1 0 0 0 0
0 1 0 1 0 1 1 0 0 1 0 0 0 1 0 0 0 0 1 1
1 0 0 0 1 0 0 1 1 1 1 0 0 1 1 0 0 0 1 1
1 0 1 1 1 1 0 1 0 1 0 0 1 1 0 0 1 0 1 1
0 1 0 0 1 1 0 1 1 0 1 0 0 1 1 1 1 0 1 1
1 1 0 1 1 1 1 0 0 1 0 0 1 0 0 1 0 1 0 1
1 1 1 1 0 0 0 1 1 0 1 0 0 0 1 0 0 0 1 1
1 0 1 0 0 1 0 1 1 0 0 0 1 1 0 1 0 0 0 0
1 1 0 1 0 1 1 0 0 0 0 0 0 1 1 0 1 1 0 1</td><td>1 0 1 1 1 1 0 1 0 1 0 0 1 0 0 0 0 0 0 0
0 1 0 1 0 0 0 1 0 1 0 0 0 0 1 1 1 0 1 0
1 1 1 1 0 1 0 0 0 1 0 0 0 1 1 1 1 1 0 1
1 1 1 0 1 1 0 0 0 0 0 0 1 1 1 1 1 1 0 1
1 1 1 1 0 1 1 0 0 1 0 0 0 1 0 0 0 0 1 0
0 1 0 0 1 1 0 1 0 1 1 1 0 1 1 1 1 0 0 1
1 1 1 0 0 1 0 1 1 1 0 1 0 1 1 0 1 0 1 1
0 0 1 1 1 1 1 1 0 1 1 0 1 1 1 1 1 1 1 0
0 1 0 0 0 1 0 1 0 1 0 1 0 0 1 1 0 0 1 1
1 0 0 0 0 1 0 1 0 0 0 1 0 0 1 0 0 1 1 0
0 0 1 1 1 0 0 0 0 0 1 1 1 0 1 1 1 1 0 0
0 1 1 0 0 1 1 1 0 0 0 0 0 1 0 1 0 0 1 1
0 1 1 1 0 0 1 0 1 0 1 0 1 1 0 1 0 0 0 0
1 0 0 1 1 1 1 1 1 1 1 0 0 0 0 0 1 0 0 0
0 0 0 1 0 1 0 0 1 0 0 1 1 0 1 0 1 1 1 1
0 0 0 1 0 1 0 1 0 1 0 0 1 1 1 0 0 1 0 1
0 1 1 0 1 1 0 0 0 1 0 0 1 0 0 0 1 0 0 1
0 1 0 0 1 0 0 1 1 1 1 1 1 0 1 0 1 1 1 1
0 1 1 0 0 0 1 1 0 0 0 1 1 0 0 0 1 1 0 0
0 1 1 1 1 0 0 0 1 1 0 1 0 0 1 0 1 1 0 1</td></tr></table>


# Constraints



# Note



# Source


