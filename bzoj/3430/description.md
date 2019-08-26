
# Description

<div class="content"><p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">   The cross-country skiing course at the winter Moolympics is described by an M x N grid of elevations (1 &lt;= M,N &lt;= 500), each elevation being in the range 0 .. 1,000,000,000.    Some of the cells in this grid are designated as starting points for the course.  The organizers of the Moolympics want to assign a difficulty rating to each starting point.  The difficulty level of a starting point P should be the minimum possible value of D such that a cow can successfully reach at least T total cells of the grid (1 &lt;= T &lt;= MN), if she starts at P and can only move from cell to adjacent cell if the absolute difference in elevation between the cells is at most D.  Two cells are adjacent if one is directly north, south, east, or west of the other.  Please help the organizers compute the difficulty rating for each starting point.  </span></span></p>
<p>给定一个n*m的高度矩阵，一个点的难度P是指 最小的D使得以这个点为起点，可到达的格子数量至少为T，一个格子可以到另外一个格子必须保证两个格子相邻且高度差不超过D，相邻是指4-相邻。再给定一个同样大小的01矩阵，求出所有1处格子的难度和。</p></div>

# Input

<div class="content"><p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">* Line 1: The integers M, N, and T.  </span></span></p>
<p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">* Lines 2..1+M: Each of these M lines contains N integer elevations.</span></span></p>
<p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">  * Lines 2+M..1+2M: Each of these M lines contains N values that are         either 0 or 1, with 1 indicating a cell that is a starting         point. </span></span></p></div>

# Output

<div class="content"><p><span style="font-size: medium;"><span id="probtext-text" class="mono prewrap">* Line 1: The sum of difficulty ratings of all starting points (note         that this may not fit into a 32-bit integer, even though         individual difficulty ratings will).</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 5 10 <br/>
20 21 18 99 5 <br/>
19 22 20 16 17 <br/>
18 17 40 60 80<br/>
1 0 0 0 0 <br/>
0 0 0 0 0<br/>
0 0 0 0 1</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 24 <br/>
OUTPUT DETAILS: The difficulty rating of the upper-left starting point is 4, and for the lower-right it is 20.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

