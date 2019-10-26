
# Description

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">You are in charge of a team that inspects a new ski resort. A ski resort is situated on several mountains and consists of a number of slopes. Slopes are connected with each other, forking and joining. A map of the ski resort is represented as an acyclic directed graph. Nodes of the graph represent different points in ski resort and edges of the graph represent slopes between the points, with the direction of edges going downwards. <br/>
Your team has to inspect each slope of the ski resort. Ski lifts on this resort are not open yet, but you have a helicopter. In one fiight the helicopter can drop one person into any point of the resort. From the drop off point the person can ski down the slopes, inspecting each slope as they ski. It is fine to inspect the same slope multiple times, but you have to minimize the usage of the helicopter. So, you have to figure out how to inspect all the slopes with the fewest number of helicopter flights.</span></div>
<div class="ptx" lang="en-US"><span style="font-size: medium">给张有向无环图，问至少多少条路径能够覆盖所有的边（可以重复</span></div></div>

# Input

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">The first line of the input file contains a single integer number n (2 &lt;= n &lt;= 100) - the number of points in the ski resort. The following n lines of the input file describe each point of the ski resort numbered from 1 to n. Each line starts with a single integer number mi (0 &lt;= mi &lt; n for i from 1 to n) and is followed by mi integer numbers aij separated by spaces. All aij are distinct for each i and each aij (1 &lt;= aij &lt;= n, aij <img alt="\ne" src="/source/bzoj/2625/img/aHR0cDovL3Bvai5vcmcvZm9ybXVsYT90ZXg9JTVDbmU=" align="absMiddle"/> i) represents a slope going downwards from point i to point aij . Each point in the resort has at least one slope connected to it.</span></div></div>

# Output

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">On the first line of the output file write a single integer number k - the minimal number of helicopter flights that are needed to inspect all slopes. Then write k lines that describe inspection routes for each helicopter flight. Each route shall start with single integer number from 1 to n - the number of the drop off point for the helicopter flight, followed by the numbers of points that will be visited during inspection in the corresponding order as the slopes are inspected going downwards. Numbers on a line shall be separated by spaces. You can write routes in any order.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">8<br/>
1 3<br/>
1 7<br/>
2 4 5<br/>
1 8<br/>
1 8<br/>
0<br/>
2 6 5<br/>
0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

