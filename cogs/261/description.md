# 题目描述


<p style="text-indent:2em;">
	<img src="/cogs/images/upload/image/20120416/20120416153733_78761.png" width="211" height="157" align="right" alt=""/> 
</p>
<p style="text-indent:2em;">
	SERCOI 最近设计了一种积木游戏。每个游戏者有N块编号依次为1 ，2，…，N的长方体积木。对于每块积木,它的三条不同的边分别称为”a边”、“b边”和”c边”，如下图所示：
</p>
<p style="text-indent:2em;">
	游戏规则如下：
</p>
<p style="text-indent:2em;">
	<br/>
</p>
<p style="text-indent:2em;">
	<br/>
</p>
<ol>
	<li>
		从N块积木中选出若干块，并将它们分成M（l&lt;=M&lt;=N） 堆，称为第1堆，第2 堆…，第M堆。每堆至少有1块积木，并且第K堆中任意一块积木的编号要大于第K+1堆中任意一块积木的编号(2&lt;=K&lt;=M)。
	</li>
	<li>
		对于每一堆积木,游戏者要将它们垂直摞成一根柱子,并要求满足下面两个条件：
	</li>
	<ol>
		<li>
			除最顶上的一块积木外，任意一块积木的上表面同且仅同另一块积木的下表面接触，并且要求下面的积木的上表面能包含上面的积木的下表面，也就是说，要求下面的积木的上表面的两对边的长度分别大于等于上面的积木的两对边的长度。
		</li>
		<li>
			对于任意两块上下表面相接触的积木，下面的积木的编号要小于上面的积木的编号。
		</li>
	</ol>
</ol>
<p>
	<br/>
</p>
<p style="text-indent:2em;">
	<br/>
</p>
<p style="text-indent:2em;">
	最后，根据每人所摞成的M根柱子的高度之和来决出胜负。
</p>
<p style="text-indent:2em;">
	请你编一程序，寻找一种摞积木的方案，使得你所摞成的M根柱子的高度之和最大。
</p>
<h3 style="text-indent:2em;">
	输入输出
</h3>
<p style="text-indent:2em;">
	输入文件的第一行有两个正整数N和M（1&lt;=M&lt;=N&lt;=100），分别表示积木总数和要求 摞成的柱子数。这两个数之间用一个空格符隔开。接下来N行依次是编号从1到N的N个积木的尺寸，每行有三个1至1000之间的整数，分别表示该积木a 边,b边和c边的长度。同一行相邻两个数之间用一个空格符隔开。
</p>
<p style="text-indent:2em;">
	输出文件只有一行，为一个整数，表示M根柱子的高度之和。
</p>
<h3 style="text-indent:2em;">
	样例
</h3>
<p style="text-indent:2em;">
	输入文件
</p>
<p style="text-indent:2em;">
	<br/>
</p>
<p>
	<br/>
</p>
<pre class="prettyprint">4 2
10 5 5
8 7 7
2 2 2
6 6 6</pre>
<p>
	<br/>
</p>
<p style="text-indent:2em;">
	<br/>
</p>
<p style="text-indent:2em;">
	输出文件
</p>
<p>
	<br/>
</p>
<pre class="prettyprint">24</pre>
<p>
	<br/>
</p>
