
# Description

<div class="content"><p><span style="font-size: medium"> Farmer John&#39;s N cows (1 &lt;= N &lt;= 50,000) are grazing along a one-dimensional fence. Cow i is standing at location x(i) and has height h(i) (1 &lt;= x(i),h(i) &lt;= 1,000,000,000). A cow feels &#34;crowded&#34; if there is another cow at least twice her height within distance D on her left, and also another cow at least twice her height within distance D on her right (1 &lt;= D &lt;= 1,000,000,000). Since crowded cows produce less milk, Farmer John would like to count the number of such cows. Please help him. </span></p>
<p><span style="font-size: medium">N头牛在一个坐标轴上，每头牛有个高度。现给出一个距离值D。</span></p>
<p><span style="font-size: medium">如果某头牛在它的左边，在距离D的范围内，如果找到某个牛的高度至少是它的两倍，且在右边也能找到这样的牛的话。则此牛会感觉到不舒服。</span></p>
<p><span style="font-size: medium">问有多少头会感到不舒服。</span></p></div>

# Input

<div class="content"><p><font size="4">* Line 1: Two integers, N and D. </font></p>
<p><font size="4">* Lines 2..1+N: Line i+1 contains the integers x(i) and h(i). The locations of all N cows are distinct. </font></p></div>

# Output

<div class="content"><p><font size="4">* Line 1: The number of crowded cows. </font></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 4<br/>
10 3<br/>
6 2<br/>
5 3<br/>
9 7<br/>
3 6<br/>
11 2<br/>
<br/>
 INPUT DETAILS: There are 6 cows, with a distance threshold of 4 for feeling crowded. Cow #1 lives at position x=10 and has height h=3, and so on.</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 <br/>
OUTPUT DETAILS: The cows at positions x=5 and x=6 are both crowded. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

