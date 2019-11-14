
# Description

<div class="content"><p><span style="font-size: medium">Farmer John&#39;s cows recently received a large piece of marble, which, unfortunately, has a number of imperfections. To describe these, we can represent the piece of marble by an N by N square grid (5 &lt;= N &lt;= 300), where the character &#39;*&#39; represents an imperfection and &#39;.&#39; represents a flawless section of the marble. The cows want to carve a number &#34;8&#34; in this piece of marble (cows are quite fond of the number &#34;8&#34; since they have cloven hooves on each of their four feet, so they can effectively count up to 8 using their &#34;toes&#34;). However, the cows need your help to determine the optimally placed figure eight in the piece of marble. Here are a few properties that define a valid figure eight: * A figure eight consists of two rectangles, a top and a bottom. * Both the top and bottom have at least one cell in their interior. * The bottom edge of the top rectangle is a (not necessarily proper) subset of the top edge of the bottom rectangle. * The figure eight can only be carved from flawless regions of the piece of marble. The aesthetic score of a figure eight is equal to the product of the areas enclosed by its two rectangles. The cows wish to maximize this score. For example, given this piece of marble </span></p>
<p><span style="font-size: medium">...............<br/>
...............<br/>
...*******.....<br/>
.*....*.......*<br/>
.*......*....*.<br/>
....*..........<br/>
...*...****....<br/>
...............<br/>
..**.*..*..*...<br/>
...*...**.*....<br/>
*..*...*.......<br/>
...............<br/>
.....*..*......<br/>
.........*.....<br/>
...............<br/>
<span style="font-size: medium">the optimally placed eight is:</span><br/>
..88888888888..<br/>
..8.........8..<br/>
..8*******..8..<br/>
.*8...*.....8.*<br/>
.*8.....*...8*.<br/>
..8.*.......8..<br/>
..8*...****.8..<br/>
.88888888888888<br/>
.8**.*..*..*..8<br/>
.8.*...**.*...8<br/>
*8.*...*......8<br/>
.8............8<br/>
.8...*..*.....8<br/>
.8.......*....8<br/>
.88888888888888 </span><span style="font-size: medium"> </span></p>
<p><span style="font-size: medium">The top rectangle has area 6x9=54, and the bottom rectangle has area 12x6=72. Thus, its aesthetic score is 54x72=3888. </span></p></div>

# Input

<div class="content"><p><font size="4">* Line 1: A single integer N, indicating the side length of the marble. </font></p>
<p><font size="4">* Lines 2..N+1: Each line describes a row of the marble, and contains N characters which are each either &#39;*&#39; (an imperfection) or &#39;.&#39; (a flawless section). </font></p></div>

# Output

<div class="content"><p> Line 1: The highest aesthetic score of any figure eight which doesn&#39;t use any imperfect squares of the marble. If no figure eight is attainable, then output -1. </p></div>

# Sample Input

<div class="content"><span class="sampledata">15<br/>
...............<br/>
...............<br/>
...*******.....<br/>
.*....*.......*<br/>
.*......*....*.<br/>
....*..........<br/>
...*...****....<br/>
...............<br/>
..**.*..*..*...<br/>
...*...**.*....<br/>
*..*...*.......<br/>
...............<br/>
.....*..*......<br/>
.........*.....<br/>
...............<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"> 3888 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold
">Gold<br/>
</a></p></div>

