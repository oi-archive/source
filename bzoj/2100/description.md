
# Description

<div class="content"><p>Bessie has two crisp red apples to deliver to two of her friends in the herd. Of course, she travels the C (1 &lt;= C &lt;= 200,000) cowpaths which are arranged as the usual graph which connects P (1 &lt;= P &lt;= 100,000) pastures conveniently numbered from 1..P: no cowpath leads from a pasture to itself, cowpaths are bidirectional, each cowpath has an associated distance, and, best of all, it is always possible to get from any pasture to any other pasture. Each cowpath connects two differing pastures P1_i (1 &lt;= P1_i &lt;= P) and P2_i (1 &lt;= P2_i &lt;= P) with a distance between them of D_i. The sum of all the distances D_i does not exceed 2,000,000,000. What is the minimum total distance Bessie must travel to deliver both apples by starting at pasture PB (1 &lt;= PB &lt;= P) and visiting pastures PA1 (1 &lt;= PA1 &lt;= P) and PA2 (1 &lt;= PA2 &lt;= P) in any order. All three of these pastures are distinct, of course. Consider this map of bracketed pasture numbers and cowpaths with distances: <img border="0" alt="" src="/source/bzoj/2100/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIxMDAuanBn.jpg"/> If Bessie starts at pasture [5] and delivers apples to pastures [1] and [4], her best path is: 5 -&gt; 6-&gt; 7 -&gt; 4* -&gt; 3 -&gt; 2 -&gt; 1* with a total distance of 12.</p>
<div style="clear: both; table-layout: fixed; margin: 10px 30px; overflow: auto; word-break: break-all; white-space: normal; text-align: left">一张P个点的无向图，C条正权路。<br/>
CLJ要从Pb点（家）出发，既要去Pa1点NOI赛场拿金牌，也要去Pa2点CMO赛场拿金牌。（途中不必回家）<br/>
可以先去NOI，也可以先去CMO。<br/>
当然神犇CLJ肯定会使总路程最小，输出最小值。</div></div>

# Input

<div class="content"><p>* Line 1: Line 1 contains five space-separated integers: C, P, PB, PA1, and PA2 * Lines 2..C+1: Line i+1 describes cowpath i by naming two pastures it connects and the distance between them: P1_i, P2_i, D_i</p></div>

# Output

<div class="content"><p>* Line 1: The shortest distance Bessie must travel to deliver both apples</p></div>

# Sample Input

<div class="content"><span class="sampledata">9 7 5 1 4<br/>
5 1 7<br/>
6 7 2<br/>
4 7 2<br/>
5 6 1<br/>
5 2 4<br/>
4 3 2<br/>
1 2 3<br/>
3 2 2<br/>
2 6 3<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">12<br/>
</span></div>

# Hint

<div class="content"><p></p><p>求翻译.........站内PM我吧.........</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

