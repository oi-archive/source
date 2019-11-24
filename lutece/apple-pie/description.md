
# Content

Apple pie is Hysramp's favorite snack for tasting so cloying, which usually formed in circular appearance. Although exotic and delicious, apple pie is not so abstruse of its cooking method. Just as the figure shows, looks pretty charming ,apple pie is often make of a big round bread and several pieces of apple slices.

However, what often discomfit Hysramp is, everyone may meet, mouth appears not big enough to touch any apple slices when eat the apple pie for the first bite. Now given the apple pie and the bite mark, you’re required to tell how many apple slices have Hysramp touched.

To simplify the problem, we do some reasonable assumptions. Apple pie (yellow part) and apple slices (red parts) on it all are exact circles. Each circle will be described by an $R$ for radius and $X$, $Y$ for centre. The bite mark on the apple pie must be a minor arc (the blue arc), which will be given by two points and a radius $r$. These two points will be guaranteed on the edge of apple pie, thus they (the two points) will be indicated by two degree $P$, $Q$, which is the degrees from the positive $X$-axis on coordinate system which the origin is on the apple pie's centre, just as illustrated below. 

![.*](/source/lutece/apple-pie/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTA1LzIwMTQwMTI5MTMzOTQ3ODEyMS5qcGc=.jpg)

#####Note:
1. Apple slices (the red parts) may not completely lie in the apple pie (the yellow part), if so, output `Bad Apple Pie`.
2. The apple slices (the red parts) may overlap on each other, but it doesn't matter.
3. The bite mark will always be a minor arc and Hysramp would never bite off the centre of the apple pie for some reasons.
4. Ex-tangency of a circle and arc also means `touch`, and in-tangency of two circles also means `include`. 

# Standard Input

The first line of the input contains one integer $T$, which indicate the number of test cases. Following each test case will be separated by a blank line.

For each test, the first line would be four integers, $R$, $X$, $Y$, $N$, separate by spaces, which are radius and centre coordinate of the apple pie (yellow), then followed by $N$ lines. Each line has three integers $r$, $x$, $y$, separate by spaces, describing the apple slices (red). The last line of each test case is $r$, $P$ and $Q$, in degree ($0\leq P, Q < 360$), which mentioned in the problem. And all data will be less than $5000$.

# Standard Output

One line for each test case, output `Bad Apple Pie` if any apple slices fails to lie completely in the apple pie, or write the number of apple slices Hysramp can touch with the given bite mark.

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
100 200 170 2
30 140 180
50 220 180
100 160 70</td><td>2</td></tr></table>


# Constraints



# Note



# Source


