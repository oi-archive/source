
# Content

Smart phone is one of the most fashion hi-tech things today, and the most profitable. Invited by the Pakiistanii air force, wolf5x joined their project that is aiming at developing a brand new smart phone to compete with IPhone (Tomato says the IPhone he sells is cheap and powerful, so wolf5x wants to design a better one!). Its name will be PAC-Phone!
Now wolf5x is busy at designing a face recognition system, which can tell whether the picture taken by the camera on the phone belongs to the same person as the one stored in the database. It does the comparison in an ordinary way: First the system calculates some feature values of each picture and generates a new picture with points (no colors, no lines, just black points) for it. Then it compares whether the two newly-generated pictures are similar.

The work is almost finished; only the comparison module needs to be done. But wolf5x is not good at designing such an algorithm, so he turns to you for help. You can regard a picture as a set of points in the xOy plane. Two pictures are similar if and only if one set of points can be transformed into the other one by applying finite times the operations listed below:
1. Translation. Move each point in the set from $(X\_i, Y\_i)$ to $(X\_i+DX, Y\_i+DX)$, where $(X\_i, Y\_i)$ is the original coordinate of the $i\_{th}$ point.
2. Scaling. Change each point’s coordinate from $(X\_i, Y\_i)$ to $(k\times X\_i, k\times Y\_i)$
3. Rotation. Rotate each point clockwise around the Origin through a same angle.

Please help him write this module. To test whether it works, you’ll be given some test data. Use your program to determine whether the two given sets are similar.

# Standard Input

There are multiple cases. First line contains a single integer $T$, the number of cases.

Each case begins with an integer $N$, the number of points of each set.

Then follow $N$ lines each containing two real numbers $X\_i$ $Y\_i$, the coordinate of the $i\_{th}$ point in the first set.

Then follow $N$ lines each containing two real numbers $X\_i$ $Y\_i$, the coordinate of the $i\_{th}$ point in the second set.

The input guarantees that $T\leq 20$, $-20000 \leq X\_i, Y\_i \leq 20000$. For $90\%$ cases, $N \leq 1000$. For all the cases, $1 \leq N \leq 20000$.

# Standard Output

One case per line. First print `Case #i: `, where $i$ is the case number. Then `YES` if two sets are similar, otherwise `NO`.

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
4
0 0
1 1
0 1
1 0
0.5 0.5
1.5 -2.5
4.5 -1.5
3.5 1.5
3
0 0
0 4
-3 0
0 0
0 3
4 3</td><td>Case #1: YES
Case #2: NO</td></tr></table>


# Constraints



# Note

For sample $1$, transform the first set by: rotate through $atan(3)$ rad $\rightarrow$ scale by $sqrt(10)$ $\rightarrow$ translate by $(0.5, 0.5)$. Note that the order the points are given doesn’t matter.

For sample $2$, you don’t have a mirror, so the first set can never be transformed into the second one.

# Source


