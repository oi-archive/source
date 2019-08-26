
# Description

<div class="content"><p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">Unhappy with the poor health of his cows, Farmer John enrolls them in an assortment of different physical fitness activities.  His prize cow Bessie is enrolled in a running class, where she is eventually expected to run a marathon through the downtown area of the city near Farmer John&#39;s farm!  The marathon course consists of N checkpoints (3 &lt;= N &lt;= 500) to be visited in sequence, where checkpoint 1 is the starting location and checkpoint N is the finish.  Bessie is supposed to visit all of these checkpoints one by one, but being the lazy cow she is, she decides that she will skip up to K checkpoints (K &lt; N) in order to shorten her total journey.  She cannot skip checkpoints 1 or N, however, since that would be too noticeable.  Please help Bessie find the minimum distance that she has to run if she can skip up to K checkpoints.    Since the course is set in a downtown area with a grid of streets, the distance between two checkpoints at locations (x1, y1) and (x2, y2) is given by |x1-x2| + |y1-y2|.<br/>
</span></p>
<div>在二维平面上有N个点，从(x1,y1)到(x2,y2)的代价为|x1-x2|+|y1-y2|。</div>
<div>求从1号点出发，按从1到N的顺序依次到达每个点的最小总代价。</div>
<div>你有K次机会可以跳过某个点，不允许跳过1号点或N号点。</div>
<p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;"> </span></p>
<p></p></div>

# Input

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">The first line gives the values of N and K. The next N lines each contain two space-separated integers, x and y, representing a checkpoint (-1000 &lt;= x &lt;= 1000, -1000 &lt;= y &lt;= 1000). The checkpoints are given in the order that they must be visited. Note that the course might cross over itself several times, with several checkpoints occurring at the same physical location.  When Bessie skips such a checkpoint, she only skips one instance of the checkpoint -- she does not skip every checkpoint occurring at the same location.<br/>
</span></div>
<p></p></div>

# Output

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">Output the minimum distance that Bessie can run by skipping up to K checkpoints.  In the sample case shown here, skipping the checkpoints at (8, 3) and (10, -5) leads to the minimum total distance of 4.<br/>
</span></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 2<br/>
0 0<br/>
8 3<br/>
1 1<br/>
10 -5<br/>
2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

