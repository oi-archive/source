
# Content

Our famous “DAGE”, God Kufeng, likes killing monsters. However, killing monsters is a tiring job, and might do harm to DAGE’s health.

Now there are n monsters, each monster has a strength value. Let’s say, before killing a monster with strength $X$, DAGE has a health point(HP) as $V$, then after killing, DAGE’s HP will become 

$V_{new} = V \&X$

Here `&` means bitwise AND. For example, $5 \& 4 = 4$, $5 \& 2 = 0$.

At first, the health point(HP) of DAGE will be $2047$. 

DAGE has a simple strategy, each time he just randomly choose a monster to kill, and kill that monster.

When DAGE’s HP becomes $0$, DAGE will feel tired and go home to sleep.

What is the expected number of monsters DAGE has killed when DAGE goes to bed?  It is guaranteed that DAGE will go to bed at some moment.

# Standard Input

The first line contains a single number $n$,  the number of the monsters. ($1\leq n\leq 50$)

The the second line comes with $n$ numbers $x\_1, x\_2, \cdots, x\_n$, those are the strenght value of each monster. $(0\leq x\_i\leq 2047)$.

# Standard Output

Output a single number in a line, the expected number of monsters DAGE has killed when he goes to bed, rounded to 3 digits after decimal point.

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
0 1 2</td><td>1.667</td></tr></table>


# Constraints



# Note



# Source


