
# Description

<div class="content"><div>John养了一只叫Joseph的奶牛。一次她去放牛，来到一个非常长的一片地，上面有N块地方长了茂盛的草。我们可</div>
<div>以认为草地是一个数轴上的一些点。Joseph看到这些草非常兴奋，它想把它们全部吃光。于是它开始左右行走，吃</div>
<div>草。John和Joseph开始的时候站在p位置。Joseph的移动速度是一个单位时间一个单位距离。不幸的是，草如果长</div>
<div>时间不吃，就会腐败。我们定义一堆草的腐败值是从Joseph开始吃草到吃到这堆草的总时间。Joseph可不想吃太腐</div>
<div>败的草，它请John帮它安排一个路线，使得它吃完所有的草后，总腐败值最小。John的数学很烂，她不知道该怎样</div>
<div>做，你能帮她么？</div></div>

# Input

<div class="content"><div>* Line 1 : Two space-separated integers: N and L. N&lt;=1000</div>
<div>* Lines 2..N+1: Each line contains a single integer giving the position P of a clump (1 &lt;= P &lt;= 1,000,000).</div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer: the minimum total staleness Bessie can achieve while eating all the clumps. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 10<br/>
1<br/>
9<br/>
11<br/>
19<br/>
INPUT DETAILS:<br/>
Four clumps: at 1, 9, 11, and 19. Bessie starts at location 10.</span></div>

# Sample Output

<div class="content"><span class="sampledata">44<br/>
OUTPUT DETAILS:<br/>
Bessie can follow this route:<br/>
* start at position 10 at time 0<br/>
* move to position 9, arriving at time 1<br/>
* move to position 11, arriving at time 3<br/>
* move to position 19, arriving at time 11<br/>
* move to position 1, arriving at time 29<br/>
giving her a total staleness of 1+3+11+29 = 44.  There are other routes<br/>
with the same total staleness, but no route with a smaller one.44</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

