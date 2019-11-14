
# Description

<div class="content">

After he partitioned his farm into R (1 &lt;= R &lt;= 200) rows and C (1
&lt;= C &lt;= 200) squares conveniently labeled 1,1 through R,C, Farmer
John spent days cutting the hay and stacking a huge amount of it
in square 1,1. He then undertook the task of mapping out the N (1
&lt;= N &lt;= 80,000) haypaths through the farm so that he could deduce
the maximum rate he could move hay from square 1,1 to square R,C.

Each haypath uniquely connects the middle of two rectilinearly
adjacent partitioned squares and has some capacity limit L_i (1 &lt;=
L_i &lt;= 20,000,000) that is the maximum amount of hay that can be
transported in either direction across the haypath.  He&#39;s just
positive that he can move hay at a reasonable rate to the other
side of the farm but he doesn&#39;t know what the fastest rate is. Help
him learn it.
</div>

# Input

<div class="content">* Line 1: Three separated integers: R, C, and N
* Lines 2..N+1: Line i+1 describes path i with five space-separated
        integers: r1, c1, r2, c2, and L_i which denote a haypath
        connecting (r1,c1) to (r2,c2) with capacity L_i.

</div>

# Output

<div class="content">
* Line 1: One number, on a line by itself, the maximum amount of
        material which can be transported from (1,1) to (R,C)
        simultaneously.
</div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3 3 8<br/>
1 1 1 2 5<br/>
1 1 2 1 3<br/>
1 2 2 2 5<br/>
2 1 2 2 2<br/>
2 2 2 3 1<br/>
2 2 3 2 6<br/>
2 3 3 3 4<br/>
3 2 3 3 7<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
The grid is as follows:<br/>
*--5--* . . *<br/>
|     |     <br/>
3     5     :<br/>
|     |    <br/>
*--2--*--1--*<br/>
      |     |<br/>
:     6     4<br/>
      |     |<br/>
* . . *--7--*<br/>
    <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
<br/>
</span></div>

# Hint

<div class="content"><p><br/>
Consider the two edges coming out of (2,2), at most 6+1=7 units of hay can<br/>
be transported. This is indeed feasible.<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

