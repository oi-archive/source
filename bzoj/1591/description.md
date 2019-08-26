
# Description

<div class="content"><div>Farmer John has purchased N (5 &lt;= N &lt;= 250) fence posts in order to build a very nice-looking fence.</div>
<div> Everyone knows the best fences are convex polygons where fence posts form vertices of a polygon. Th</div>
<div>e pasture is represented as a rectilinear grid; fencepost i is at integer coordinates (x_i, y_i) (1 </div>
<div>&lt;= x_i &lt;= 1,000; 1 &lt;= y_i &lt;= 1000). Given the locations of N fence posts (which, intriguingly, featu</div>
<div>re no set of three points which are collinear), what is the largest number of fence posts FJ can use</div>
<div> to create a fence that is convex? For test cases worth 45% of the points for this problem, N &lt;= 65.</div>
<div> Farmer John</div>
<div>有n(5≤n≤250)个栅栏点，他需要围成一个栅栏圈，这个圈是一个凸包并且凸包上的点最多....</div></div>

# Input

<div class="content"><div>Line 1: A single integer: </div>
<div>N * Lines 2..N+1: Line i+1 describes fence post i&#39;s location with two space-separated integers: x_i and y_i</div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer, the maximum possible number of fence posts that form a convex polygon. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
5 5<br/>
2 3<br/>
3 2<br/>
1 5<br/>
5 1<br/>
1 1<br/>
INPUT DETAILS:<br/>
A square with two points inside.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
The largest convex polygon is the pentagon (2,3), (3,2), (5,1), (5,5), (1,5).</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

