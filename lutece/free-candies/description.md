
# Content

Little Bob is playing a game. He wants to win some candies in it - as many as possible.

There are $4$ piles, each pile contains $N$ candies. Bob is given a basket which can hold at most $5$ candies. Each time, he puts a candy at the top of one pile into the basket, and if there're two candies of the same color in it , he can take both of them outside the basket and put them into his own pocket. When the basket is full and there are no two candies of the same color, the game ends. If the game is played perfectly, the game will end with no candies left in the piles.

For example, Bob may play this game like this ($N=5$):

![title](/source/lutece/free-candies/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNDI3LzIwMTQwODE0MTkzOTI5MzA1MTAucG5n.png)

Note that different numbers indicate different colors; there are $20$ kinds of colors numbered $1\cdots 20$.

'Seems so hard...' Bob got very much puzzled. How many pairs of candies could he take home at most?

# Standard Input

The input will contain no more than $10$ test cases. Each test case begins with a line containing a single integer $n$ ($1\leq n\leq 40$) representing the height of the piles. In the following $n$ lines, each line contains four integers $x\_{i\_1}$, $x\_{i\_2}$, $x\_{i\_3}$, $x\_{i\_4}$ (in the range $1\cdots 20$). Each integer indicates the color of the corresponding candy. The test case containing $n=0$ will terminate the input, you should not give an answer to this case.

# Standard Output

Output the number of pairs of candies that the cleverest little child can take home. Print your answer in a single line for each test case.

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
<tr><td>5
1 2 3 4
1 5 6 7
2 3 3 3
4 9 8 6
8 7 2 1
1
1 2 3 4
3
1 2 3 4
5 6 7 8
1 2 3 4
0</td><td>8
0
3</td></tr></table>


# Constraints



# Note



# Source


