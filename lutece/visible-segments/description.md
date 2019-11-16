
# Content

The central problem to computer graphics is rendering, where we only display visible objects for a given viewpoint. The problem in general, in three dimension world with arbitrary shape, is very difficult. As a student in college, you are encouraged to study some simpler cases at first.

Here we describe a special case of visibility problem. The scenario is restricted to a plane, and the object is only segment. Initially, lots of disjoint segments are placed in the plane arbitrarily. The viewpoint $p$ is fixed at the origin (i.e. $(0, 0)$), and doesn’t lie on any of the segments. Our task is to determine all the segments we can see from $P$. More precisely, a segment $S$ can be seen from $P$ if and only if there exists a point $q$ on $S$, the segment $\overline{pq}$ doesn’t intersect any segment $S’$ other than $S$. For example, the following figure has three non-visible segments from $p$, they are $L\_1$, $L\_3$ and $L\_0$.

![.*](/source/lutece/visible-segments/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTIyLzIwMTQwMjAxMTIzNjAxNzk4NS5wbmc=.png)

# Standard Input

The first line contains one integer $n$ ($0 < n \leq 100,000$), which is the number of segments. Followed are $n$ lines, where each line contains four integers $x\_1$, $y\_1$, $x\_2$, $y\_2$ ($-10,000 \leq x\_1, y\_1, x\_2, y\_2 \leq 10,000$) to represent two end points $(x\_1, y\_1)$ and $(x\_2, y\_2)$ of a segment.

# Standard Output

List all visible segments in ascending order (each one in a line, index starts from $0$).

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
1 1 2 2
-2 -4 1 -4
-1 -2 2 -2
-3 0 0 3</td><td>2
3</td></tr></table>


# Constraints



# Note

1. Given any segment $S$, whose two ends are $v\_1$ and $v\_2$. $S$ is invisible to $p$ if $p$, $v\_1$ and $v\_2$ are collinear;
2. Given any two segments $S\_1$ and $S\_2$, $v\_1$ is one of $S\_1$’s end points, and $v\_2$ is one of $S\_2$’s. If $v\_2$ is on the line of $\overline{pv\_1}$, we say $v\_2$ is not visible to $p$.

You can notice these two cases in the figure; they are $L\_1$ and $L\_3$ respectively.

# Source


