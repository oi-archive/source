
# Description

<div class="content"><div>Teacher Mai has solved the #P complete in polynomial time recently.</div>
<div></div>
<div>So he gives this task to you. You are given a matrix of n rows and n columns, you should calculate the permanent of this.</div>
<div></div>
<div>But this matrix is special, nearly all the elements are 1. Only the cells on the main diagonal are modified.</div>
<div></div>
<div>You are given n integers ai. You should calculate permanents of m matrices. The size of i-th matrix is n+i-1.</div>
<div></div>
<div>In i-th matrix,</div>
<div></div>
<div></div>
<div><img src="source/bzoj/3860/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMS8xMTEuanBn.jpg" width="236" height="70" alt=""/></div>
<div>The number can be very large, just output the number modulo 998244353.</div>
<div></div>
<div>If you don&#39;t know what is the permanent of a matrix, please click http://en.wikipedia.org/wiki/Permanent or http://baike.baidu.com/view/8212164.htm</div>
<p></p></div>

# Input

<div class="content"><div>There are multiple test cases, terminated by a line &#34;0 0&#34;.</div>
<div></div>
<div>For each test case, the first line contains two integers n,m(1&lt;=n,m&lt;=10^5).</div>
<div></div>
<div>The following one line contains n integers ai,(0&lt;=ai&lt;=10^6).</div>
<p></p></div>

# Output

<div class="content"><div>For each test case, first output one line &#34;Case #k:&#34;, where k is the case number counting from 1.</div>
<div>
<div></div>
<div>The following k lines contains a integer, indicating the permanent of the i-th matrix.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 2<br/>
2 3 3<br/>
0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1:<br/>
28<br/>
46<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

