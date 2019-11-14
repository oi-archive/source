
# Description

<div class="content"><p><span style="font-size: medium">Farmer John has N (1 &lt;= N &lt;= 25,000) rectangular barns on his farm, all with sides parallel to the X and Y axes and integer corner coordinates in the range 0..1,000,000. These barns do not overlap although they may share corners and/or sides with other barns. Since he has extra cows to milk this year, FJ would like to expand some of his barns. A barn has room to expand if it does not share a corner or a wall with any other barn. That is, FJ can expand a barn if all four of its walls can be pushed outward by at least some amount without bumping into another barn. If two barns meet at a corner, neither barn can expand. Please determine how many barns have room to expand. </span></p>
<div><span style="font-size: medium">    约翰有N(1≤N≤25000)个矩形牛棚，它们的墙均与坐标轴平行，而且其坐标在[o，1061范围内．任意两个牛棚不重叠，但可能会有公共的墙． 由于约翰的奶牛持续增加，他不得不考虑扩张牛棚．一个牛棚可以扩张，当且仅当它的四边均不与其它牛棚接触．如果两个牛棚有一个公共角，那它们均是不可扩张的．统计有多少牛棚可以扩张．</span></div></div>

# Input

<div class="content"><p>* Line 1: A single integer, N</p>
<p>* Lines 2..N+1: Four space-separated integers A, B, C, and D, describing one barn. The lower-left corner of the barn is at (A,B) and the upper right corner is at (C,D).</p>
<p></p>
<div><span style="font-size: medium">    第1行输入N，之后N行每行输入一个牛棚的左下角和右上角坐标．</span></div>
<div><span style="font-size: medium">输出说明</span></div>
<div><span style="font-size: medium">   </span></div></div>

# Output

<div class="content"><p>* Line 1: A single integer that is the number of barns that can be expanded.</p>
<p><font size="4"> 输出可扩张的牛棚数．</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
0 2 2 7<br/>
3 5 5 8<br/>
4 2 6 4<br/>
6 1 8 6<br/>
0 0 8 1<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
There are 5 barns.  The first barn has its lower-left corner at (0,2) and<br/>
its upper-right corner at (2,7), and so on.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
仅有前两个牛棚可以扩张．</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

