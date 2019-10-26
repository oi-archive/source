
# Content

MM/DD/YY, the Star Wars break out.There is a bridge from the earth to the moon,which is considered as the attack objective by the extraterrestrials.The aliens will use $n$ bombs to blow up the bridge.Your task is to calculate the remaining length of the bridge after the aliens' attack.

In order to simplify the problem,the attack is considered to occur in a two-dimensional plane.The bridge is represented by a line segment, and each of the $n$ bombs has a different circular range of explosion, and any part of the line segment included in any of the circular ranges will be destroyed. Then the task is to calculate the remaining length of the line segment.

# Standard Input

The first line of each test is an integer $n(0 \leq n \leq 1000)$,which represents the number of bombs.

Then there are n lines,and each line has three real numbers:$x,y,r$.Which means the coordinate of the corresponding bomb is $(x,y)$,and the radius of its explosive range is $r( 0 < r < 100)$ . 

Then there comes the last two lines,and each of the line has two integers,which are the coordinates of the endpoints of the bridge in the two-dimensional plane.
All the coordinates $(x,y)$ in the input satisfy $(0 \leq x,y < 10000)$ 

Input ends when $n=0$.

# Standard Output

Output the remaining length of the bridge for every test.

The answer should be rounded to $4$ digits after the decimal point.

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
0 0 2
-1 0 
1 0
1
0 0 2
-3 0 
3 0
2
0 0 2
2 0 0.5
-3 0 
3 0
0</td><td>0.0000
2.0000
1.5000</td></tr></table>


# Constraints



# Note



# Source


