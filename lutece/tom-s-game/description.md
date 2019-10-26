
# Content

Tom is playing the following game on a computer. There are $101$ squares connected in a line, with the $i\_{th}$ square adjacent to the $(i-1)\_{th}$ one on its left and to the $(i+1)\_{th}$ on its right, for $1 \leq i \leq 99$, and the $0\_{th}$ and $100\_{th}$ square are the starting and finishing square, respectively.

![.*](/source/lutece/tom-s-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODIvMjAxNDAxMTMxNzIwMjc5NzExLmdpZg==.gif)

Initially Tom's character is at Square $0$. At each turn the computer throws a dice and produces a number $k$ between $1$ and $6$, inclusive. Tom's character will then go $k$ steps forward, i.e. from Square $i$ to Square $i + k$. Once the character reaches the finishing square $100$, the game ends and Tom wins. If the character goes more than needed steps toward the finishing square, he will be wrapped around. For example, if the character is at $98$ and computer throws $5$, then he will end up at $97$($98\rightarrow 99\rightarrow 100\rightarrow 99\rightarrow 98\rightarrow 97$).

In addition, some squares are special. There are $3$ types of special squares:
1. Advance $k$. When the character reaches this type of square, he will go $k$ more steps forward from it. Note he will still be wrapped around toward the end of the path. For example, if Square $98$ is `Advance 3` , then if the character reaches this square, he will end up at $99$($98\rightarrow 99\rightarrow 100\rightarrow 99$).
2. Back $k$. When the character reaches this type of square, he will go $k$ steps back from it, i.e. from $i$ to $i - k$. if $i - k < 0$, the character will end up at $0$.
3. Goto $k$. When the character reaches this type of square, he will go to Square $k$.

In a single turn the character may encounter more than one special squares, and they will take effect one after another.

After playing the game for a while without victory, Tom begins to suspect that the computer cheats on the dice throwing so as to not let him win. So he writes a program and hacks into the random number generating module of the game. Now Tom can control in each turn what number the dice throwing will produce. Of course this number is still in the range $[1\cdots 6]$. To surprise his friends on how well he can play the game, Tom decides to control the dice throwing in each turn such that he can win the game in as few turns as possible.

Note that the special squares may be ill-designed such that Tom will never win the game no matter how he controls the output of the dice throwing.

# Standard Input

The first line is an integer $N$, number of special squares. Following $N$ lines each contain three integers, $s$, $t$ and $k$. $s$ is the index of the special square. $t$ is type of the square and is in the range $[0\cdots 2]$, with $0$, $1$ and $2$ stands for `Advance`, `Back` and `Goto` respectively. $k$ is the argument for this type, as described above.

* $1 \leq s \leq 99$, i.e. the staring and finishing squares will never be special.
* Each square can be at most one of the three special types.
* The $k$ for `Advance` and `Back` squares is in the range $[1\cdots 6]$.
* The $k$ for `Goto` squares is in the range $[0\cdots 100]$.
* If Square $i$ is `Goto k`, then $k$ will not be $i$.

# Standard Output

Output on a single line the minimum number of turns Tom needs to win the game, if he can control the output of the dice throwing in each turn. If Tom can never win the game, output $-1$.

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
<tr><td>0</td><td>17</td></tr><tr><td>1
2 2 99</td><td>2</td></tr><tr><td>6
1 0 1
2 0 1
3 0 1
4 0 1
5 0 1
6 1 5</td><td>-1</td></tr></table>


# Constraints



# Note

#####Sample Input/Output 1 Clarification

With no special squares, Tom can't play too many tricks. The best strategy for him is to throw $6$ in each turn except the last, where he should throw $4$.

#####Sample Input/Output 2 Clarification

Square 2 is special; it is `Goto 99`. Tom can throw $2$ in the first turn, which takes him to Square $99$. Then he throws $1$ and wins the game.

#####Sample Input/Output 3 Clarification

No matter what Tom throws in the first turn, his character will be trapped into an infinite loop($1\rightarrow 2\rightarrow 3\rightarrow 4\rightarrow 5\rightarrow 6\rightarrow 1$). So he can never win the game.

# Source


