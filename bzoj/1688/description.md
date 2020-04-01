
# Description

<div class="content"><p><span style="font-size: medium">Alas! A set of D (1 &lt;= D &lt;= 15) diseases (numbered 1..D) is running through the farm. Farmer John would like to milk as many of his N (1 &lt;= N &lt;= 1,000) cows as possible. If the milked cows carry more than K (1 &lt;= K &lt;= D) different diseases among them, then the milk will be too contaminated and will have to be discarded in its entirety. Please help determine the largest number of cows FJ can milk without having to discard the milk. </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Three space-separated integers: N, D, and K * Lines 2..N+1: Line i+1 describes the diseases of cow i with a list of 1 or more space-separated integers. The first integer, d_i, is the count of cow i&#39;s diseases; the next d_i integers enumerate the actual diseases. Of course, the list is empty if d_i is 0. 有N头牛,它们可能患有D种病,现在从这些牛中选出若干头来,但选出来的牛患病的集合中不过超过K种病.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: M, the maximum number of cows which can be milked. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 3 2<br/>
0---------第一头牛患0种病<br/>
1 1------第二头牛患一种病,为第一种病.<br/>
1 2<br/>
1 3<br/>
2 2 1<br/>
2 2 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
If FJ milks cows 1, 2, 3, 5, and 6, then the milk will have only two<br/>
diseases (#1 and #2), which is no greater than K (2). <br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

