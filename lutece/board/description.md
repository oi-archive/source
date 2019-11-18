
# Content

In the Olympic days, we pay much attention on the medal-board. Now you should show us the board if we give you the result of all the matches.

In the board, the countries should be ordered by the gold medals. If a tie occurred, we will order them by the silver medals, if there is still a tie, we will compare them by the bronze medals. If two countries got the same medals in all the three scales, we will list them by lexicographic order of their names(you may assume that the countries' names won't be repeated).

# Standard Input

The first line of the input contains a number $T$ indicate the test cases.

For each test case,

You will get $N$ ($1\leq N\leq 1000$) in the first line indicate the number of countries.

Then $N$ lines, each line contains a string indicate the $i\_{th}$ country’s name, no two country share the same name.

The next line you will get an integer $M$ ($1\leq M\leq 1000$) denotes the number of items we have in the Olympic game.

Then $M$ items come, for each items, you will get $4$ lines, the first line will be the name of this item, the next $3$ line each give you the nationality of the players in this item from gold to bronze. You can assume the nationality is included in the above country names.

Each of the string above contains no more than $80$ letter (`a` to `z` and `A` to `Z`).

# Standard Output

For each test case, you should output the final medal-board, the countries should be ordered by rules mentioned above, the output format should the same with the sample, after each case, output a blank line.

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
3
China
USA
Russia
1
Football
China
USA
Russia</td><td>China 1 0 0
USA 0 1 0
Russia 0 0 1</td></tr></table>


# Constraints



# Note



# Source


