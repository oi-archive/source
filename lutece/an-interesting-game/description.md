
# Content

Cloudiris and XiaoT like to play a game. The game is playing in the following way. First, XiaoT writes $N$ positive integers in a paper. These integers are labeled from $0$ to $N-1$. Then, XiaoT gives Cloudiris some instructions. The instructions take one of the two forms: $A > B$ or $A = B$. The first means that the $A$th number is larger than the $B$th number whereas the second means that the $A$th number equals the $B$th number. Since XiaoT is such an honest boy, all the instructions are guaranteed to be correct. And then, XiaoT will ask Cloudiris the relationship between some pairs of numbers. Depending on the instructions given by XiaoT, Cloudiris should respond with one of the following answers: $>, =, <,$ or $N$ (which means the relationship is not clear). If Cloudiris gives a correct answer, she can get a strawberry and she really like strawberries. But when there are many numbers and even more relationships, the answer is difficult if not impossible to get. So Cloudiris turn to you for help. Now will you use your brilliant mind and help Cloudiris find the correct answer?

# Standard Input

The first line of the input contains a positive integer $T$ representing the number of test cases.$T<30$

Each test case start with three integers $N, M,$ and $K$, representing the number of integers and relationship in the game and the number of questions XiaoT asked. $0 < N \leq 100, 0 \leq M \leq 10000, 0 < K \leq 10000$

Each of the following $M$ lines takes one of the two forms: $A > B$ or $A=B$, whose meaning has been mentioned above. $0 \leq A < N, 0 \leq B < N$.

Then K lines follow. Each line contains two integers $C$ and $D$ which means a question is asked about the relationship between the $C$th number and the Dth number. $0 \leq C < N, 0 \leq D < N, C != D$.

# Standard Output

For each question, give an answer in one line. The answer should be: $>, =, <,$ or $N$.

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
3 2 2
0 = 1
2 > 1
2 0
1 0
5 4 3
2 = 3
4 > 1
0 > 1
0 > 2
0 4
1 2
3 0</td><td>>
=
N
N
<</td></tr></table>


# Constraints



# Note



# Source


