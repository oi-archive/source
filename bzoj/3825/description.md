
# Description

<div class="content"><p><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">An avid marathon runner herself, Bessie enjoys creating marathon courses for her fellow cows to run.  She has most recently designed a route specified by N checkpoints (1 &lt;= N &lt;= 100,000) that must be visited in sequence.  Unfortunately, Bessie realizes that the other cows may not have the stamina to run the full route. She therefore wants to know how long certain sub-routes take to run, where a sub-route is a contiguous subsequence of the checkpoints from the full route.  To make matters more complicated, Bessie knows that the other cows, being lazy, might choose to skip one checkpoint any time they run a sub-route -- whichever one results in a minimum total travel time.  They are not allowed to skip the first or last checkpoints in a sub-route, however.  In order to build the best possible marathon course, Bessie wants to investigate the ramifications of making changes to the checkpoint locations in her current course.  Please help her determine how certain changes to checkpoint locations will affect the time required to run different sub-routes (taking into account that the cows might choose to omit one checkpoint any time they run a sub-route).  Since the course is set in a downtown area with a grid of streets, the distance between two checkpoints at locations (x1, y1) and (x2, y2) is given by |x1-x2| + |y1-y2|.<br/>
</span></p>
<p><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">yjq要被n(n&lt;=100,000)个zhx按顺序吊打，第i个zhx在平面上的坐标为(xi, yi)。</span></p>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">有m(m&lt;=100,000)次操作。</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">U操作：第i个zhx的位置改为(xnew, ynew)。</div>
<div style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 23px;">Q操作：yjq要被编号从i到j的zhx按顺序吊打，但是yjq可以选择跳过编号在[i+1, j-1]中的一个zhx，问yjq最少要走多远的路。</div>
<p></p>
<p></p></div>

# Input

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">The first line gives N and Q (1 &lt;= Q &lt;= 100,000). The next N lines contain (x, y) locations of N checkpoints in the sequence they must be visited along the route.  All coordinates are in the range -1000 .. 1000. The next Q lines consist of updates and queries, one per line, to be processed in the order they are given. Lines will either take the form &#34;U I X Y&#34; or &#34;Q I J&#34;.  A line of the form &#34;U I X Y&#34; indicates that the location of checkpoint I (1 &lt;= I &lt;= N) is to be changed to location (X, Y).  A line of the form &#34;Q I J&#34; asks for the minimum travel time of the sub-route from checkpoint I to checkpoint J (I &lt;= J), given that the cows choose to skip one checkpoint along this sub-route (but not the endpoints I and J).<br/>
</span></div>
<p></p></div>

# Output

<div class="content"><div><span style="font-family: monospace; font-size: 14px; white-space: pre-wrap;">For each sub-route length request, output on a single line the desired length.<br/>
</span></div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
-4 4<br/>
-5 -3<br/>
-1 5<br/>
-3 4<br/>
0 5<br/>
Q 1 5<br/>
U 4 0 1<br/>
U 4 -1 1<br/>
Q 2 4<br/>
Q 1 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
8<br/>
8</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

