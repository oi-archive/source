
# Content

There are many round lakes in the new campus of UESTC. Some lakes completely belong to UESTC, but some lakes don't locate in UESTC absolutely. WCM likes going fishing. He often goes fishing on weekends. But Tom Riddle who is the local officer makes a law that all the students of UESTC can only fish in the lakes which completely locate in UESTC. Therefore, as for a round lake, WCM must be sure whether it locates in UESTC completely. Can you help him solve this problem?

To simplify the problem, the new campus of UESTC is supposed to be a rectangle. Given a rectangle and a circle, you should determine whether the circle is inside the rectangle completely. You can assume that the rectangle's sides are always parallel to $X$-coordinate axes or $Y$-coordinate axes.

# Standard Input

The input contains an integer $T$ on the first line, which indicates the number of test cases. Each test case consists of two lines. The first line contains four integers, $X_1$,$Y_1$,$X_2$,$Y_2$, ($-1000 \leq X_1,Y_1,X_2,Y_2 \leq 1000$), ($X_1,Y_1$) represents the coordinates of the lower-left vertex of the rectangle and ($X_2,Y_2$) represents the coordinates of the upper-right vertex of the rectangle. The second line contains three integers, $X$, $Y$, $R$, ($-1000 \leq X, Y \leq 1000, 0 < R \leq 2000$), ($X$, $Y$) represents the coordinates of the center of the circle, and $R$ represents the radius of the circle.

# Standard Output

For each test case, if the circle is inside the rectangle completely, then output `Just do it` on a line; otherwise, output `Don't get close to it` instead.

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
<tr><td>3
-2 -1 2 2
1 0 1
1 3 7 9
4 6 3
-5 6 3 10
2 7 5</td><td>Just do it
Just do it
Don't get close to it</td></tr></table>


# Constraints



# Note



# Source


