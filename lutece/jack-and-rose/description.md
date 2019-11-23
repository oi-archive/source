
# Content

Jack and Rose are fond of gaming. During the night on Titanic, Jack comes up with a new interesting game. 

The game is designed for $2$ players so that he and Rose can compete in it. He draws $N$ slots in a row, and assigns a point to each slot. Then he puts his piece labeled with $A$ in the $1\_{st}$ slot (the leftmost one) and Rose's piece labeled with $B$ in the $N\_{th}$ slot (the rightmost one). Jack and Rose take turns to play. Each round, the player must move $A$ to the next slot to its right, or move $B$ to the next slot to its left. If both pieces are in the same slot, the game ends. (Please refer to sample for more details.)

Whenever $A$ or $B$ is moved to a new slot, the new slot's point will be added to Jack's or Rose's total point. Of course if the point is negative, the owner's total point will be decreased.

Initially, because $A$ is in the $1\_{st}$ slot and $B$ is in the $N\_{th}$ slot, Jack's point equals to the point of $1\_{st}$ slot and Rose's equals to the point of $N\_{th}$ slot. Now Jack wants to know, after the row of slots are drawn, whether or not he can get more points in total and beat Rose definitely. Both Jack and Rose will try their best.

# Standard Input

There will be multiple test cases. The first line of the input is an integer $T$ ($T \leq 100$) indicating the number of test cases.

For each test case an integer $N$ ($2 \leq N \leq 10000$) comes first in a single line representing the number of slots drawn in a row. The next line lists $N$ integers describing the point assigned to every slot.

Note these points will be limited in the range $[-10000, 10000]$.

# Standard Output

For each test case print `Case #x: s` in a single line, in which $x$ is the number of the test case starting from $1$, and s is a string. If Jack can definitely beat Rose, $s$ is `win`; if Jack is definitely a loser to Rose, $s$ is `lose`; otherwise $s$ is `tie`.

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
4
1 3 2 3
4
1 2 2 3
5
-1 -2 -1 -1 -1</td><td>Case #1: win
Case #2: tie
Case #3: lose</td></tr></table>


# Constraints



# Note

For the first sample, both choose move his/her own piece. And Jack gets $1+3+2 = 6$, Rose gets $3+2 = 5$.

# Source


