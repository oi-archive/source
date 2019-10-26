
# Content

Little P is playing a music game called OSU! recently.In this game, player needs to click the notes on the screen.To simplify this problem, we only consider whether the player click the note successfully.At the start of one song, $Combo$ and $Score$ are both $0$.If player click one note successfully, $Combo$ will be added by one, and after that, $Score$ will be added by $Combo\times Combo$.Otherwise, $Combo$ will be set to zero, and $Score$ will be added by zero, too.

Now for one song, Little P knows that there are $n$ notes in this song, and he can get max $Combo$ $m$. Little P wants to know the max $Score$ that he can get.

# Standard Input

The first line contains an integer $T$ ($1\leq T\leq 20$), indicating the number of test cases.

In each test case, there are two integer $n$,$m$ ($0< m\leq n\leq 10^9$), indicating the total notes in this song, and the max $Combo$ that Little P can get.

# Standard Output

For each test case, output one line with an integer, which is the max score that Little P can get in this song.

Because the answer is so large, please module the answer with $1000000007$.

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
5 5
8 3</td><td>55
28</td></tr></table>


# Constraints



# Note



# Source


