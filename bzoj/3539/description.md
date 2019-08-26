
# Description

<div class="content"><p><span style="font-size: medium"> Farmer John&#39;s cows are on a road trip! The odometer on their car displays an integer mileage value, starting at X (100 &lt;= X &lt;= 10^18) miles at the beginning of their trip and ending at Y (X &lt;= Y &lt;= 10^18) miles at the end of their trip. Whenever the odometer displays an &#39;interesting&#39; number (including at the start and end of the trip) the cows will moo. A number is &#39;interesting&#39; if when you look at all its digits except for leading zeros, at least half of these should be the same. For example, the numbers 3223 and 110 are interesting, while the numbers 97791 and 123 are not. Help FJ count how many times the cows will moo during the trip. </span></p>
<div><span style="font-size: medium"><span style="background: white; color: black">定义”</span><span style="background: white; color: black">有趣的数</span><span style="background: white; color: black">”</span><span style="background: white; color: black">为</span><span style="background: white; color: black">:</span><span style="background: white; color: black">把该数的前缀零去掉后</span><span style="background: white; color: black">,</span><span style="background: white; color: black">存在一个数字使得其出现次数至少为数位总数的一半</span><span style="background: white; color: black">,</span><span style="background: white; color: black">例如3223,110.</span></span></div>
<div><span style="font-size: medium"><span style="background: white; color: black">求[X,Y]</span><span style="background: white; color: black">中有多少个</span><span style="background: white; color: black">”</span><span style="background: white; color: black">有趣的数”.</span></span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: The first line will contain two integers, X and Y, separated by a space. </span></p></div>

# Output

<div class="content"><p><font size="4"> * Line 1: A single integer containing how many times the cows will moo during the trip. </font></p></div>

# Sample Input

<div class="content"><span class="sampledata">110 133 <br/>
<br/>
INPUT DETAILS: The trip starts with the odometer at 110 and ends at 133. <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14 <br/>
OUTPUT DETAILS: The cows moo when the odometer reads 110, 111, 112, 113, 114, 115, 116, 117, 118, 119, 121, 122, 131, and 133. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver  By liyizhen2">Silver  By liyizhen2</a></p></div>

