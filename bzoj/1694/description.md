
# Description

<div class="content">
A long, linear field has N (1 &lt;= N &lt;= 1,000) clumps of grass at
unique integer locations on what will be treated as a number line.
Think of the clumps as points on the number line.

Bessie starts at some specified integer location L on the number
line (1 &lt;= L &lt;= 1,000,000) and traverses the number line in the two
possible directions (sometimes reversing her direction) in order
to reach and eat all the clumps.  She moves at a constant speed
(one unit of distance in one unit of time), and eats a clump instantly
when she encounters it.

Clumps that aren&#39;t eaten for a while get stale.  We say the
``staleness&#39;&#39; of a clump is the amount of time that elapses from
when Bessie starts moving until she eats a clump.  Bessie wants to
minimize the total staleness of all the clumps she eats.

Find the minimum total staleness that Bessie can achieve while
eating all the clumps.

</div>

# Input

<div class="content">* Line 1 : Two space-separated integers: N and L.

* Lines 2..N+1: Each line contains a single integer giving the
        position P of a clump (1 &lt;= P &lt;= 1,000,000).

</div>

# Output

<div class="content">
* Line 1: A single integer: the minimum total staleness Bessie can
        achieve while eating all the clumps.
</div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
4 10<br/>
1<br/>
9<br/>
11<br/>
19<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Four clumps: at 1, 9, 11, and 19. Bessie starts at location 10.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
44<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Bessie can follow this route:<br/>
<br/>
* start at position 10 at time 0<br/>
* move to position 9, arriving at time 1<br/>
* move to position 11, arriving at time 3<br/>
* move to position 19, arriving at time 11<br/>
* move to position 1, arriving at time 29<br/>
<br/>
giving her a total staleness of 1+3+11+29 = 44.  There are other routes<br/>
with the same total staleness, but no route with a smaller one.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

