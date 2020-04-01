
# Description

<div class="content"><div>After beats all opponents in 3-dimension-world OI, ZCC feels bored and sets about going to other universes. In a universe with D dimension(s), ZCC finds D segments floating in the air. To be more precise: if we build a rectangular coordinate system with D axis, each of the segments is parallel with one axis, whose endpoints have a coordination of which all components belong to the set {x∈Z|0≤x＜N}. For each axis, there is exactly one segment parallel with it.</div>
<div>Each of the D segments changes location every second. Read the pseudo code below for more details:</div>
<div><img src="/source/bzoj/3841/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMS9hYS5qcGc=.jpg" width="555" height="290" alt=""/></div>
<div></div>
<div></div>
<div></div>
<div>Every second, from every pair of segments intersect, ZCC acquires a unit of Energy. Calculate the Expectation of the amount of the acquired energy per second please.</div>
<p></p></div>

# Input

<div class="content"><div>There are several test cases in one input file. EOF indicates the end of input file.</div>
<div>Every test case contain two positive numbers N, D in one line.</div>
<div>It is guaranteed that 1＜N≤10^9, D≤99. The number of test cases≤10.</div>
<p></p></div>

# Output

<div class="content"><div>
<div>For each test case, output a line with an integer or an irreducible fraction p/q, which is the Expectation.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
3 3<br/>
5 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
49/81<br/>
18/625</span></div>

# Hint

<div class="content"><p></p><div>For the first test case of the sample input, there are 2 segments in a 2*2 lattice.</div><br/>
<div>Because two endpoint couldn’t coincide, two segments must be (0,y)-(1,y) and (x,0)-(x,1). (x, y∈{0,1}) </div><br/>
<div>Thus, they always intersect at (x,y). As an irreducible fraction the answer is 1/1, where q = 1, so we should output an integer 1 instead.</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

