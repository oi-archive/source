
# Description

<div class="content"><img border="0" src="/source/bzoj/1954/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5NTQuanBn.jpg"/> 
给定一棵n个点的带权树，求树上最长的异或和路径</div>

# Input

<div class="content">The input contains several test cases. The first line of each test case contains an integer n(1&lt;=n&lt;=100000), The following n-1 lines each contains three integers u(0 &lt;= u &lt; n),v(0 &lt;= v &lt; n),w(0 &lt;= w &lt; 2^31), which means there is an edge between node u and v of length w. 
</div>

# Output

<div class="content">For each test case output the xor-length of the xor-longest path.
</div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2 3<br/>
2 3 4<br/>
2 4 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
<br/>
</span></div>

# Hint

<div class="content"><p>The xor-longest path is 1-&gt;2-&gt;3, which has length 7 (=3 ⊕ 4) <br/>
注意：结点下标从1开始到N....</p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢陶文博">鸣谢陶文博</a></p></div>

