
# Content

Recently, qbwj bought a powerful cellphone which performs even better than most computers. He spent lots of time on it. However, this cellphone has a very strange feature which confused qbwj. There is a battery with infinite capacity in the cellphone. On each day, qbwj has three choices: use the cellphone, charge the battery or do nothing. He cannot do using and charging on the same day. Charging on the $k\_{th}$ day adds $k$ units of power to the battery. If qbwj chooses to use the cellphone on the $k\_{th}$ day, it would consume $k$ units of power. Note that qbwj can choose to use the cellphone if and only if there are enough units of power in the battery.

Despite of the strengths of the cellphone, qbwj couldn't suffer it any more. So he decides to sell it at the end of $T\_{th}$ day. Today is the Sth day and the battery is empty now. He wants to know how many days at maximum he can use the cellphone before selling it out.

Note that qbwj can still choose to use the cellphone on both the $S\_{th}$ day and $T\_{th}$ day.

# Standard Input

The first line of the input will be an integer $N$ ($N \leq 10000$) indicating the number of cases.

For each test case, two integers are given on a single line: $S$ $T$. $1 \leq S \leq T \leq 10^8$.

# Standard Output

Print `Case #k: d` in a single line for each test case, in which $k$ represents the case number which starts from $1$, and $d$ is the answer.

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
3 6
3 9
1 100000</td><td>Case #1: 1
Case #2: 3
Case #3: 49994</td></tr></table>


# Constraints



# Note

For the first sample, we charge the cellphone on the $3\_{rd}$, $4\_{th}$, $5\_{th}$ day and use it on the $6\_{th}$ day.

# Source


