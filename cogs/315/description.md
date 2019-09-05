# 题目描述


<p>
Description
</p>
<div>
<p>
Bessie has moved to a small farm and sometimes enjoys returning to visit one of her best friends. She does not want to get to her old home too quickly, because she likes the scenery along the way. She has decided to take the second-shortest rather than the shortest path. She knows there must be some second-shortest path.
</p>
<p>
The countryside consists of <i>R</i> (1 ≤ <i>R</i> ≤ 100,000) bidirectional roads, each linking two of the N (1 ≤ <i>N</i> ≤ 5000) intersections, conveniently numbered 1..<i>N</i>. Bessie starts at intersection 1, and her friend (the destination) is at intersection <i>N</i>.
</p>
<p>
The second-shortest path may share roads with any of the shortest paths, and it may backtrack i.e., use the same road or intersection more than once. The second-shortest path is the shortest path whose length is longer than the shortest path(s) (i.e., if two or more shortest paths exist, the second-shortest path is the one whose length is longer than those but no longer than any other path).
</p>
<p>
<br/>
</p>
<p>
贝茜搬到了一个小农场去住，但她很享受偶尔回去看看她的一个好朋友。贝茜很喜欢沿途的风景，因此她希望路上走的尽可能慢一些。于是她决定走次短路而不是最短路。
</p>
<p>
城郊包含R(1&lt;=R&lt;=100,000)条双向的路，它们分别连接了N(1&lt;=N&lt;=5000)个十字路口(节点)，为了方便我们把它们标记为1..N。贝茜从1号节点出发，她的好朋友(目的地)在N号节点。
</p>
<p>
次短路和最短路可以部分重合，次短路也有可能经过同一条路或同一个节点多次。次短路是长于最短路的路中最短的那一条。当有多个最短路存在时，次短路是其他所有路中最短的那条。
</p>
<p>
<br/>
</p>
</div>
<p>
Input
</p>
<div>
Line 1: Two space-separated integers: <i>N</i> and <i>R</i> <br/>
<p>
Lines 2..<i>R</i>+1: Each line contains three space-separated integers: <i>A</i>, <i>B</i>, and <i>D</i> that describe a road that connects intersections <i>A</i> and <i>B</i> and has length <i>D</i> (1 ≤ <i>D</i> ≤ 5000)
</p>
<p>
<br/>
</p>
<p>
输入：
</p>
<p>
第1行：两个被空格分开的整数N和R
</p>
<p>
第2..R+1行：每行包括三个由空格分开的整数A,B和D组成。用来描述连接节点A和节点B之间路径的长度是D(1&lt;=D&lt;=5000)。
</p>
<p>
<br/>
</p>
</div>
<p>
Output
</p>
<div>
<p>
Line 1: The length of the second shortest path between node 1 and node <i>N</i> 
</p>
</div>
<p>
<br/>
</p>
<p>
输出：
</p>
<p>
第一行：一个整数表示从节点1到节点N之间次短路的长度。
</p>
<p>
<br/>
</p>
<p>
Sample Input
</p>
<pre class="sio">4 4
1 2 100
2 4 200
2 3 250
3 4 100</pre>
<p>
Sample Output
</p>
<pre class="sio">450</pre>
<p>
Hint
</p>
<div>
<p>
Two routes: 1 -&gt; 2 -&gt; 4 (length 100+200=300) and 1 -&gt; 2 -&gt; 3 -&gt; 4 (length 100+250+100=450)
</p>
<p>
<br/>
</p>
<p>
提示：
</p>
<p>
样例中由两条从节点1到节点N的路分别是1-&gt;2-&gt;4(len=100+200=300(最短路))和1-&gt;2-&gt;3-&gt;4(100+250+100=450(次短路))。
</p>
<p>
译byKZFFFFFFFF
</p>
<p>
<br/>
</p>
</div>
