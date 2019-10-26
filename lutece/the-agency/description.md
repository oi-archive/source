
# Content

Following in the footsteps of a number of ight searching startups you want to create the first inter-planetary travel website. Your first problem is to quickly find the cheapest way to travel between two planets. You have an advantage over your competitors because you have realized that all the planets and the ights between them have a special structure. Each planet is represented by a string of $N$-bits and there is a 
ight between two planets if their N-bit strings differ in exactly one position.

The cost of a ight is the cost of landing on the destination planet. If the $i\_{th}$ character in a planet's string is a $1$ then the $i\_{th}$ tax must be paid to land. The cost of landing on a planet is the sum of the applicable taxes.

Given the starting planet, ending planet, and cost of the $i\_{th}$ tax compute the cheapest set of ights to get from the starting planet to the ending planet.

# Standard Input

Input for each test case will consist of two lines. The first line will have $N$ ($1 \le N \le 1,000$), the number of bits representing a planet; $S$, a string of $N$ zeroes and ones representing the starting planet; and $E$,a string representing the ending planet in the same format. The second line will contain $N$ integers the $i\_{th}$ of which is the cost of the $i\_{th}$ tax. All costs will be between $1$ and $1,000,000$. The input will be terminated by a line with a single $0$.

# Standard Output

For each test case output one number, the minimum cost to get from the starting planet to the ending planet, using the format given below.

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
<tr><td>3 110 011
3 1 2
5 00000 11111
1 2 3 4 5
4 1111 1000
100 1 1 1
30 000000000000000000000000000000 111111111111111111111111111111
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30
0</td><td>Case 1: 4
Case 2: 35
Case 3: 106
Case 4: 4960</td></tr></table>


# Constraints



# Note



# Source


