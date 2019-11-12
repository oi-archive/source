# 题目描述


<p>
timeismoney 100 points
</p>
<p>
Source code: timeismoney.c, timeismoney.cpp, timeismoney.pas
</p>
<p>
Input file: timeismoney.in
</p>
<p>
Output file: timeismoney.out
</p>
<p>
Time limit: 2 seconds
</p>
<p>
Memory limit: 64 MB
</p>
<p>
The NetLine company wants to offer broadband internet to N towns. For this, it suffices to construct
</p>
<p>
a network of N-1 broadband links between the towns, with the property that a message can travel
</p>
<p>
from any town to any other town on this network. NetLine has already identified all pairs of towns
</p>
<p>
between which a direct link can be constructed. For each such possible link, they know the cost and
</p>
<p>
the time it would take to construct the link.
</p>
<p>
The company is interested in minimizing both the total amount of time (links are built one at a time)
</p>
<p>
and the total amount of money spent to build the entire network. Since they couldn’t decide among
</p>
<p>
the two criteria, they decided to use the following formula to evaluate the value of a network:
</p>
<p>
SumTime = sum of times spent to construct the chosen links
</p>
<p>
SumMoney = sum of the money spent to construct the chosen links
</p>
<p>
V = SumTime * SumMoney
</p>
<p>
Task
</p>
<p>
Find a list of N-1 links to build, which minimizes the value V.
</p>
<p>
Description of input
</p>
<p>
The first line of input contains integers N – the number of towns and M – the number of pairs of
</p>
<p>
towns which can be connected. The towns are numbered starting from 0 to N-1. Each of the next M
</p>
<p>
lines contain four integers x, y, t and c – meaning town x can be connected to town y in time t and
</p>
<p>
with cost c.
</p>
<p>
Description of output
</p>
<p>
In the first line of output print two numbers: the total time (SumTime) and total money (Sum-
</p>
<p>
Money) used in the optimal solution (the one with minimal value V), separated by one space. The
</p>
<p>
next N-1 lines describe the links to be constructed. Each line contains a pair of numbers (x,y) describing
</p>
<p>
a link to be build (which must be among the possible links described in the input file). The
</p>
<p>
pairs can be printed out in any order. When multiple solutions exist, you may print any of them.
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
· 1 ≤ N ≤ 200
</p>
<p>
· 1 ≤ M ≤ 10 000
</p>
<p>
· 0 ≤ x,y ≤ N-1
</p>
<p>
· 1 ≤ t,c ≤ 255
</p>
<p>
· One test has M = N - 1
</p>
<p>
· 40% of the tests will have for each possible link t = c
</p>
<p>
Example
</p>
<p>
timeismoney.in timeismoney.out
</p>
<p>
5 7
</p>
<p>
0 1 161 79
</p>
<p>
0 2 161 15
</p>
<p>
0 3 13 153
</p>
<p>
1 4 142 183
</p>
<p>
2 4 236 80
</p>
<p>
3 4 40 241
</p>
<p>
2 1 65 92
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
279 501
</p>
<p>
2 1
</p>
<p>
0 3
</p>
<p>
0 2
</p>
<p>
3 4
</p>
<p>
    注意测试数据中不要求输出方案。
</p>
<p>
<br/>
</p>
