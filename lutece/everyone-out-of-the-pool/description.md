
# Content

When you rent a table at a pool hall, the proprietor gives you a $4$-by-$4$ tray of $16$ balls, as shown in Figure (a) below. One of these balls, called the "cue ball", is white, and the remaining $15$ are numbered $1$ through $15$. At the beginning of a game,the numbered balls are racked up in a triangle (without the cue ball), as shown in Figure (b).

![title](/source/lutece/everyone-out-of-the-pool/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzI4LzIwMTQwOTAyMTMyNTEwMDYxMzcucG5n.png)

Now imagine other pool-like games where you have a cue ball and x numbered balls. You'd like to be able to rack up the $x$ numbered balls in a triangle, and have all $x+ 1$ balls perfectly fill a square $m$-by-$m$ tray. For what values of $x$ is this possible? In this problem you'll be given an lower bound $a$ and upper bound $b$, and asked how many numbers within this range have the above property.


# Standard Input

Input for each test case will one line containin two integers $a$ $b$, where $0 < a < b \le 10^9$. The line `0 0` will follow the last test case.

# Standard Output

For each test case one line of output as follows:
`Case n: k`
if there are $k$ integers $x$ such that $a < x+ 1 < b$, $x$ balls can be racked up in a triangle, and $x + 1$ balls fill a square tray.

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
<tr><td>15 17
14 16
1 20
0 0</td><td>Case 1: 1
Case 2: 0
Case 3: 2</td></tr></table>


# Constraints



# Note



# Source


