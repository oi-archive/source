
# Description

<div class="content"><p><span style="font-size: medium;"><span class="mono prewrap" id="probtext-text">Cow curling is a popular cold-weather sport played in the Moolympics.    Like regular curling, the sport involves two teams, each of which slides N heavy stones (3 &lt;= N &lt;= 50,000) across a sheet of ice.  At the end of the game, there are 2N stones on the ice, each located at a distinct 2D point.   Scoring in the cow version of curling is a bit curious, however.  A stone is said to be &#34;captured&#34; if it is contained inside a triangle whose corners are stones owned by the opponent (a stone on the boundary of such a triangle also counts as being captured).  The score for a team is the number of opponent stones that are captured.    Please help compute the final score of a cow curling match, given the locations of all 2N stones.</span></span></p>
<p></p>
<p></p>
<div>给二维平面n个白点和n个黑点，定义一个点被捕获是在另外一种颜色的某三个点组成的三角形内部(包括边界)，问被捕获的黑白点各有多少</div>
<div></div></div>

# Input

<div class="content"><p><span class="mono prewrap" id="probtext-text">* Line 1: The integer N. </span></p>
<p><span class="mono prewrap" id="probtext-text"> * Lines 2..1+N: Each line contains 2 integers specifying the x and y         coordinates of a stone for team A (each coordinate lies in the         range -40,000 .. +40,000).</span></p>
<p><span class="mono prewrap" id="probtext-text">  * Lines 2+N..1+2N: Each line contains 2 integers specifying the x and         y coordinates of a stone for team B (each coordinate lies in         the range -40,000 .. +40,000).</span></p></div>

# Output

<div class="content"><p>* Line 1: Two space-separated integers, giving the scores for teams A and B.</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 <br/>
0 0 <br/>
0 2 <br/>
2 0 <br/>
2 2 <br/>
1 1 <br/>
1 10 <br/>
-10 3 <br/>
10 3<br/>
<br/>
 INPUT DETAILS: Each team owns 4 stones. Team A has stones at (0,0), (0,2), (2,0), and (2,2), and team B has stones at (1,1), (1,10), (-10,3), and (10,3).</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2 <br/>
<br/>
OUTPUT DETAILS: Team A captures their opponent&#39;s stone at (1,1). Team B captures their opponent&#39;s stones at (0,2) and (2,2).</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

