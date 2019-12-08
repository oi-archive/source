
# Content

$ \textbf{Warning}$: In most Online Judges, `A+B` problem may be the easiest problem. However, this `A+B` problem is too hard for freshmen. Any naive algorithm won't pass.

Everyone knows that Lord Huang is the leader of the largest religion among the world. But few know that, before becoming the leader, he was a mathematician. He had solved many hard problems. Today, he encounters another one --- the A+B problem, which is supposed to be the most difficult problem on earth. Even Lord Huang can't solve it. Here comes the problem.

Given two numbers, $A$ and $B$, in base $P$ whose lengths are both $N$. Adding them up, we can get a new number $C$ in base $P$. After changing several digits in $A$ or $B$, their sum $C$ would also change. Lord Huang wants you to tell him the values of some digits in number $C$.

We number the digits ($0$-based) from the rightmost(lowest) digit to leftmost(highest) one. For example, under base $10$, the $0\_{th}$ digit of $123$ is $3$, and the $2\_{nd}$ is $1$.

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T (T \leq 20)$ indicating the number of test cases.

For each test case two integers $P$ and $N (2 \leq P \leq 10000, 1 \leq N \leq 100000)$ come first in a single line, representing the base and the length of $A$ and $B$ respectively. 

The next two lines list the numbers $A$ and $B$ in base $P$. Each line contains $N$ numbers, indicating digits from highest to lowest. We ensure that all these numbers are in range $[0,P-1]$. 

The next line contains an integer $M (1 \leq M \leq 100000)$, representing the number of operations. Each operation belongs to one of the three kinds:
  * $C$ $A$ $X$ $D$. Change the $X\_{th}$ digit of number $A$ to $D (0 \leq X < N, 0 \leq D < P)$.
  * $C$ $B$ $X$ $D$. Change the $X\_{th}$ digit of number $B$ to $D (0 \leq X < N, 0 \leq D < P)$.
  * $Q$ $X$. Output the $X\_{th}$ digit of number $C (0 \leq X < N)$.

# Standard Output

For each test case, print `Case #k:` first, in a single line, where $k$ indicates the case number and starts at $1$.

For each "$Q$ $X$" query, output one number in a single line, representing the $X\_{th}$ number in $C$.

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
10 3
1 2 3
1 2 3
4
C A 0 0
Q 0
C A 0 9
Q 1
10 3
1 2 9
1 1 1
7
Q 1
C A 0 7
Q 0
Q 1
C B 1 9
Q 1
Q 2</td><td>Case #1:
3
5
Case #2:
4
8
3
1
3</td></tr></table>


# Constraints



# Note

Huge input/output. Please use scanf/printf for C/C++.

For the first case, after operation "$C$ $A$ $0$ $0$", $A$ turns into $1$ $2$ $0$. And it becomes $1$ $2$ $9$ after "$C$ $A$ $0$ $9$".

# Source


