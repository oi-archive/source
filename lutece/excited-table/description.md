
# Content

There is a table with $n$ legs. Because of the foolishness of the designer, the table may be unstable.

A leg can be describe as three integers $x,y,l$, while $(x,y)$ is its position on the tabletop and the leg is perpendicular to the tabletop with length $l$.

We define a direction of the table is stable if and only if it exists that three or more legs touch the floor and they are not on one plane, and the table can't be upside down.

A table is stable if and only if it has exactly one stable direction.

Because the tabletop is compact enough, the collision between the tabletop and the floor can be neglected.

In addition, the thickness of legs also should be neglected.

You should determine whether the table is stable.

# Standard Input

The first line contains one integer $n$.

Then $n$ lines follow, each with three integers $x,y,l$.

It is guaranteed that no two legs is on the same position.

$1\leq n\leq 2*10^5$

$0\leq |x|, |y|\leq 10^5$

$1\leq l\leq 10^5$

# Standard Output

If the table is stable, print `STABLE`; otherwise, print `UNSTABLE`.

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
<tr><td>4
1 1 1
-1 -1 1
-1 1 1
1 -1 1</td><td>STABLE</td></tr><tr><td>4
1 1 2
-1 -1 1
-1 1 1
1 -1 1</td><td>UNSTABLE</td></tr></table>


# Constraints



# Note

![title](/source/lutece/excited-table/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTMxMS8yMDE2MDQwMjEwNDA0NjU1NjQucG5n.png)

A stable direction of the table in sample 2.

# Source


