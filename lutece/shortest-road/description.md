
# Content

Before long, xiaoze received a call from the sponsor company All Options, while he was busy on the problems for the upcoming UESTC programming contest. He was invited to discuss the patronage. Sure, xiaoze was exciting and they made a time immediately.

But, here comes the problem. You know, Chengdu is a metropolis, you should choose a smart route in order to save time. As there're many routes, xiaoze is puzzled. You are xiaoze's best friend. Could you help him compute the least time spent on the road? What's more, you should tell xiaoze the number of shortest routes, that's because xiaoze wants to choose another route when he be back if applicable.

Now, suppose xiaoze is at $S$, and the company All Options is at $T$. There're $N$ crosses and $M$ roads in Chengdu. Now, please solve this problem for xiaoze as soon as possible.

# Standard Input

The beginning is an integer $T$, which is the number of test case.

First line of each test case contains two numbers $N$($2 \leq N \leq 1000$) and $M$($0 \leq M \leq 10^6$). Then followed by $M$ lines, each line contains three numbers $A$ $B$ ($1 \leq A,B \leq N$) and $C$($1 \leq C \leq 10^6$), indicating you need $C$ minutes to go from $A$ to $B$. The last line contains two numbers $S$ and $T$, indicating the start and end places. Each node is numbered from $1$.

It is sure that there’s at most one undirect road between any two places.

# Standard Output

First line, the least time you need from $S$ to $T$ measured in minute. The second line is the number of shortest routes $mod$ $1000007$. Output two lines each contain a `0` if it’s impossible to travel to destination.

Output an empty line after each test cases.

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

4 2
1 2 10
3 4 5
1 4

4 4
1 2 1
2 4 2
1 3 2
3 4 1
1 4

9 12
1 2 1000000
1 3 1000000
2 4 1000000
2 5 1000000
3 5 1000000
3 6 1000000
4 7 1000000
5 7 1000000
5 8 1000000
6 8 1000000
7 9 1000000
8 9 1000000
1 9</td><td>0
0

3
2

4000000
6</td></tr></table>


# Constraints



# Note



# Source


