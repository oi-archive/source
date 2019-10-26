
# Content

Winter is coming (or going? who can be sure these days) and a new king rises in the North. The
message travels quickly these days... That is why you, the rising king, have not much time left. You
need to rally your bannermen behind you. But one question seems harder to answer than you would
have first expected. How large of a kingdom can you claim and how many men should you send for?
Your advisors have taken a close look at the potential kingdom and have determined how many of
your bannermen would be required to fully defend any part of the map against your foes. As you
are a loving and caring king, you want to minimize the number of men that have to serve in your
army. To give your war council a fair chance of figuring out the best kingdom to defend, you have
to determine the size of the army that you will raise as soon as possible.

Luckily, armies are not that advanced yet. You will only have to defend against armies moving
horizontally or vertically (an army cannot pass but your bannermen diagonally). Your kingdom
counts as defended, if there is not a single way to reach your castle, starting anywhere outside of
the map, without passing to a fully defended area. Squares on the map labeled $0$ represent high
mountains, or walls, no one would ever be foolish enough to climb. You can assume to be save from
invasion without sending any bannermen to defend them. Since you are uncertain about what lurks
behind the wall (or in our case the borders of the map), you have to assume the worst and plans as
if you would never be able to hold any position outside of the given map.

![201308010108028531.png](/source/lutece/the-king-of-the-north/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTkvMjAxMzEyMjkwMDUxMTAxNjQzLnBuZw==.png)

*Illustration of the sample input — the kingdom can be defended with a minimal army of $37$
bannerman, located at the cross-marked positions. The kingdom itself is illustrated using a tiling
pattern. Note that you do not have to find out about the kingdom, or the position of you bannermen.
These questions are to be figured out by your war council.*

# Standard Input

The input is given in the form of the (rectangular) strategic map which your advisors came up with.
Every square in map is assigned a number of bannermen which would be required to defend the
position against any potential army. The map is formatted as follows: In a first line you are given
to integers $R$ and $C$, $3\leq R,C\leq 300$, specifying the dimensions of the map. This line is followed by
$R$ lines, each containing $C$ integers $0\leq c_i\leq 100000$, the number of bannermen necessary to defend
each square. Finally, you are given $0 < r < R−1$ and $0 < c < C−1$, the position of your own castle
on the map.

# Standard Output

Output an integer on a single line, the smallest possible army you would require to defend any
kingdom.

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
<tr><td>7 8
42 42 0 0 0 0 0 16
42 11 14 42 42 42 10 16
42 0 42 42 42 42 0 16
42 0 42 42 42 42 0 42
42 0 42 42 42 42 0 42
42 11 42 42 42 5 5 42
42 42 0 0 0 42 42 42
3 4</td><td>37</td></tr></table>


# Constraints



# Note



# Source


