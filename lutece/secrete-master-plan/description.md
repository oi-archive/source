
# Content

Master Mind KongMing gave Fei Zhang a secrete master plan stashed in a pocket. The plan instructs how to deploy soldiers on the four corners of the city wall. Unfortunately,
when Fei opened the pocket he found there are only four numbers written in dots on a piece of sheet. The numbers form a $2\times 2$ matrix, but Fei didn't know the correct
direction to hold the sheet. What a pity!

Given two secrete master plans. The first one is the master's original plan. The second one is the plan opened by Fei. As KongMing had many pockets to hand out, he might give
Fei the wrong pocket. Determine if Fei receives the right pocket.

![title](/source/lutece/secrete-master-plan/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTIxNS8yMDE1MTAyMDE3MTgwNTY2MTMucG5n.png)

# Standard Input

The first line of the input gives the number of test cases, $T$($1\leq T\leq 10^4$). $T$ test cases follow. Each test case contains $4$ lines. Each line contains two integers
$a\_{i0}$ and $a\_{i1}$ ($1\leq a\_{i0}, a\_{i1}\leq 100$). The first two lines stands for the original plan, the $3\_{rd}$ and $4\_{th}$ line stands for the plan Fei opened.

# Standard Output

For each test case, output one line containing `Case #x: y`, where $x$ is the test case number (starting from $1$) and $y$ is either "`POSSIBLE`" or "`IMPOSSIBLE`"
(quotes for clarity).

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
<tr><td>4
1 2
3 4
1 2
3 4

1 2
3 4
3 1
4 2

1 2
3 4
3 2
4 1

1 2
3 4
4 3
2 1</td><td>Case #1: POSSIBLE
Case #2: POSSIBLE
Case #3: IMPOSSIBLE
Case #4: POSSIBLE</td></tr></table>


# Constraints



# Note



# Source


