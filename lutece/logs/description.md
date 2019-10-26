
# Content

The server of CDOJ logs all the submissions submitted by users. There are four types of logs: submissions of 
1. every day ($1\_{st}$ day, $2\_{nd}$ day, ......),
2. every $7$ days ($1\_{st}$ to $7\_{th}$ days, $8\_{th}$ to $14\_{th}$ days, ……), 
3. every $30$ days ($1\_{st}$ to $30\_{th}$ days, $31\_{th}$ to $60\_{th}$ days, ……), 
4. every $365$ days($1\_{st}$ to $365\_{th}$ days, $366\_{th}$ to $730\_{th}$ days, ……). 

We name a log as an interval $[s,t]$, in which s and t represent the time of the first submission and the last submission. For each type, every submission would be recorded only once. For example, in the second type of logs, submissions on the $7\_{th}$ day would be recorded in log $[1,7]$. Logs such as $[2,8]$, $[100,465]$ do not exist. 

Now Yangsir wants to know the information about all the submissions between day $X$ and day $Y$ (inclusive). He can take several logs out one by one. Assume that Yangsir has a `box` to put submissions. When he takes a log out, all the submission in that log would be put into the `box`. However, if some submissions have already been in the `box`, both submissions would disappear because of some strange reason. The final submissions in the `box` are what Yangsir gets.

For example, Yangsir would get submissions between day $2$ and day $7$ when he takes $[1,7]$ and $[1,1]$ out. If he takes $[1,7]$, $[1,1]$, $[8,8]$, $[1,1]$ out one by one, what he gets are submissions between day $1$ and day $8$. 

How many logs Yangsir should take out at least if he needs all the submissions between day $X$ and day $Y$?

# Standard Input

There are multiple test cases. The first line of the input will be an integer $T$ ($T\leq 100$) indicating the number of test cases.

For each test case there are two integers $X$ and $Y$ ($1 \leq X \leq Y \leq 10^9$) in a single line.

# Standard Output

For each test case, print `Case #t: ` first, in which $t$ is the number of the test case starting from $1$. Then output the minimum number of logs needed.

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
42 42
21 28
180 203</td><td>Case #1: 1
Case #2: 2
Case #3: 3</td></tr></table>


# Constraints



# Note

For the third sample, only $3$ logs are needed: $[180,180]$, $[181,210]$, $[204,210]$. Combining log $[180,180]$ with $[181,210]$, we get $[180,210]$. Log $[204,210]$ could remove all submission after Day $203$.

# Source


