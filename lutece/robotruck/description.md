
# Content

This problem is about a robotic truck that distributes mail packages to several locations in a factory. The robot sits at the end of a conveyer at the mail office and waits for packages to be loaded into its cargo area. The robot has a maximum load capacity, which means that it may have to perform several round trips to complete its task. Provided that the maximum capacity is not exceeded, the robot can stop the conveyer at any time and start a round trip distributing the already collected packages. The packages must be delivered in the incoming order.

The distance of a round trip is computed in a grid by measuring the number of robot moves from the mail office, at location $(0,0)$, to the location of delivery of the first package, the number of moves between package delivery locations, until the last package, and then the number of moves from the last location back to the mail office. The robot moves a cell at a time either horizontally or vertically in the factory plant grid. For example, consider four packages, to be delivered at the locations $(1,2),(1,0), (3,1)$ and $(3,1)$. By dividing these packages into two round trips of two packages each, the number of moves in the first trip is $3+2+1=6$ and $4+0+4=8$ in the second trip. Notice that the two last packages are delivered at the same location and thus the number of moves between them is $0$.

Given a sequence of packages, compute the minimum distance the robot must travel to deliver all packages.

# Standard Input

A positive integer $P$ in a single line followed by a sequence of $P$ test cases. Each test case consists of a line containing one positive integer $C$, not greater than $100$, indicating the maximum capacity of the robot, a line containing one positive integer $N$, not greater than $100,000$, which is the number of packages to be loaded from the conveyer. Next, there are $N$ lines containing, for each package, two non-negative integers $x,y$ ($x\leq 1000$, $y\leq1000$) to indicate its delivery location in the grid, and a non-negative integer to indicate its weight. The weight of the packages is always smaller than the robot's maximum load capacity. The order of the input is the order of appearance in the conveyer.

# Standard Output

One line containing the case number and one integer representing the minimum number of moves the robot must travel to deliver all the packages.

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
10
4
1 2 3
1 0 3
3 1 4
3 1 4</td><td>Case 1: 14</td></tr></table>


# Constraints



# Note



# Source


