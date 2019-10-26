
# Content

Parabola is very important in math, I believe every one of you should be very familiar with that.

A parabola on a $XOY$ plane can be expressed as $y = ax^2 + bx + c$ ($a\neq 0$) (Well, you can see we have simplified the problem a little bit...)

In this problem, a point $(x\_{i}, y\_{i})$ is said to be "inside a parabola", if such conditions holds:

If $a > 0$, then $y\_{i}\geq ax\_{i}^2 + bx\_{i} + c$.

If $a < 0$, then $y\_{i}\leq ax\_{i}^2 + bx\_{i} + c$.

Given two parabolas, one with $a > 0$, the other with $a < 0$, you need to find the `intersection` of two parabolas. Which is the area made up by all the points $(x\_{i}, y\_{i})$ which are inside both parabolas.

# Standard Input

The test contains two lines, the first line with three numbers $a\_{1}, b\_{1}, c\_{1}$, given a parabola $y = a\_{1}x^2 + b\_{1}x + c\_{1}$.

The second line comes three numbers $a\_{2}, b\_{2}, c\_{2}$, given a parabola $y = a\_{2}x^2 + b\_{2}x + c\_{2}$

$-100\leq a\_{1}, b\_{1}, c\_{1}, a\_{2}, b\_{2}, c\_{2}\leq 100,   a\_{1}a\_{2} < 0$.

# Standard Output

Output the area of intersection, rounded to $3$ digits after decimal point.

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
<tr><td>8 -10 3
-5 7 2</td><td>3.598</td></tr></table>


# Constraints



# Note

You can use `printf("%.3f\n")` to output the answer

# Source


