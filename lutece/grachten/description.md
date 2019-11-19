
# Content

Damn! I did not only oversleep (and today is *the* contest day!) but
I also got stuck somewhere in Delft on my way from the hotel to the contest
site. Everywhere around me are grachten, these city-canals that are part of
many cities in the Netherlands. I am in a bit of hurry, because the
NWERC contest starts in a few minutes.

To make matters even worse, some bridges in Delft are closed due to a cycling
race through the city. Thus, I decided to jump over some of the grachten
instead of searching for open bridges.

Everyone knows that computer scientists like me are good at algorithms but
not very good athletes. Besides, I am a bit faint-hearted and don't want to get
wet. So I need your help to calculate the distance I have to
jump over a gracht.

Luckily, I did attend the excursion in Delft city center yesterday, where I
learned that all paving stones in Delft are squares and have the same size.
This way, I can do some measurements on my side of the gracht (my units are
paving stones):

<p class="text-center"><img src="/source/lutece/grachten/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODk0LzIwMTQwNTIzMTMwMTU5MjA4MTMucG5n.png" alt="title"></p>
*Illustration of first sample input.*

I walked from point $C$ to point $D$ via points $A$ and $B$ while
counting the paving stones.

Points $A$ and $C$ are always on the edge of the gracht.
Points $B$ and $D$ have the same distance to the gracht.
The target point $T$ is always on the edge of the other side of the canal;
    it is the intersection point of the line through $B$ and $A$, and the line through $D$ and $C$.
The angle between $AT$ and $AC$ is $90$ degrees, and the two edges of the canal are parallel lines.

Please calculate the distance between $A$ and $T$ (necessary jump
distance) for me.

# Standard Input

For each test case, the input consists of one line containing three positive integers that
specify the distances between $A$ and $B$, $A$ and $C$, and $B$ and $D$.

You may safely assume that no distance is larger than $1000$ and the distance
between $B$ and $D$ is larger than the distance between $A$ and $C$.

# Standard Output

For each test case, print one line of output: the distance between $A$ and $T$ as a `reduced`
fraction (i.e.\ remove all common factors of numerator and denominator).

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
<tr><td>5 3 7
5 3 8
1 2 3
23 42 47
500 500 1000
1 1 1000</td><td>15/4
3/1
2/1
966/5
500/1
1/999</td></tr></table>


# Constraints



# Note



# Source


