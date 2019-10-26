
# Content

In order to protect himself from evil bunnies, Freddy decided to install an automatic system to detect them in pictures from surveillance cameras. Sophisticated software detects important points in the picture and lines between them. Unfortunately, the terrain in the pictures is quite varied and lot of the points and lines are actually not bunnies.

You have made the following observation: Each bunny has four paws and a body joining them.Based on this observation, write a program to decide whether a given picture can possibly contain a bunny.

# Standard Input

The input contains several test cases. The first line of each test case contains two integers $n$ and $m$ ($0\leq n\leq 10,000$, $0\leq m\leq 20,000$), giving the number of points and lines in the image,respectively. Each of the m following lines contains two distinct integers $x$ and $y$ ($1\leq x, y\leq n$),indicating that the points $x$ and $y$ are directly joined by a line. You may assume that each pair of points is joined by at most one direct line and that no point is directly joined with itself.

# Standard Output

For each input instance, output `YES` if the picture can contain a bunny, and `NO` otherwise.The picture can contain a bunny if it is possible to remove some of the points and lines so that the resulting image is connected and has exactly $4$ paws.

The image is said to be connected if (and only if ) each two points are joined with each other by one or more successive lines. A paw is a point which is directly joined with exactly one other point.

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
<tr><td>2 1
1 2
5 4
1 2
1 3
1 4
1 5</td><td>NO
YES</td></tr></table>


# Constraints



# Note



# Source


