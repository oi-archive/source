
# Content

In a three-dimensional space there are $n$ points ($2 \leq n \leq 2\times10^5$), where the point $P$ is on the z-coordinate axis, i.e. its coordinate is $P(0,0,z_0)$, and $z_0$ is an integer, the coordinates of the other points are given in floating points. Of these points, at least $(n-1)/2$ (rounded up) are on the prongs of a triangular cone $PABC$ with $P$ as its apex ($A$, $B$ and $C$ are not necessarily included in the given $n$ points) in addition to point $P$. The bottom triangle $\triangle ABC$ is an equilateral triangle perpendicular to the z-coordinate axis, and its center is directly below $P$ (i.e., the triangle's center coordinate is $(0,0,z_1)$ and $z_1 < z_0$). The side length of this equilateral triangle is also an integer. And, there are at least $(n-1)/4$ (rounded up) points on the sides of this triangle (with vertices). Your task is simple, after knowing the coordinates of these $n$ points, calculate the length of the sides of the bottom triangle, and then find the number of points on the prongs connecting $P$ to the bottom ($PA$, $PB$, $PC$, **without endpoints**) out of the given $n$ points, and the number of points on the sides of the bottom triangle ($\triangle ABC$, **with vertices**).

# Standard Input

The first line, an integer $n$ ($2\leq n \leq 2\times 10^5$), indicates the number of points.

The second line, an integer $z_0$, indicates the z-coordinate of $P$.

The following $n-1$ lines, each with three floating-point $x,y,z$( $-2e5 \leq x,y,z \leq 2e5$), denote a point whose coordinates are $(x,y,z)$.

Floating points retain 9 decimal places, ensuring that any two points are not directly separated by less than $1 \times 10^{-6}$.

# Standard Output

Three integers. The length of the sides of the bottom triangle, the number of points on the prongs connecting $P$ to the bottom triangle ($PA$, $PB$, $PC$, **without endpoints**) out of the given $n$ points, and the number of points on the sides of the bottom triangle ($\triangle ABC$, **with vertices**).

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
2
1.554784407 -1.154700538 0.100000000</td><td>4 0 1</td></tr></table>


# Constraints



# Note



# Source


