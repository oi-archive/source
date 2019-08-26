
# Description

<div class="content"><p><span style="font-size: medium">Farmer John has taken his cows on a trip to the city! As the sun sets, the cows gaze at the city horizon and observe the beautiful silhouettes formed by the rectangular buildings. The entire horizon is represented by a number line with N (1 &lt;= N &lt;= 40,000) buildings. Building i&#39;s silhouette has a base that spans locations A_i through B_i along the horizon (1 &lt;= A_i &lt; B_i &lt;= 1,000,000,000) and has height H_i (1 &lt;= H_i &lt;= 1,000,000,000). Determine the area, in square units, of the aggregate silhouette formed by all N buildings. </span></p>
<p><span style="font-size: medium">N个矩形块，交求面积并.</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer: N </span></p>
<p><span style="font-size: medium">* Lines 2..N+1: Input line i+1 describes building i with three space-separated integers: A_i, B_i, and H_i</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The total area, in square units, of the silhouettes formed by all N buildings </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2 5 1<br/>
9 10 4<br/>
6 8 2<br/>
4 6 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">16<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
The first building overlaps with the fourth building for an area of 1<br/>
square unit, so the total area is just 3*1 + 1*4 + 2*2 + 2*3 - 1 = 16.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

