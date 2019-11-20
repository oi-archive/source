
# Content

Homura is a Mahou Shoujo, who enjoys playing games with her best friend Madoka. Today, they get a large house in the three-dimensional space whose length is a, width is b and height is c. This house contains $a \times b \times c$ small rooms(Each room is $1 \times 1 \times 1$). The rooms are recorded from (1,1,1) to (a,b,c). The coordinate of each dimension is the position of the room at each dimension. Initially, there is a stone in the room of (1,1,1). Homura and Madoka trys to move it to an adjacent room in turns. Homura moves it first. However, they can't move it to a room that once owned the stone. If a participant can not move it any more, then this participant loses. For the reason that Madoka is really clever, Homura wants you to help her to answer this question: 

Can Homura always win if she moves the stone first, while Modoka always uses the optimal strategy?

If two rooms (a1,b1,c1) and (a2,b2,c2) are adjacent, then |a1-a2|+|b1-b2|+|c1-c2| == 1 .

# Standard Input

The first line of the input file contains 3 integers a(the length of the house),b(the width of the house) and c(the height of the house)$(1\leq a,b,c\leq 2*10^9)$.

# Standard Output

The output file should contains only one line, which contains a "YES" or a "NO"(without quotation marks).

A "YES" means, Homura can win while Modoka always uses the optimal strategy.

A "NO" means, Homura might lose.

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
<tr><td>2 2 1</td><td>YES</td></tr><tr><td>3 3 1</td><td>NO</td></tr><tr><td>4 4 2</td><td>YES</td></tr></table>


# Constraints



# Note



# Source


