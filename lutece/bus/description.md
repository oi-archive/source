
# Content

UESTC is moving to the beautiful new campus which locates in the suburb of Chengdu. WCM is taking charge of arranging the buses for the students who are about to move to the new campus. There are two large transportation companies (which we'll call $A$ and $B$) in Chengdu. However, the two transportation companies are very busy, so on any given day they are only able to send limited number of buses.

Here's the problem WCM faces. He gets a list of how many buses are available from each company over each of the next $n$ days. But he can only contact one of the companies in any given day. On day $i$, there are $a_i$($a_i > 0$) buses available if he contacts Company $A$ and there are $b_i$($b_i > 0$) buses available if he contacts Company $B$. He also has the ability to change from one company to the other, but doing this takes one day in which no buses are available.

So, given a sequence of $n$ days, a plan is specified by a choice of $A$, $B$, or `change` for each day, with the constraint that choice $A$ and $B$ cannot appear in consecutive days. For example, if he contacts Company $A$ in day $i$, and he wants to switch to company $B$, then his choice for day $i+1$ must be `change`, and then his choice for day $i+2$ can be $B$. The value of a plan is the total number of buses that he manages to arrange for the students of UESTC over the $n$ days: so it's the sum of $a_i$ over all days in which the buses are available from Company $A$, plus the sum of bi over all days in which the buses are available from Company $B$.

The problem: Given the values of $a_1, a_2, a_3 \cdots a_n$ and $b_1, b_2, b_3 \cdots b_n$, find a plan of the maximum value(Such a plan is called optimal). Note that your plan can start with either of the company $A$ or $B$ in day $1$.

Example: Suppose $n = 4$ and the values of $a_i$ and $b_i$ are given by the following table.

| Day 1 | Day 2 | Day 3 | Day 4
--- | --- | --- | --- | ---
$A$ | $11$ | $2$ | $2$ | $9$
$B$ | $4$ | $1$ | $21$ | $23$

Then the plan of the maximum value would be to choose $A$ for day $1$, then `change` for day $2$, and then $B$ for day $3$ and $4$. The value of this plan would be $11+0+21+23=55$.

Facing this problem, WCM feels despaired. He asks you for help to solve this problem. Give an efficient algorithm that takes values for $a_1, a_2 \cdots a_n$ and $b_1, b_2 \cdots b_n$ and returns the value of an optimal plan.

# Standard Input

The input contains an integer one the first line, which indicates the number of test cases. Each test case consists of three lines. The first line contains one positive integer $n$,($0 < n \leq 1000000$),which means the number of the days. The second line contains $n$ positive integer, $a\_1, a\_2 \cdots a\_n$ ($0 < a\_i \leq 100$), $a\_i$ means the number of buses which can be available if WCM contacts Company $A$ in the $i\_{th}$ day; The third line contains $n$ positive integer, $b\_1, b\_2 \cdots b\_n$,($0 < b\_i \leq 100$), $b\_i$ means the number of buses which can be available if WCM contacts Company $B$ in the $i\_{th}$ day.

# Standard Output

For each test case, output one number on a line which represents the value of the optimal plan, i.e. the maximum of the number of the available buses over the $n$ days.

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
4
11 2 2 9
4 1 21 23
3
1 3 1
7 7 7</td><td>55
21</td></tr></table>


# Constraints



# Note



# Source


