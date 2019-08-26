
# Description

<div class="content"><p><span style="font-size: medium">给你一个仙人掌图（每条边最多只属于一个简单环），你需要把这个图的点<br/>
集分成大小相等的K部份，并且每部分中的点是相互连通的。<br/>
下图是一个１５个点分成３部分的例子。</span></p>
<p><span style="font-size: medium"><img height="240" width="200" alt="" src="source/bzoj/3634/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNi8xMSgyKS5qcGc=.jpg"/></span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行３个整数，N，M，K表示N个点，M条边。要分成K部分<br/>
接下来M行，每行一条路径，路径的第一个数为S，表示路径的长度<br/>
接下来S个数表示路径上的节点，相邻的节点之间有一条边。<br/>
输入数据保证N是K的倍数，每条边最多只出现一次，整个图是仙人掌图。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">有解输出1,无解输出-1</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">15 3 3<br/>
9 1 2 3 4 5 6 7 8 3<br/>
7 2 9 10 11 12 13 10<br/>
5 2 14 9 15 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">1&lt;=N&lt;=50000,0&lt;=M&lt;=N&lt;=10000,2&lt;=S&lt;=1000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

