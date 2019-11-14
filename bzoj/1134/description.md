
# Description

<div class="content"><p>在三角形图上，每个小正三角形的面积都是1。可以在边上走出一个多边形，（即三角形网格图的边界，见下图）使得围成一定的面积。 我们可以用编码来表示走法：（即从一条边到下一条边的方向改变量） a左转120° b左转60° c直走 d右转60° e右转120°</p>
<p> <img border="0" alt="" src="/source/bzoj/1134/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExMzQuanBn.jpg"/></p>
<p>可以描述为cdddcddd 或dddcdddc，cbbbcbbb 对于描述同样形状的图形的不同序列，我们只用字典序最小的，即bbbcbbbc 两个多边形在几何的概念上全等即看做等价。显然等价的图形用字母路径表示出来是一样的。 你的任务有两个： 1． 对于给定的N输出所有面积为N的可以走出来的图形的编码 2． 对于给定的形状序列，求出其面积K并计算在这个图形基础上加一个小三角形可以组成哪些可编码图形。 每个测试点 询问不超过5次 数据保证 N,K ≤ 10</p></div>

# Input

<div class="content"><p>第一行数据总数t， t≤5 每个询问以“N”开头则表示任务1，接下来一个整数N 以“K”开头则表示任务2，接下来是一个字符串。</p></div>

# Output

<div class="content"><p>对于每个任务，输出两行， 第一行表示满足要求的方案总数， 第二行按字典序输出所有序列，两个序列之间用一个空格隔开。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
K adeccecced<br/>
N 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
acedccecced addebcecced adebebecced adecbedcced cceccecce<br/>
4<br/>
aeddde bdecdde bececde ccedcde</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

