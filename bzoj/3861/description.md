
# Description

<div class="content"><div>Teacher Mai has a directed graph with n nodes and n edges. This graph is special: Out degree of each node is 1, and there is no self loop.</div>
<div></div>
<div>For every node Teacher Mai wrote down a set of nodes which directly links to this node.</div>
<div></div>
<div>For example, the graph contains 4 edges: {1-&gt;2,2-&gt;4,3-&gt;1,4-&gt;1}, the set of each node is {3,4},{1},{},{2}</div>
<div></div>
<div>But Teacher Mai found that he forgot writing which node the set belonged to.</div>
<div></div>
<div>Teacher Mai wanted to recover it, but he found there are many graphs with the same node sets.</div>
<div></div>
<div>You should count the number of different graphs have the same node sets as the given one.</div>
<div></div>
<div>The number can be very large, just output the number modulo 1000000007 (10^9+7).</div>
<div></div>
<div>If there is no solution, the answer is 0.</div>
<p></p></div>

# Input

<div class="content"><div>There are multiple test cases, terminated by a line &#34;0&#34;.</div>
<div>
<div></div>
<div>For each test case, the first line contains a integer n (1&lt;=n&lt;=1000).</div>
<div></div>
<div>The following are n lines representing the set of each node. For every line, there is a integer p first, indicating the size of the set. Then there are p integers, indicating the node with index from 1 to n in this set.</div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>For each test case, output one line &#34;Case #k: ans&#34;, where k is the case number, counting from 1, ans is the number module 10^9+7.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
1 1<br/>
0<br/>
0<br/>
0<br/>
2 2 3<br/>
3 4 5 6<br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 38<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

