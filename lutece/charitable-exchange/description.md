
# Content

Have you ever heard a star charity show called Charitable Exchange? In this show, a famous star starts with a small item which values $1$ yuan. Then, through the efforts of repeatedly exchanges which continuously increase the value of item in hand, he (she) finally brings back a valuable item and donates it to the needy.

In each exchange, one can exchange for an item of Vi yuan if he (she) has an item values more than or equal to $R\_i$ yuan, with a time cost of $T\_i$ minutes.

Now, you task is help the star to exchange for an item which values more than or equal to $M$ yuan with the minimum time.

# Standard Input

The first line of the input is $T$ (no more than $20$), which stands for the number of test cases you need to solve.

For each case, two integers $N$, $M$ ($1 \leq N \leq 10^5$, $1 \leq M \leq 10^9$) in the first line indicates the number of available exchanges and the expected value of final item. Then $N$ lines follow, each line describes an exchange with $3$ integers $V\_i$, $R\_i$, $T\_i$ ($1 \leq R\_i \leq V\_i \leq 10^9$, $1 \leq T\_i \leq 10^9$).

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and counts from $1$. Then output the minimum time. Output $-1$ if no solution can be found.

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
3 10
5 1 3
8 2 5
10 9 2
4 5
2 1 1
3 2 1
4 3 1
8 4 1
5 9
5 1 1
10 4 10
8 1 10
11 6 1
7 3 8</td><td>Case #1: -1
Case #2: 4
Case #3: 10</td></tr></table>


# Constraints



# Note



# Source


