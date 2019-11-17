
# Content

Once every year, Jo and his friends want to visit the local fair in Erlangen, called Bergkirchweih.
This year, they want to make a Kastenlauf (box run). They start at Jo's home, and have one box
(Kasten) of beer (with twenty bottles). As they are very thirsty, they drink one bottle of beer every
$50$ metres.

As the way from Jo's home to the Bergkirchweih is pretty long, they need more beer than they have
initially. Fortunately, there are stores selling beer on the way. When they visit a store, they can
drop their empty bottles and buy new bottles, but their total number of full bottles will not be more
than twenty (because they are too lazy to carry more than one full box).

You are given the coordinates of the stores, of Jo's home and of the location of the Bergkirchweih.
Write a program to determine whether Jo and his friends can happily reach the Bergkirchweih, or
whether they will run out of beer on the way.

# Standard Input

Input starts with one line containing the number of test cases $t$ ($t\leq 50$).

Each test case starts with one line, containing the number n of stores selling beer (with $0\leq n\leq 100$).
The next $n + 2$ lines cointain (in this order) the location of Jo's home, of the stores, and of the
Bergkirchweih. The location is given with two integer coordinates $x$ and $y$, (both in meters, $−32768\leq
x,y\leq 32767$).

As Erlangen is a rectangularly laid out city, the distance between two locations is the difference of
the first coordinate plus the difference of the second coordinate (also called Manhattan-Metric).

# Standard Output

For each test case print one line, containing either `happy` (if Jo and his friends can happily reach
the Bergkirchweih), or `sad` (if they will run out of beer on the way).

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
0 0
1000 0
1000 1000
2000 1000
2
0 0
1000 0
2000 1000
2000 2000</td><td>happy
sad</td></tr></table>


# Constraints



# Note



# Source


