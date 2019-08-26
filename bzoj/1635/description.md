
# Description

<div class="content"><p><span style="font-size: medium">FJ&#39;s N (1 &lt;= N &lt;= 10,000) cows conveniently indexed 1..N are standing in a line. Each cow has a positive integer height (which is a bit of secret). You are told only the height H (1 &lt;= H &lt;= 1,000,000) of the tallest cow along with the index I of that cow. FJ has made a list of R (0 &lt;= R &lt;= 10,000) lines of the form &#34;cow 17 sees cow 34&#34;. This means that cow 34 is at least as tall as cow 17, and that every cow between 17 and 34 has a height that is strictly smaller than that of cow 17. For each cow from 1..N, determine its maximum possible height, such that all of the information given is still correct. It is guaranteed that it is possible to satisfy all the constraints. </span></p>
<p><span style="font-size: medium">有n(1 &lt;= n &lt;= 10000)头牛从１到n线性排列，每头牛的高度为h[i](1 &lt;= i &lt;= n),现在告诉你这里面的牛的最大高度为maxH,而且有r组关系，每组关系输入两个数字，假设为a和b,表示第a头牛能看到第b头牛，能看到的条件是a, b之间的其它牛的高度都严格小于min(h[a], h[b]),而h[b] &gt;= h[a]</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Four space-separated integers: N, I, H and R</span></p>
<p><span style="font-size: medium"> * Lines 2..R+1: Two distinct space-separated integers A and B (1 &lt;= A, B &lt;= N), indicating that cow A can see cow B.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Lines 1..N: Line i contains the maximum possible height of cow i. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">9 3 5 5<br/>
1 3<br/>
5 3<br/>
4 3<br/>
3 7<br/>
9 8<br/>
<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
There are 9 cows, and the 3rd is the tallest with height 5.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
4<br/>
5<br/>
3<br/>
4<br/>
4<br/>
5<br/>
5<br/>
5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

