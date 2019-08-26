
# Description

<div class="content"><div>Farmer John has N cows that need to be milked (1 &lt;= N &lt;= 10,000), each of which takes only one unit of time to milk. Being impatient animals, some cows will refuse to be milked if Farmer John waits too long to milk them. More specifically, cow i produces g_i gallons of milk (1 &lt;= g_i &lt;= 1000), but only if she is milked before a deadline at time d_i (1 &lt;= d_i &lt;= 10,000). Time starts at t=0, so at most x total cows can be milked prior to a deadline at time t=x. Please help Farmer John determine the maximum amount of milk that he can obtain if he milks the cows optimally. </div>
<div><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">Sinogi有n头牛(1&lt;=n&lt;=10000)，每头牛i可以在时刻d_i之前被挤奶，获得g_i的价值，求最大价值</span></div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>* Line 1: The value of N. </div>
<div>* Lines 2..1+N: Line i+1 contains the integers g_i and d_i.</div>
<p></p></div>

# Output

<div class="content"><p>* Line 1: The maximum number of gallons of milk Farmer John can obtain.</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
10 3<br/>
7 5<br/>
8 1<br/>
2 1<br/>
INPUT DETAILS: There are 4 cows. The first produces 10 gallons of milk if milked by time 3, and so on.</span></div>

# Sample Output

<div class="content"><span class="sampledata">25<br/>
OUTPUT DETAILS: Farmer John milks cow 3 first, giving up on cow 4 since she cannot be milked by her deadline due to the conflict with cow 3. Farmer John then milks cows 1 and 2.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver 鸣谢duan2提供译文">Silver 鸣谢duan2提供译文</a></p></div>

