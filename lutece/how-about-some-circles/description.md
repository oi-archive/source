
# Content

Kufeng is fond of circles. He builds a big machine which deal with circles and points.

There are $m$ points on a $XOY$ plane. The points' position may coincide. Kufeng also has $n$ circles, the position of each circle's center, as long as the initial radius of each circle are given to you.

Each time, Kufeng can operate the machine, and change some circles' radius.

The points give energy to the circles, the total energy for a circle is the number of points that **strictly lie inside** that circle. A point might serve energy to more than one circle.

At some time, Kufeng wants to know the total energy of some circles.

# Standard Input

The first line of the input contains two numbers $n$ and $m$, the number of circles and the number of points. $(1\leq n\leq 10000, 1\leq m\leq 100)$

The next $n$ lines each with three numbers $x\_{i}, y\_{i}, r\_{i}$, which means the $i\_{th}$ circle on the plane. With center located at $(x\_{i}, y\_{i})$, and with radius length $r\_{i}$.  $(0\leq x\_{i}, y\_{i}, r\_{i}\leq 100)$

The next $m$ lines each with three numbers $px\_{i}, py\_{i}$, which means the $i\_{th}$ point on the plane located at $(px\_{i}, py\_{i})$. $(0\leq px\_{i}, py\_{i}\leq 100)$

The next lines contain a number $q$, the number of operations Kufeng will do. $(1\leq q\leq 100000)$

The next $q$ lines each can be given in the following two types:

`1 l r val`: Kufeng will operate on all the circles, from $l\_{th}$ to $r\_{th}$, inclusive, and change those circles' radius to $val$.$ (1\leq l\leq r\leq n, 1\leq val\leq 500)$

`2 l r`: Kufeng will calculate the sum of energy of all the circles, from $l\_{th}$ to $r\_{th}$, inclusive.$ (1\leq l\leq r\leq n)$

# Standard Output

For each type of `2 l r`, output the answer in a line.

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
<tr><td>3 4
1 0 1
1 1 1
1 2 1
0 0
2 0
2 2
0 2
5
2 1 3
1 2 2 2
2 1 3
1 1 3 2
2 1 3</td><td>0
4
8</td></tr></table>


# Constraints



# Note



# Source


