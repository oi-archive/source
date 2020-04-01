
# Description

<div class="content"><p>Farmer John is decorating his Spring Equinox Tree (like a Christmas tree but popular about three months later). It can be modeled as a rooted mathematical tree with N (1 &lt;= N &lt;= 100,000) elements, labeled 1...N, with element 1 as the root of the tree. Each tree element e &gt; 1 has a parent, P_e (1 &lt;= P_e &lt;= N). Element 1 has no parent (denoted &#39;-1&#39; in the input), of course, because it is the root of the tree. Each element i has a corresponding subtree (potentially of size 1) rooted there. FJ would like to make sure that the subtree corresponding to element i has a total of at least C_i (0 &lt;= C_i &lt;= 10,000,000) ornaments scattered among its members. He would also like to minimize the total amount of time it takes him to place all the ornaments (it takes time K*T_i to place K ornaments at element i (1 &lt;= T_i &lt;= 100)). Help FJ determine the minimum amount of time it takes to place ornaments that satisfy the constraints.  Note that this answer might not fit into a 32-bit integer, but it will fit into a signed 64-bit integer. For example, consider the tree below where nodes located higher on the display are parents of connected lower nodes (1 is the root):</p>
<p><img border="0" src="/source/bzoj/2197/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIxOTdfMS5qcGc=.jpg" alt=""/></p>
<p>Suppose that FJ has the following subtree constraints:</p>
<p><img border="0" src="/source/bzoj/2197/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIxOTdfMi5qcGc=.jpg" alt=""/></p>
<p>Then FJ can place all the ornaments as shown below, for a total cost of 20:</p>
<p><img border="0" src="/source/bzoj/2197/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIxOTdfMy5qcGc=.jpg" alt=""/></p>
<p>FJ要装饰一棵Spring Equinox树（N个节点，标号为1--N，1为根节点）。 </p>
<p><img border="0" src="/source/bzoj/2197/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzIxOTdfNC5qcGc=.jpg" alt=""/></p></div>

# Input

<div class="content"><p>* Line 1: A single integer: N  * Lines 2..N+1: Line i+1 contains three space-separated integers: P_i,         C_i, and</p>
<p>T_i</p>
<p> 第一行：N -----代表N个节点 接下来N行 每行三个数P_i -----i的父亲节点 C_i ----以i为根节点的子树需要至少C_i个装饰品 T_i ----在i这个节点挂一个装饰品需要T_i的时间 </p></div>

# Output

<div class="content"><p>* Line 1: A single integer: The minimum time to place all the         ornaments</p>
<p>挂上所有装饰品所需要的总时间</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
-1 9 3<br/>
1 2 2<br/>
5 3 2<br/>
5 1 4<br/>
2 3 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">20<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

