
# Description

<div class="content"><div>There is an old country and the king fell in love with a devil. The devil always asks the king to do some crazy things. Although the king used to be wise and beloved by his people. Now he is just like a boy in love and can’t refuse any request from the devil. Also, this devil is looking like a very cute Loli.</div>
<div></div>
<div>The devil likes to make thing in chaos. This kingdom’s road system is like simply a tree(connected graph without cycle). A road has a color of black or white. The devil often wants to make some change of this system.</div>
<div></div>
<div>In details, we call a path on the tree from a to b consists of vertices lie on the shortest simple path between a and b. And we say an edge is on the path if both its two endpoints is in the path, and an edge is adjacent to the path if exactly one endpoint of it is in the path.</div>
<div></div>
<div>Sometimes the devil will ask you to reverse every edge’s color on a path or adjacent to a path.</div>
<div></div>
<div>The king’s daughter, WJMZBMR, is also a cute loli, she is surprised by her father’s lolicon-like behavior. As she is concerned about the road-system’s status, sometimes she will ask you to tell there is how many black edge on a path.</div>
<div></div>
<div>Initially, every edges is white.</div>
<p></p></div>

# Input

<div class="content"><div>The first line contains an integer T, denoting the number of the test cases.</div>
<div>For each test case, the first line contains an integer n, which is the size of the tree. The vertices be indexed from 1.</div>
<div>On the next n-1 lines, each line contains two integers a,b, denoting there is an edge between a and b. </div>
<div>The next line contains an integer Q, denoting the number of the operations.</div>
<div>On the next Q lines, each line contains three integers t,a,b. t=1 means we reverse every edge’s color on path a to b. t=2 means we reverse every edge’s color adjacent to path a to b. t=3 means we query about the number of black edge on path a to b.</div>
<div></div>
<div>T&lt;=5.</div>
<div>n,Q&lt;=10^5.</div>
<div>Please use scanf,printf instead of cin,cout,because of huge input.</div>
<p></p></div>

# Output

<div class="content"><div>
<div>For each t=3 operation, output the answer in one line.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
10<br/>
2 1<br/>
3 1<br/>
4 1<br/>
5 1<br/>
6 5<br/>
7 4<br/>
8 3<br/>
9 5<br/>
10 6<br/>
<br/>
10<br/>
2 1 6<br/>
1 3 8<br/>
3 8 10<br/>
2 3 4<br/>
2 10 8<br/>
2 4 10<br/>
1 7 6<br/>
2 7 3<br/>
2 1 4<br/>
2 10 10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><div>reverse color means change from white to black or vice virsa.</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By WJMZBMR">By WJMZBMR</a></p></div>

