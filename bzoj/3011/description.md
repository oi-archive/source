
# Description

<div class="content"><p><span style="font-size: medium">It&#39;s milking time at Farmer John&#39;s farm, but the cows have all run away! Farmer John needs to round them all up, and needs your help in the search. FJ&#39;s farm is a series of N (1 &lt;= N &lt;= 200,000) pastures numbered 1...N connected by N - 1 bidirectional paths. The barn is located at pasture 1, and it is possible to reach any pasture from the barn. FJ&#39;s cows were in their pastures this morning, but who knows where they ran to by now. FJ does know that the cows only run away from the barn, and they are too lazy to run a distance of more than L. For every pasture, FJ wants to know how many different pastures cows starting in that pasture could have ended up in. Note: 64-bit integers (int64 in Pascal, long long in C/C++ and long in Java) are needed to store the distance values. </span></p>
<p><span style="font-size: medium">
</span></p><div><font face="system">给出以1号点为根的一棵有根树，问每个点的子树中与它距离小于l的点有多少个。</font></div>
<p></p></div>

# Input

<div class="content"><p><font size="4"> * Line 1: 2 integers, N and L (1 &lt;= N &lt;= 200,000, 1 &lt;= L &lt;= 10^18) </font></p>
<p><font size="4">* Lines 2..N: The ith line contains two integers p_i and l_i. p_i (1 &lt;= p_i &lt; i) is the first pasture on the shortest path between pasture i and the barn, and l_i (1 &lt;= l_i &lt;= 10^12) is the length of that path.</font></p></div>

# Output

<div class="content"><p>* Lines 1..N: One number per line, the number on line i is the number pastures that can be reached from pasture i by taking roads that lead strictly farther away from the barn (pasture 1) whose total length does not exceed L.</p></div>

# Sample Input

<div class="content"><span class="sampledata"> 4 5 <br/>
1 4<br/>
 2 3<br/>
 1 5 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 <br/>
2 <br/>
1<br/>
1<br/>
 OUTPUT DETAILS: Cows from pasture 1 can hide at pastures 1, 2, and 4. Cows from pasture 2 can hide at pastures 2 and 3. Pasture 3 and 4 are as far from the barn as possible, and the cows can hide there. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

