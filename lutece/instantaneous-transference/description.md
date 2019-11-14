
# Content

It was long ago when we played the game Red Alert. There is a magic function for the game objects which is called instantaneous transfer. When an object uses this magic function, it will be transferred to the specified point immediately, regardless of how far it is.

Now there is a mining area, and you are driving an ore-miner truck. Your mission is to take the maximum ores in the field.

The ore area is a rectangle region which is composed by $n \times m$ small squares, some of the squares have numbers of ores, while some do not. The ores can't be regenerated after taken. 

The starting position of the ore-miner truck is the northwest corner of the field. It must move to the eastern or southern adjacent square, while it can not move to the northern or western adjacent square. And some squares have magic power that can instantaneously transfer the truck to a certain square specified. However, as the captain of the ore-miner truck, you can decide whether to use this magic power or to stay still. One magic power square will never lose its magic power; you can use the magic power whenever you get there.

# Standard Input

The first line of the input is an integer $T$ which indicates the number of test cases.

For each of the test case, the first will be two integers $N, M (1 \leq N, M \leq 40)$.

The next $N$ lines will describe the map of the mine field. Each of the N lines will be a string that contains $M$ characters. Each character will be an integer $X (0 \leq X \leq 9)$ or a `*` or a `#`. The integer $X$ indicates that square has $X$ units of ores, which your truck could get them all. The `*` indicates this square has a magic power which can transfer truck within an instant. The `#` indicates this square is full of rock and the truck can't move on this square. You can assume that the starting position of the truck will never be a `#` square.

As the map indicates, there are $K$ `*` on the map. Then there follows $K$ lines after the map. The next $K$ lines describe the specified target coordinates for the squares with `*`, in the order from north to south then west to east. (the original point is the northwest corner, the coordinate is formatted as north-south, west-east, all from $0$ to $N - 1,M - 1$).

# Standard Output

For each test case output the maximum units of ores you can take.

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
2 2
11
1*
0 0</td><td>3</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by allenlowesy. So any mistake here does not imply mistake in the offcial judge data.

# Source


