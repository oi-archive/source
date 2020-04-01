
# Description

<div class="content"><div>Farmer John is continuing to ponder the issue of cows crossing the road through his farm, introduced</div>
<div> in the preceding problem. He realizes that interaction between some pairs of breeds is actually acc</div>
<div>eptable if the breeds are friendly, a property that turns out to be easily characterized in terms of</div>
<div> breed ID: breeds aa and bb are friendly if |a-b|≤4, and unfriendly otherwise. It is ok for cows to</div>
<div> wander into fields designated for other breeds, as long as they are friendly.Given the ordering of </div>
<div>N fields on both sides of the road through FJ&#39;s farm (again, with exactly one field for each breed o</div>
<div>n each side), please help FJ determine the maximum number of crosswalks he can draw over his road, s</div>
<div>uch that no two intersect, and such that each crosswalk joins a pair of fields containing two breeds</div>
<div> that are friendly. Each field can be accessible via at most one crosswalk (so crosswalks don&#39;t meet</div>
<div> at their endpoints).</div>
<div>
<div>上下有两个长度为n、位置对应的序列A、B，</div>
<div>其中数的范围均为1~n。若abs(A[i]-B[j]) &lt;= 4，</div>
<div>则A[i]与B[j]间可以连一条边。现要求在边与边不相交的情况下的最大的连边数量。</div>
<div>n &lt;= 10^6</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N (1≤N≤100,0000). </div>
<div>The next N lines describe the order, by breed ID, of fields on one side of the road; </div>
<div>each breed ID is an integer in the range 1…N </div>
<div>The last N lines describe the order, by breed ID, of the fields on the other side of the road. </div>
<div>Each breed ID appears exactly once in each ordering.</div>
<div>注意:<span style="font-family: arial, verdana, helvetica, sans-serif;">两个序列都是全排列</span></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Please output the maximum number of disjoint &#34;friendly crosswalks&#34; Farmer John can draw across the road.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1<br/>
2<br/>
3<br/>
4<br/>
5<br/>
6<br/>
6<br/>
5<br/>
4<br/>
3<br/>
2<br/>
1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

