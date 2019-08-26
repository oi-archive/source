
# Description

<div class="content"><div class="problem-text" align="left"><span style="font-size: medium"><span class="mono prewrap" id="probtext-text">  Bessie and her bovine pals from nearby farms have finally decided that they are going to start connecting their farms together by trails in an effort to form an alliance against the farmers. The cows in each of the N (1 &lt;= N &lt;= 100,000) farms were initially instructed to build a trail to exactly one other farm, for a total of N trails. However months into the project only M (1 &lt;= M &lt; N) of these trails had actually been built. Arguments between the farms over which farms already built a trail now threaten to split apart the cow alliance. To ease tension, Bessie wishes to calculate how many ways the M trails that exist so far could have been built. For example, if there is a trail connecting farms 3 and 4, then one possibility is that farm 3 built the trail, and the other possibility is that farm 4 built the trail. Help Bessie by calculating the number of different assignments of trails to the farms that built them, modulo 1,000,000,007. Two assignments are considered different if there is at least one trail built by a different farm in each assignment. </span></span></div>
<div class="problem-text" align="left"></div>
<div class="problem-text" align="left"><span class="Apple-style-span" style="font-family: simsun; font-size: 14px; color: rgb(70, 70, 70); line-height: 21px; ">给出n个点m条边的图，现把点和边分组，每条边只能和相邻两点之一分在一组，点可以单独一组，问分组方案数。</span></div></div>

# Input

<div class="content"><p><font size="4">* Line 1: Two space-separated integers N and M</font></p>
<p><font size="4"> * Lines 2..1+M: Line i+1 describes the ith trail. Each line contains two space-separated integers u_i and v_i (1 &lt;= u_i, v_i &lt;= N, u_i != v_i) describing the pair of farms connected by the trail.  Note that there can be two trails between the same pair of farms. </font></p></div>

# Output

<div class="content"><p><font size="4">* Line 1: A single line containing the number of assignments of trails to farms, taken modulo 1,000,000,007. If no assignment satisfies the above conditions output 0.</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 4 <br/>
1 2<br/>
 3 2<br/>
 4 5<br/>
 4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 6 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">OUTPUT DETAILS: There are 6 possible assignments. Letting {a,b,c,d} mean that farm 1 builds trail a, farm 2 builds trail b, farm 3 builds trail c, and farm 4 builds trail d, the assignments are: {2, 3, 4, 5} {2, 3, 5, 4} {1, 3, 4, 5} {1, 3, 5, 4} {1, 2, 4, 5} {1, 2, 5, 4} </span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

