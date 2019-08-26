
# Description

<div class="content"><p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">In an effort to better manage the grazing patterns of his cows, Farmer John has installed one-way cow paths all over his farm.  The farm consists of N fields, conveniently numbered 1..N, with each one-way cow path connecting a pair of fields.  For example, if a path connects from field X to field Y, then cows are allowed to travel from X to Y but not from Y to X.  Bessie the cow, as we all know, enjoys eating grass from as many fields as possible.  She always starts in field 1 at the beginning of the day and visits a sequence of fields, returning to field 1 at the end of the day.  She tries to maximize the number of distinct fields along her route, since she gets to eat the grass in each one (if she visits a field multiple times, she only eats the grass there once).  As one might imagine, Bessie is not particularly happy about the one-way restriction on FJ&#39;s paths, since this will likely reduce the number of distinct fields she can possibly visit along her daily route.  She wonders how much grass she will be able to eat if she breaks the rules and follows up to one path in the wrong direction. Please compute the maximum number of distinct fields she can visit along a route starting and ending at field 1, where she can follow up to one path along the route in the wrong direction.  Bessie can only travel backwards at most once in her journey.  In particular, she cannot even take the same path backwards twice.<br/>
</span><font face="monospace"><span style="font-size: 14px; white-space: pre-wrap;">给一个有向图，然后选一条路径起点终点都为1的路径出来，有一次机会可以沿某条边逆方向走，问最多有多少个点可以被经过？（一个点在路径中无论出现多少正整数次对答案的贡献均为1）</span></font></p>
<p></p></div>

# Input

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">The first line of input contains N and M, giving the number of fields and the number of one-way paths (1 &lt;= N, M &lt;= 100,000).  The following M lines each describe a one-way cow path.  Each line contains two distinct field numbers X and Y, corresponding to a cow path from X to Y.  The same cow path will never appear more than once.<br/>
</span></div>
<p></p></div>

# Output

<div class="content"><div>A single line indicating the maximum number of distinct fields Bessie</div>
<div>can visit along a route starting and ending at field 1, given that she can</div>
<div>follow at most one path along this route in the wrong direction.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 10<br/>
1 2<br/>
3 1<br/>
2 5<br/>
2 4<br/>
3 7<br/>
3 5<br/>
3 6<br/>
6 5<br/>
7 2<br/>
4 7</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold&amp;鸣谢18357">Gold&amp;鸣谢18357</a></p></div>

