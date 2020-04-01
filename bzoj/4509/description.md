
# Description

<div class="content"><div>Bessie the cow has designed what she thinks will be the next big hit video game: &#34;Angry Cows&#34;. The premise, which she believes is completely original, is that the player shoots a cow with a slingshot into a one-dimensional scene consisting of a set of hay bales located at various points on a number line; the cow lands with sufficient force to detonate the hay bales in close proximity to her landing site, which in turn might set of a chain reaction that causes additional hay bales to explode. The goal is to use a single cow to start a chain reaction that detonates all the hay bales.</div>
<div>There are NN hay bales located at distinct integer positions x1,x2,…,xNx1,x2,…,xN on the number line. If a cow is launched with power RR landing at position xx, this will causes a blast of &#34;radius RR&#34;, engulfing all hay bales within the range x−R…x+Rx−R…x+R. These hay bales then themselves explode (all simultaneously), each with a blast radius of R−1R−1. Any not-yet-exploded bales caught in these blasts then all explode (all simultaneously) with blast radius R−2R−2, and so on.</div>
<div></div>
<div>Please determine the minimum amount of power RR with which a single cow may be launched so that, if it lands at an appropriate location, it will cause subsequent detonation of every single hay bale in the scene.</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains NN (2≤N≤50,000). The remaining NN lines all contain integers x1…xN (each in the range 0…1,000,000,000).</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Please output the minimum power RR with which a cow must be launched in order to detonate all the hay bales. Answers should be rounded and printed to exactly 1 decimal point.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
8<br/>
10<br/>
3<br/>
11<br/>
1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3.0<br/>
In this example, a cow launched with power 3 at, say, location 5, will cause immediate detonation of hay bales at positions 3 and 8. These then explode (simultaneously) each with blast radius 2, engulfing bales at positions 1 and 10, which next explode (simultaneously) with blast radius 1, engulfing the final bale at position 11, which finally explodes with blast radius 0.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

