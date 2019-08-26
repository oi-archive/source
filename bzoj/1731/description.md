
# Description

<div class="content"><p><span style="font-size: medium">Like everyone else, cows like to stand close to their friends when queuing for feed. FJ has N (2 &lt;= N &lt;= 1,000) cows numbered 1..N standing along a straight line waiting for feed. The cows are standing in the same order as they are numbered, and since they can be rather pushy, it is possible that two or more cows can line up at exactly the same location (that is, if we think of each cow as being located at some coordinate on a number line, then it is possible for two or more cows to share the same coordinate). Some cows like each other and want to be within a certain distance of each other in line. Some really dislike each other and want to be separated by at least a certain distance. A list of ML (1 &lt;= ML &lt;= 10,000) constraints describes which cows like each other and the maximum distance by which they may be separated; a subsequent list of MD constraints (1 &lt;= MD &lt;= 10,000) tells which cows dislike each other and the minimum distance by which they must be separated. Your job is to compute, if possible, the maximum possible distance between cow 1 and cow N that satisfies the distance constraints. </span></p>
<p></p>
<p><span style="font-size: medium"> 当排队等候喂食时，奶牛喜欢和它们的朋友站得靠近些。FJ有N（2&lt;=N&lt;=1000）头奶牛，编号从1到N，沿一条直线站着等候喂食。奶牛排在队伍中的顺序和它们的编号是相同的。因为奶牛相当苗条，所以可能有两头或者更多奶牛站在同一位置上。即使说，如果我们想象奶牛是站在一条数轴上的话，允许有两头或更多奶牛拥有相同的横坐标。一些奶牛相互间存有好感，它们希望两者之间的距离不超过一个给定的数L。另一方面，一些奶牛相互间非常反感，它们希望两者间的距离不小于一个给定的数D。给出ML条关于两头奶牛间有好感的描述，再给出MD条关于两头奶牛间存有反感的描述。（1&lt;=ML,MD&lt;=10000，1&lt;=L,D&lt;=1000000）你的工作是：如果不存在满足要求的方案，输出-1；如果1号奶牛和N号奶牛间的距离可以任意大，输出-2；否则，计算出在满足所有要求的情况下，1号奶牛和N号奶牛间可能的最大距离。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Three space-separated integers: N, ML, and MD. * Lines 2..ML+1: Each line contains three space-separated positive integers: A, B, and D, with 1 &lt;= A &lt; B &lt;= N. Cows A and B must be at most D (1 &lt;= D &lt;= 1,000,000) apart. * Lines ML+2..ML+MD+1: Each line contains three space-separated positive integers: A, B, and D, with 1 &lt;= A &lt; B &lt;= N. Cows A and B must be at least D (1 &lt;= D &lt;= 1,000,000) apart. </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer. If no line-up is possible, output -1. If cows 1 and N can be arbitrarily far apart, output -2. Otherwise output the greatest possible distance between cows 1 and N. </span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2 1<br/>
1 3 10<br/>
2 4 20<br/>
2 3 3<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
There are 4 cows.  Cows #1 and #3 must be no more than 10 units<br/>
apart, cows #2 and #4 must be no more than 20 units apart, and cows<br/>
#2 and #3 dislike each other and must be no fewer than 3 units apart.<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">27<br/>
<br/>
 四只牛分别在0，7，10，27.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

