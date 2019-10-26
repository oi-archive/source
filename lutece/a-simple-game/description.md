
# Content

Alice likes to play games. One day she meets such a game. There are $N$ `*` $N$ switches arranged in an $N$ `*` $N$ array. Pressing a switch would change its state, from `off` to `on` or from `on` to `off`. In addition, if a switch at row r and column c is pressed, then all switches with coordinate ($k$ `*` $r$, $k$ `*` $c$) will change state, with integer $k > 1$. Initially all switches are `off`.

![.*](/source/lutece/a-simple-game/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNjMvMjAxNDAxMDExMTMzMDE2OTgzLmpwZw==.jpg)

For example, in the picture above, white buttons represent switches turned `off` and colored ones represent switches turned `on`. Initially all buttons are white. If the button at ($2$,$2$) is pressed, then buttons at ($2$,$2$), ($4$,$4$) will change state(represented with orange color). And if one presses the button ($2$,$1$), buttons at ($2$,$1$) and ($4$,$2$) will change from `off` to `on`(represented with gray color).

The goal of the game is to turn `on` all the switches (i.e. when you finish the game, all the switches must be at the state of `on`) and the player must do that with as few presses as possible. Now Alice would like your help.

# Standard Input

The first line of input file is an integer $T$, the number of test cases. $T$ lines follow, each contain an integer $N$, the dimension of the array in one game.

$1\leq T \leq 100, 1\leq N \leq 10000$

# Standard Output

Output consists of T lines. Each line contains an integer, the minimum number of presses for the corresponding test case.

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
2
3</td><td>3
7</td></tr></table>


# Constraints



# Note

For test case $1$, press ($1$,$1$) ($1$,$2$) ($2$,$1$). 
For test case $2$, press ($1$,$1$) ($1$,$2$) ($1$,$3$) ($2$,$1$) ($2$,$3$) ($3$,$1$) ($3$,$2$).

# Source


