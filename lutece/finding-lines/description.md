
# Content

Annabel and Richard like to invent new games and play against each other. One day Annabel has a new game for Richard. In this game there is a game master and a player. The game master draws n points on a piece of paper. The task for the player is to find a straight line, such that at least p percent of the points lie exactly on that line. Richard and Annabel have very good tools for measurement and drawing. Therefore they can check whether a point lies exactly on a line or not. If the player can find such a line then the player wins. Otherwise the game master wins the game.

There is just one problem. The game master can draw the points in a way such that it is not possible at all to draw a suitable line. They need an independent mechanism to check whether there even exists a line containing at least p percent of the points, i.e., $⌈ n⋅p/100⌉$ points. Now it is up to you to help them and write a program to solve this task.

# Standard Input

The input consists of:

one line with one integer $n\ (1≤n≤10^5)$, the number of points the game master has drawn;  
one line with one integer $p \ (20≤p≤100)$, the percentage of points which need to lie on the line;  
n lines each with two integers $x$ and $y \ (0≤x,y≤10^9)$, the coordinates of a point.

No two points will coincide.

# Standard Output

Output one line containing either `possible` if it is possible to find a suitable line or `impossible` otherwise.

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
55
0 0
10 10
10 0
0 10
3 3</td><td>possible</td></tr><tr><td>5
45
0 0
10 10
10 0
0 10
3 4</td><td>impossible</td></tr></table>


# Constraints



# Note

![title](/source/lutece/finding-lines/img/aHR0cHM6Ly9oZXJhbm8uZ2l0aHViLmlvL2ltYWdlcy9MdXRlY2UvMTExNy5wbmc=.png)

# Source


