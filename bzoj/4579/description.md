
# Description

<div class="content"><div>Farmer John and his cows are planning to leave town for a long vacation, and so FJ wants to temporar</div>
<div>ily close down his farm to save money in the meantime.The farm consists of NN barns connected with M</div>
<div>M bidirectional paths between some pairs of barns (1≤N,M≤200,000). To shut the farm down, FJ plans</div>
<div> to close one barn at a time. When a barn closes, all paths adjacent to that barn also close, and ca</div>
<div>n no longer be used.FJ is interested in knowing at each point in time (initially, and after each clo</div>
<div>sing) whether his farm is &#34;fully connected&#34; -- meaning that it is possible to travel from any open b</div>
<div>arn to any other open barn along an appropriate series of paths. Since FJ&#39;s farm is initially in som</div>
<div>ewhat in a state of disrepair, it may not even start out fully connected.</div>
<div><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">给你N点M边的无向图(1&lt;=N,M&lt;=200000)，一共删n次点，</span></div>
<div><span style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 15.549334526062px;">每次询问删这个点之前是否完全联通</span></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N and M. The next M lines each describe a path in terms of the pair</div>
<div> of barns it connects (barns are conveniently numbered 1…N). The final N lines give a permutation o</div>
<div>f 1…N describing the order in which the barns will be closed.</div>
<p></p></div>

# Output

<div class="content"><div>The output consists of N lines, each containing &#34;YES&#34; or &#34;NO&#34;. The first line indicates whether the </div>
<div>initial farm is fully connected, and line i+1 indicates whether the farm is fully connected after th</div>
<div>e iith closing.</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
1 2<br/>
2 3<br/>
3 4<br/>
3<br/>
4<br/>
1<br/>
2</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
NO<br/>
YES<br/>
YES</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold 鸣谢duan2提供译文">Gold 鸣谢duan2提供译文</a></p></div>

