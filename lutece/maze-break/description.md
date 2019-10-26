
# Content

One day, TheBeet found that there is a maze in ArXoR's company, deeply hiden in underground. Unfortunately, he was caught while tring to explore it. ArXoR was always a good man, and was going to thrown the curious man into the maze without any food and water.

Of course, TheBeet wanted to escape.

The maze consists $n$ rooms numbered $0, 1, \cdots n - 1,$ and $m$ directed tunnels between rooms. Each tunnel has a color and no two of outcoming tunnels of a room have the identical color. There is totally $k$ colors, which is numbered $0, 1, \cdots k - 1$.

Before being thrown into the maze, TheBeet was able to dig only one hole to only one room as the exit. But he would never know which room ArXoR would thrown he into. When he was in the maze, he can not recognize which room he was standing in. All he can know is the colored outcoming tunnels of the room where he stood in.

In order to escape, TheBeet must make a sequence of colors. If there is an outcoming tunnel with the same color as the current color in the sequence, he would run through the tunnel, otherwise he would stand still and examine the next tunnel color in the sequence.

By following the whole sequence, if he can stand in the room where he had dig a hole to, he can escape, otherwise, he failed in escaping.

Your task is to computer the minimal length of the sequence of colors which would guarantee TheBeet's escape.

# Standard Input

The input contains a single test case.

The first line contains three integers presenting $n m k. (1 \leq n \leq 30, 1 \leq m \leq n \times k, 1 \leq k \leq 10)$

Then m lines follow, each of them contain three integer $i$ $j$ $c$, which means there is a tunnel of color $c$ from room $i$ to room $j, (0 \leq i < n, 0 \leq j < n, i != j, 0 \leq c < k)$

# Standard Output

Output a single line containing an integer indicating the minimal length of the sequence of colors which would guarantee TheBeet's escape.

If such sequence doesn't exist, output `-1`.

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
<tr><td>9 8 5
0 1 0
1 3 2
5 4 4
4 3 1
7 6 4
6 3 2
8 2 3
2 3 1</td><td>5</td></tr></table>


# Constraints



# Note

TheBeet can always escape through room $3$ by following the color sequence $43012$ no matter which room he was thrown into, and no other shorter sequence exsists.

# Source


