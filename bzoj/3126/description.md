
# Description

<div class="content"><p><span style="font-size: medium">Farmer John has decided to assemble a panoramic photo of a lineup of his N cows (1 &lt;= N &lt;= 200,000), which, as always, are conveniently numbered from 1..N. Accordingly, he snapped M (1 &lt;= M &lt;= 100,000) photos, each covering a contiguous range of cows: photo i contains cows a_i through b_i inclusive. The photos collectively may not necessarily cover every single cow. After taking his photos, FJ notices a very interesting phenomenon: each photo he took contains exactly one cow with spots! FJ was aware that he had some number of spotted cows in his herd, but he had never actually counted them. Based on his photos, please determine the maximum possible number of spotted cows that could exist in his herd. Output -1 if there is no possible assignment of spots to cows consistent with FJ&#39;s photographic results. </span></p>
<p></p>
<p><span style="font-size: medium">给你一个n长度的数轴和m个区间，每个区间里有且仅有一个点，问能有多少个点</span></p></div>

# Input

<div class="content"><p><font size="4"> * Line 1: Two integers N and M. </font></p>
<p><font size="4">* Lines 2..M+1: Line i+1 contains a_i and b_i.</font></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The maximum possible number of spotted cows on FJ&#39;s farm, or -1 if there is no possible solution. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 3<br/>
1 4<br/>
2 5<br/>
3 4<br/>
<br/>
 INPUT DETAILS: There are 5 cows and 3 photos. The first photo contains cows 1 through 4, etc.</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
 OUTPUT DETAILS: From the last photo, we know that either cow 3 or cow 4 must be spotted. By choosing either of these, we satisfy the first two photos as well. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

