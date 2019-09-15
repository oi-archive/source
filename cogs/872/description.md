# 题目描述


<p>
	USACO/fence(译 by Jeru)
</p>
<span id=".E6.8F.8F.E8.BF.B0" class="mw-headline">描述</span> 
<p>
	Farmer John每年有很多栅栏要修理。他总是骑着马穿过每一个栅栏并修复它破损的地方。
</p>
<p>
	John是一个与其他农民一样懒的人。他讨厌骑马，因此从来不两次经过一个栅栏。你必须编一个程序，读入栅栏网络的描述，并计算出一条修栅栏的路径，使每个栅栏都恰好被经过一次。John能从任何一个顶点(即两个栅栏的交点)开始骑马，在任意一个顶点结束。
</p>
<p>
	每一个栅栏连接两个顶点，顶点用1到500标号(虽然有的农场并没有500个顶点)。一个顶点上可连接任意多(&gt;=1)个栅栏。两顶点间可能有多个栅栏。所有栅栏都是连通的(也就是你可以从任意一个栅栏到达另外的所有栅栏)。
</p>
<p>
	你的程序必须输出骑马的路径(用路上依次经过的顶点号码表示)。我们如果把输出的路径看成是一个500进制的数，那么当存在多组解的情况下，输出500进制表示法中最小的一个 (也就是输出第一个数较小的，如果还有多组解，输出第二个数较小的，等等)。
</p>
<p>
	输入数据保证至少有一个解。
</p>
<span id=".E6.A0.BC.E5.BC.8F" class="mw-headline">格式</span> 
<p>
	<b>PROGRAM NAME</b>: fenceus
</p>
<p>
	<b>INPUT FORMAT</b>：
</p>
<p>
	(fenceus.in)
</p>
<p>
	第1行: 一个整数F(1 &lt;= F &lt;= 1024)，表示栅栏的数目
</p>
<p>
	第2到F+1行: 每行两个整数i, j(1 &lt;= i,j &lt;= 500)表示这条栅栏连接i与j号顶点。
</p>
<p>
	<b>OUTPUT FORMAT</b>：
</p>
<p>
	(fenceus.out)
</p>
<p>
	输出应当有F+1行，每行一个整数，依次表示路径经过的顶点号。注意数据可能有多组解，但是只有上面题目要求的那一组解是认为正确的。
</p>
<span id="SAMPLE_INPUT" class="mw-headline">SAMPLE INPUT </span>
<pre>9
1 2
2 3
3 4
4 2
4 5
2 5
5 6
5 7
4 6
</pre>
<span id="SAMPLE_OUTPUT" class="mw-headline">SAMPLE OUTPUT </span>
<pre>1
2
3
4
2
5
4
6
5
7
</pre>
<!-- 
NewPP limit report
Preprocessor node count: 15/1000000
Post-expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
--><!-- Saved in parser cache with key newnocow:pcache:idhash:851-0!*!*!!zh-cn!*!* and timestamp 20120711015503 -->
<p>
	 
</p>
