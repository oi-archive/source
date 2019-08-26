
# Description

<div class="content"><p><span style="font-size: medium; ">Oh those picky N (1 &lt;= N &lt;= 50,000) cows! They are so picky that each one will only be milked over some precise time interval A..B (1 &lt;= A &lt;= B &lt;= 1,000,000), which includes both times A and B.  Obviously, FJ must create a reservation system to determine which stall each cow can be assigned for her milking time. Of course, no cow will share such a private moment with other cows.  Help FJ by determining: * The minimum number of stalls required in the barn so that each   cow can have her private milking period * An assignment of cows to these stalls over time  </span></p>
<p><span style="font-size: medium; ">有N头牛,每头牛有个喝水时间,这段时间它将专用一个Stall 现在给出每头牛的喝水时间段,问至少要多少个Stall才能满足它们的要求</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium; ">* Line 1: A single integer, N </span></p>
<p><span style="font-size: medium; "> * Lines 2..N+1: Line i+1 describes cow i&#39;s milking interval with two         space-separated integers.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium; ">* Line 1: The minimum number of stalls the barn must have.</span></p>
<p><span style="font-size: medium; ">  * Lines 2..N+1: Line i+1 describes the stall to which cow i will be         assigned for her milking period.</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 10<br/>
2 4<br/>
3 6<br/>
5 8<br/>
4 7<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
Here&#39;s a graphical schedule for this output:<br/>
<br/>
Time     1  2  3  4  5  6  7  8  9 10<br/>
Stall 1 c1&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;<br/>
Stall 2 .. c2&gt;&gt;&gt;&gt;&gt;&gt; c4&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt; .. ..<br/>
Stall 3 .. .. c3&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt; .. .. .. ..<br/>
Stall 4 .. .. .. c5&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt;&gt; .. .. ..<br/>
<br/>
Other outputs using the same number of stalls are possible.</span></div>

# Hint

<div class="content"><p></p><p>不妨试下这个数据,对于按结束点SORT,再GREEDY的做法 1 3 5 7 6 9 10 11 8 12 4 13 正确的输出应该是3</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

