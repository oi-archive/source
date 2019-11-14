
# Content

lxhgww feels quite bored these days,so he invented some weird game to kill time.

`Counting is Easy` is undoubtedly the weirdest, which is played on an $N\times N$ chess board. You are supposed to put $N$ rooks on the chess board,and there shouldn't be two of these in the same row or column. There are many different assignment,and it's clear that the exact number is $N!$.

In this game,there is a positive integer number on each cell of the board,an assignment's value is the product of all the numbers whose cells are occupied by rooks.To make the game more interesting,an assignment may be nagetive or possitive,the sign is decided by the number of `Z Pairs`.If there is a pair of rooks in the assignment,and one is on the right-top direction(any angle is accepted) to another,this pair is a `Z Pair`.If there are odd number of `Z Pairs`,this assignment is negative,otherwise is positive.

The goal of this game is to summarize all the $N!$ assignment's value,don't forget to use minus operation while the assignment is negative.

The final answer $S$ is too large to write down,so your task is just to calculate the result $S \mod P$.

# Standard Input

There are multiple test cases in one input file.Each test case begins with two integer numbers $N$(where $2\leq N\leq 200$) and $P$($2\leq P\leq 1000000000$).The next $N$ lines each contains $N$ integer numbers,which describes the value of each chess board cell,all the numbers are in the range of $[0,1000000000]$.The input is terminated by an invalid test case with $N = P = 0$, which should not be processed.

# Standard Output

For each test case,output one single line contains the answer $S\mod P$.

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
<tr><td>2 10
4 9
2 8
0 0</td><td>4</td></tr></table>


# Constraints



# Note

There are two assignments(# means Rook):
```
*#
#*
```
```
#*
*#
```
First assignment's value is $2\times 9=18$,and there are one `Z-Pair`,so it's negative.

Second assignment's value is $4\times 8=32$,and there are no `Z-pair`,so it's positive.

So the total value $S= -18 + 32 =14$,and $S\mod P=14\mod 10=4$

# Source


