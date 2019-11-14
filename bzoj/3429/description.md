
# Description

<div class="content"><p><span style="font-size: medium;"><span class="mono prewrap" id="probtext-text"> Farmer John is helping to turn his large field into a ski course for the upcoming winter Moolympics.  The field has dimensions M x N (1 &lt;= M,N &lt;= 100), and its intended final composition is described by an M x N grid of characters like this:  RSRSSS RSRSSS RSRSSS  Each character describes how the snow in a unit square of the field should be groomed: either &#39;R&#39; for &#39;rough&#39; or &#39;S&#39; for &#39;smooth&#39; (the Moolympics organizers think that a course is more interesting if it has a mixture of rough and smooth patches).    To build the desired course, Farmer John plans to modify his tractor so that it can stamp any B x B patch of the field (B &lt;= M, B &lt;= N) with either entirely smooth snow or entirely rough snow.  Since it takes a long time to reset the tractor between each of these stamps, FJ wants to make B as large as possible.  With B = 1, he can clearly create the desired ski course by stamping each individual square with either R or S, as intended.  However, for larger values of B, it may no longer be possible to create the desired course design.  Every unit square of the course must at some point be stamped by FJ&#39;s tractor; it cannot be left in its default state.  Please help FJ determine the largest possible value of B he can successfully use.</span></span></p>
<p>定一个n*m的矩阵的目标状态(每个格子是R或S的一种)，初始时格子状态未知，为了达到目标状态，你可以选择一个数b，可以多次将一个b*b的的子矩阵全部改成R或S，问能从初始达成目标状态的最大的b是多少。注意每个格子至少要被修改一次。</p></div>

# Input

<div class="content"><p><span style="font-size: medium;"><span class="mono prewrap" id="probtext-text">* Line 1: Two space-separated integers M and N.  </span></span></p>
<p><span style="font-size: medium;"><span class="mono prewrap" id="probtext-text">* Lines 2..M+1: M lines of exactly N characters (each R or S),         describing the desired ski course design. </span></span></p></div>

# Output

<div class="content"><p><span style="font-size: medium;"><span class="mono prewrap" id="probtext-text">* Line 1: The maximum value of B Farmer John can use to create the         desired course pattern.</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 6 <br/>
RSRSSS <br/>
RSRSSS <br/>
RSRSSS</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 <br/>
<br/>
OUTPUT DETAILS: FJ can stamp a rough patch spanning columns 1-3, followed by a smooth<br/>
 patch spanning columns 2-4, then a rough patch spanning columns 3-5, and finally a smooth <br/>
patch spanning columns 4-6.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

