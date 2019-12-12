
# Content

The Rubik's Cube is one of the most famous mechanical puzzles in the world. In a classic $3\times 3\times 3$ Rubik's Cube, each of the six faces is covered by nine stickers, among six solid colors (traditionally white, red, blue, orange, green and yellow).

![.*](/source/lutece/rubik-s-cube/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTAzLzIwMTQwMTI5MDAzNzQyMjAyNS5wbmc=.png)

We can name the six faces as `F`(Front), `B`(Back), `U`(Up), `D`(Down), `L`(Left), `R`(Right).

![.*](/source/lutece/rubik-s-cube/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTAzLzIwMTQwMTI5MDAzNzQ4MDUzNi5wbmc=.png)

A letter followed by a prime symbol `'` means rotating the corresponding face $90$ degrees in counterclockwise direction, while a letter without a prime symbol denotes a clockwise turn. A letter followed by a `2` denotes two turns, in other words, a $180$-degree turn.

One day, Hongshu performed a sequence of moves, which left the puzzle in a scrambled state. After seeing that, Hongshu began to wonder whether repeating the exact same sequence of moves over and over again would bring the cube back to its initial state --- that is, each of the small stickers must return to the exact same place where it started. Could you help him?

# Standard Input

One integer $T$ (about $10000$) on the first line indicates the number of cases.

Then followed by $T$ cases, every case contains a single line which is a space-separated list of rotations (no more than $100$ rotations) Hongshu performed.

# Standard Output

For each case, print an integer $X$ in a single line, which is the smallest number of rounds Hongshu need to perform all the rotations to bring each sticker to where it was in the beginning(including the first round). If no such $X$ exists, print $-1$ instead.

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
F2
F B'</td><td>2
4</td></tr></table>


# Constraints



# Note

A brute force algorithm may lead to `Time Limited Exceed`.

# Source


