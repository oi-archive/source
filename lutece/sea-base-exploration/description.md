
# Content

When the scientists explore the sea base, they use a kind of auto mobile robot, which has the mission to collect the swatches of resource of the sea base. The collections of the resource are taken to the research ship and classified, and then the research ship goes back to the mainland -- the research centre where scientists can do further research.

The robots have equipments to collect and store the resource, but the equipments have limited capability. Only a small quantity of each kind of recourse is enough for scientific research. So, once the robot has collected one kind of resource, it needs not to collect more. The capability of the robot is fixed and the same as the number of kinds of resource the scientists have already known. So, the robot will collect a list of resource and come back with fruitful results. The resource is buried beneath the surface of the sea base, and the quantity is always enough for the robot to collect if the map indicates that there are some. If the robot doesn't want to collect the resource underneath its location, it can leave it ignored and pass the square freely.

The robot needs a unit electric power to move from a square to another when its container is vacant and only can it move to a square adjacent to it. It needs $A\_i$ units to dig and collect the resource marked $i$. Each of the resource has its weight, so the robot costs $B\_i$ units of power per move after it has collected resource $i$.

During the sea base walk, the robot carries a battery with a certain units(P) of electric power, and the power of it need to be economized, the scientists ask you to calculate the minimal quantity of power the robot will use to collect all kinds of resource and back to the ship.

# Standard Input

The first line of the input is an integer $T$ which indicates the number of test cases.

Each of the cases tells the map of the sea base you will explore, The first line will be the $M, N, K, P, M$ ($1\leq M\leq 20$) is the width of the area, $N$ ($1\leq N\leq 20$) is the length of the area, and $K$ ($1\leq K\leq 10$) is the number of kinds of resource, $P$ is the certain capacity of the battery.

Then follows $M$ lines characters indicating the map, each line contains $N$ characters.

There are four kinds of characters, `.`, `*`, `#` and capital letters.

The symbol `.` indicate that free space. The `*` indicates where the research ship located, notice that once the robot moves back to this area, it will be fetched back to the main ship automatically. You can assume there is only one `*` on one map.The `#` indicates that the space is blocked of some reason, the capital letters indicate $K$ kinds of resource, and you can assume that there are always $K$ kinds of capital letters (alphabetically from $A$).

The next $K$ lines follows two integers each line, $A\_i$ and $B\_i$.

# Standard Output

For each input set output a number of the minimal quantity of power on one single line. Print a warning `Impossible` if the minimal quantity of power needed exceeds the capacity of the battery or it's impossible for the robot to accomplish the mission.

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
5 5 1 50
*....
##.##
A#.#A
.#.#.
.....
1 0</td><td>21</td></tr></table>


# Constraints



# Note

The data used in this problem is unofficial data prepared by pfctgeorge. So any mistake here does not imply mistake in the official judge data.

# Source


