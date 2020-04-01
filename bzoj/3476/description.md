
# Description

<div class="content"><p><span style="font-size: medium"> It&#39;s a hot summer day, and Bessie the cow is feeling quite lazy. She wants to locate herself at a position in her field so that she can reach as much delicious grass as possible within only a short distance. There are N patches of grass (1 &lt;= N &lt;= 100,000) in Bessie&#39;s field. The ith such patch contains g_i units of grass (1 &lt;= g_i &lt;= 10,000) and is located at a distinct point (x_i, y_i) in the field (0 &lt;= x_i, y_i &lt;= 1,000,000). Bessie would like to choose a point in the field as her initial location (possibly the same point as a patch of grass, and possibly even a point with non-integer coordinates) so that a maximum amount of grass is within a distance of K steps from this location (1 &lt;= K &lt;= 2,000,000). When Bessie takes a step, she moves 1 unit north, south, east, or west of her current position. For example, to move from (0,0) to (3,2), this requires 5 total steps. Bessie does not need to take integer-sized steps -- for example, 1 total step could be divided up as half a unit north and half a unit east. Please help Bessie determine the maximum amount of grass she can reach, if she chooses the best possible initial location. </span></p>
<p></p>
<p><span style="font-size: medium">在二维平面有N个点。每个点都有个权值。</span></p>
<p><span style="font-size: medium">现在希望你选择某个点，如果其它点到这个点的距离不超过K。</span></p>
<p><span style="font-size: medium">则牛就可以吃到这个点的东西。</span></p>
<p><span style="font-size: medium">现在希望吃到的东西的权值越大越好。请求出这个值来。</span></p></div>

# Input

<div class="content"><p><font size="4">* Line 1: The integers N and K.</font></p>
<p><font size="4"> * Lines 2..1+N: Line i+1 describes the ith patch of grass using 3 integers: g_i, x_i, y_i. </font></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The maximum amount of grass Bessie can reach within K steps, if she locates herself at the best possible initial position. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
7 8 6<br/>
3 0 0<br/>
4 6 0<br/>
1 4 2<br/>
<br/>
 INPUT DETAILS: Bessie is willing to take at most 3 steps from her initial position. There are 4 patches of grass. The first contains 7 units of grass and is located at position (8,6), and so on.</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 8 <br/>
<br/>
OUTPUT DETAILS: By locating herself at (3,0), the grass at positions (0,0), (6,0), and (4,2) is all within K units of distance.<br/>
<br/>
可以选择(3,0)这个点，这样可以吃到 (0,0), (6,0), and (4,2)这三个点的东西，其总和为8</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

