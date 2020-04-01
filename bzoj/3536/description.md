
# Description

<div class="content"><p><span style="font-size: medium"> Farmer John&#39;s cows would like to host a dance party in their barn, complete with a laser light show. Unfortunately, the only working laser they have found is located far away from the barn and too heavy to move, so they plan to re-direct the laser light to the barn using a series of mirrors. The layout of the farm has the laser at position (0,0) pointing north (in the positive y direction), and the barn at (Bx, By); we can think of both the laser and the barn as points in the 2D plane. There are already N cows (1 &lt;= N &lt;= 100,000) scattered throughout the farm holding mirrors that are aligned at angles of 45 degrees to the axes. For example, a mirror aligned like \ will take a beam of light entering from below and reflect it to the left. We can also think of the mirrors as being located at points in the 2D plane. Just before pressing the big red button to activate the laser, Bessie noticed a major flaw in the plan: the laser cannot hit the barn with the mirrors in their current configuration! As a result, she plans to run out onto the field, and hold up one more mirror (placed once again at a 45 degree angle) in order to redirect the laser onto the barn. Please count the number of locations in the field where Bessie can stand to accomplish this goal. All coordinates are integers between -1,000,000,000 and 1,000,000,000. It is guaranteed that any mirrors to be placed will be in this range as well. The cows running the laser insist that the beam should never come back to (0,0) after leaving this location (and with the mirrors in their initial configuration, it is guaranteed that this will not happen). No two cows occupy the same point in space, and Bessie cannot locate herself at the same position as an existing cow. </span></p>
<p></p>
<div><span style="font-size: medium">(0,0)向正上方有一条射线.</span></div>
<div><span style="font-size: medium">有n个互不相同已经存在并固定的镜子,可以90度折射射线.</span></div>
<div><span style="font-size: medium">现在要添加一个镜子,使得射线最后会到目标节点(Bx,By).</span></div>
<div><span style="font-size: medium">求有多少种安置这个镜子的方式.</span></div></div>

# Input

<div class="content"><p><font size="4">* Line 1: The integers N, Bx, and By.</font></p>
<p><font size="4"> * Lines 2..N + 1: Line i+1 describes the ith mirror with 3 elements: its (x,y) location, and its orientation (either &#39;\&#39; or &#39;/&#39;). </font></p></div>

# Output

<div class="content"><p><font size="4">: A single integer giving the number of locations where Bessie can stand to redirect the laser to the barn. </font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1 2<br/>
-2 1 \<br/>
2 1 /<br/>
2 2 \<br/>
-2 2 /<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 2 <br/>
OUTPUT DETAILS: A mirror at (0,1) or (0,2) placed in either direction would do the trick. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold By liyizhen2">Gold By liyizhen2</a></p></div>

