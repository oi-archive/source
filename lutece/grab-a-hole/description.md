
# Content

<p class="text-right"><i>"One radish, one hole"</i></p>

$N$ rats migrate to a new habitat. There are exactly $N$ holes which lie on a line one by one. The holes are numbered (starting from the leftmost one) from $1$ to $n$. They don't want to share a hole with others, so every rat should grab a hole as its home. Each rat has an interested interval (we denote it as $[s,t]$, in which s and t are the two ends) of holes from which it would choose one to grab. However, a plan that ensures any rats have a hole may not exist.

RectaFlex loves these rats very much. He wants to train these rats to expand their interested interval with $K$ more holes. Note that the new expanded interested interval of each rat must still be continuous. If a rat interested in holes which belong to interval $[s,t]$, it could extend the interval with $K$ more hole. After training, the intervals this rat interest will be $[s-a,t+b]$ ($a+b\leq k$, $0\leq a\leq k$, $0\leq b\leq k$).

Because training these rats to expand their habitat's scope is very hard, RectaFlex wants to know the minimum $K$.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T \leq 20$) indicating the number of test cases.

For each test case there is an integer $N$ ($1 \leq N \leq 500$) in a single line, representing the number of holes (i.e. the number of rats). The holes are numbered from $1$ to $N$. Then follows $N$ lines, each contains two integers $L\_i$ and $R\_i$ ($1 \leq L\_i \leq R\_i \leq N$), indicating the interest interval of the $i\_{th}$ rat (inclusive).

# Standard Output

For each test case, print `Case #t: ` first, in which $t$ is the number of the test case starting from $1$. Then output the minimum $K$.

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
<tr><td>5
2
1 1
1 1
5
1 1
1 1
5 5
5 5
5 5
3
1 1
2 2
3 3
4
1 1
1 2
2 3
3 4
4
1 1
1 2
1 1
1 4</td><td>Case #1: 1
Case #2: 2
Case #3: 0
Case #4: 0
Case #5: 1</td></tr></table>


# Constraints



# Note

In the first case, expanding the intervals to be $[1,2]$ guarantees each rat a hole.

# Source


