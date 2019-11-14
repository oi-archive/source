
# Content

In Starcraft II, Stalker is an unusual kind of unit for its amazing ability called `blink`. Blink means you can move from one position to another one immediately as long as the distance between the two position is less than $D$. Now, there is $N$ stalkers on some islands, and everyone have a target island to go. And of course, targets of them can be variable. Because any stalker can't move on water, they can only blink between islands. For some strange reason, only some particular pairs of island are allowed to blink. Your task is to determine whether they can move to their target island.

# Standard Input

In the first line of input there is an integer $T$, which indicates there are $T$ test cases in the input.

For each test case, the first line contains two integer $n$($2\leq n\leq 1000$), $m$($1\leq m\leq 100000$), meaning there are $n$ islands and $m$ pairs island where stalkers can blink. Then $m$ lines followed, each line contain three integer $u$, $v$, $w$, ($1\leq u, v\leq n$), ($0< w \leq 1000000$), which means a stalker can blink from $u$ to $v$ or $v$ to $u$, and the distance is $w$. Then a single line contains a integer $Q$($1\leq Q\leq 3000$), which indicates there are $Q$ stalkers. Then $Q$ lines followed, each line contain three integer $a$, $b$, $c$, ($1\leq a, b\leq n$), ($0 < c \leq 1000000$), meaning this stalker start at island $a$ and target island is $b$, the distance it can blink is $c$. You can assume that the graph described in every test case is connected.

# Standard Output

For each test case, output $Q+1$ lines. First, output `Case #C: `, where $C$ is the number of test case, from $1$ to $T$. Then output $Q$ lines, if the $i\_{th}$ stalker can move to its target island using its ability for finite times, output `YES` in a single line, otherwise output `NO`.

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
3 3
1 2 2
1 3 3
2 3 2
2
1 3 1
1 3 2</td><td>Case #1:
NO
YES</td></tr></table>


# Constraints



# Note



# Source


