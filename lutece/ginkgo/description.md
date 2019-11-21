
# Content

You know, this year's UESTC programming contest is coming. After the register time, we learn that the number of participants exceeded $600$! No doubt every former and current UESTC ACMer is waiting long for this moment. They have imagined thousands of balloons simultaneously rise up for several times, but now, the dream comes true!

After the opening ceremony, the organizers started to debate on the holding place. One of them, Richard, offered an idea:

"It's a historic time, right? So, why not make the tournament hall in the ginkgo forest?"

What an attractive option! Running a competition in the open air could relieve the pressure, also we make all UESTCers experience a real ACM/ICPC contest!

The committee finally approved this suggestion, and let Richard submit a detailed plan first. After a short while, Richard found he was in trouble with enclosing an empty ground due to his poor geometry knowledge. So, he posted this problem in hopes that any smart guy could help him (He will offer you a balloon as your prize, ^_^).

Richard's problem is: During the final phase, as all teams are scattered in the forest, they are permitted to select any place they like in the forest. To restrict the participants, we use string to enclose a polygon ground with all teams setting inside or on the boundary of this polygon. We fasten the string to the trees, so we should pick some trees as the vertices of this polygon.

The problem is, Richard wanted to choose the fewest trees to finish this task. It's hard, and he has worked on this for days. However, you may know an efficient solution for this puzzle.

# Standard Input

The first line of the input contains one integer $T$, which indicate the number of test cases.

For each case, the first line contains two numbers $n$ ($3\leq n\leq 500$) and $m$ ($3\leq m\leq 500$), standing for n teams and m trees. The next $n$ lines contain the location of the $n$ teams, each line has two real numbers $x$ and $y$, describing the $x$ and $y$ coordinates. The next $m$ lines contain the location of the $m$ trees, and also two real numbers $x$ and $y$ on each line describe the coordinate.

To simplify the problem, the absolute values of all $x$-coordinates and $y$-coordiantes are less than $10001$.

# Standard Output

Only one number, indicating the fewest trees used to form a satisfied polygon; or $-1$ meaning there's no such polygon.

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
<tr><td>2
6 5
1 3
4 6
5 4
4 1
3 5
2 3
1 6
6 6
6 1
7 4
1 1
2 4
3 1
3 3
1 1
2 2
3 3
5 1</td><td>4
3</td></tr></table>


# Constraints



# Note

1. Assume $v\_1$ and $v\_2$ are two vertices of your polygon, and there's another vertex $v\_3$. If $v\_3$ lies on the line formed by $v\_1$ and $v\_2$, you don't need to take $v\_3$ into account (See Sample $2$ for clarification).
2. Of course, no two teams take a seat in the same place, and no two trees are planted in the same place either.

# Source


