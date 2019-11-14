
# Content

Sometimes I just need to manouver a baby penguin as quickly as possible through a maze, so it can find the fish someone has hidden inside. I have taught the penguin to be proficient with a compass, and can thus give it instructions `E`, `N`, `W` and `S`. The penguin's maze also has an extra feature: at some of the tiles are pressure plates that cause a $90$ degree counter-clockwise rotation of the whole iceberg on which the maze is located, when the penguin steps on one of them. The penguin is oblivious to this, as it rotates along with the iceberg. The compass needle, however, doesn't rotate along with the iceberg, and thus I have to modify my instructions whevenever such a pressure plate is activated. In the long run, I think this will give me a headache, so please, can you write a program to help me out?
Fortunately the maze always has exactly one path from the starting tile to the goal tile. Between each pair of tiles there exists exactly one path, and the starting tile will never contain a pressure plate.

# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. Each test case begins with a line containing two integers $X$, $Y$ - the size of the maze in the $X$ and $Y$ directions, and another line containing $4$ integers $p\_x$, $p\_y$, $g\_x$, $g\_y$ - the penguin's starting coordinates and the goal tile coordinates. Then follow $Y$ lines with $X$ characters each, where each character represents a single tile of the labyrinth as a base-$32$ number $(0,1\cdots 9, A,B,\cdots ,V)$. This number is the sum of the features the tile contains: If the tile has an east-going passage, $1$ is added to the sum. If the tile has a north-going passage,$2$ is added. For west-going passages $4$ is added, and for south-going ones $8$. In addition,if the tile contains a pressure plate, $16$ (or $G$) is added to the sum. Thus e.g. a tile value of $H$ (or $17$) means the tile has an east-going passage and a pressure plate.

# Standard Output

For each test case, output a single line with the compass instructions you will have to give your penguin to guide it along the shortest path to the tile where the sh can be found,assuming each instruction makes it move exactly one tile in the given direction.

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
<tr><td>1
2 3
0 0 1 2
9C
AQ
22</td><td>ESE</td></tr></table>


# Constraints



# Note

$0 < T \leq 100$

$0 < X \leq 500$

$0 < Y \leq 500$

$0 \leq p\_x, g\_x < X$

$0 \leq p\_y, g\_y < Y$

# Source


