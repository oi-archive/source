
# Description

<div class="content">
Due to recent rains, water has pooled in various places in Farmer
John&#39;s field, which is represented by a rectangle of N x M (1 &lt;= N
&lt;= 100; 1 &lt;= M &lt;= 100) squares. Each square contains either water
(&#39;W&#39;) or dry land (&#39;.&#39;).  Farmer John would like to figure out how
many ponds have formed in his field.  A pond is a connected set of
squares with water in them, where a square is considered adjacent
to all eight of its neighbors.

Given a diagram of Farmer John&#39;s field, determine how many ponds he has.

</div>

# Input

<div class="content">
* Line 1: Two space-separated integers: N and M

* Lines 2..N+1: M characters per line representing one row of Farmer
        John&#39;s field.  Each character is either &#39;W&#39; or &#39;.&#39;.  The
        characters do not have spaces between them.

</div>

# Output

<div class="content">
* Line 1: The number of ponds in Farmer John&#39;s field.

</div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
10 12<br/>
W........WW.<br/>
.WWW.....WWW<br/>
....WW...WW.<br/>
.........WW.<br/>
.........W..<br/>
..W......W..<br/>
.W.W.....WW.<br/>
W.W.W.....W.<br/>
.W.W......W.<br/>
..W.......W.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
3<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
There are three ponds: one in the upper left, one in the lower left,<br/>
and one along the right side.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

