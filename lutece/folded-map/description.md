
# Content

Freddy's garden became so large that he needs a map to keep evidence of which vegetables are planted in what area. He ordered a high-quality map from the International CartographicPublishing Company (ICPC). Since the map has a large scale, it does not fit onto a single page and it has to be split into several rectangular tiles.

Even with a fixed tile size (determined by a page size) and map scale, the number of tiles may still differ by adjusting the position of the tile grid. Your task is to find the minimal number of tiles necessary to cover the whole region of Freddy's garden.

![.*](/source/lutece/folded-map/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzg2LzIwMTQwMzIyMjAxMDQwMTY0Mi5wbmc=.png)

Let's have a look at an example. The figure on the left shows $14$ map tiles covering a region. By adjusting the grid position a little bit, we may cover the same region with only $10$ tiles, without changing their size or orientation. 

Note that the tiles must be part of a rectangular grid aligned with the $x-axis$ and $y-axis$. That is, they touch each other only with their whole sides and cannot be rotated.

# Standard Input

The input contains several test cases. The first line of each test case contains four integer numbers: $A\_r$ , $A\_c$, $T\_r$ , and $T\_c$. $A\_r$ and $A\_c$ give the input image resolution in pixels ($1\leq A\_x\leq 1000$), while $T\_r$ and $T\_c$ is the size of one tile in pixels ($1\leq T\_x\leq 100$). The next $A\_r$ lines each contain $A\_c$ characters, each of them being either `X` (the pixel corresponds to a part of the garden to be covered by a tile) or `.` (the corresponding pixel is outside the garden and does not need to be covered). The region pixels form one connected region.

# Standard Output

For each test case, print one integer number -- the minimal number of tiles necessary to cover all pixels represented by `X`.

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
<tr><td>3 3 2 2
XXX
XXX
XXX
3 3 2 2
XX.
XXX
XXX
17 32 5 9
........XXXXXXXX................
........XXXXXXXX................
........XXXXXXXX................
........XXXXXXXXX...............
........XXXXXXXXXXXXXXX.........
........XXXXXXXXXXXXXXXXXXXX....
........XXXXXXXXXXXXXXXXXXXXX...
XXXXXXXXXXXXXXXXXXXXXXXXXXXXXX..
..XXXXXXXXXXXXXXXXXXXXXXXXXXXXX.
....XXXXXXXXXXXXXXXXXXXXXXXXXXX.
......XXXXXXXXXXXXXXXXXXXXXXXXX.
........XX..XXXXXXXXXXXXXXXXX...
.............XXXXXXXXXXXXXX.....
...............XXXXXXXXX........
................XXXXXXX.........
.................XXXXX..........
....................XXX.........</td><td>4
3
10</td></tr></table>


# Constraints



# Note



# Source


