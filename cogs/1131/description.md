# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span>
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	小明要搬家了，大家都来帮忙。
</p>
<p style="text-indent:21.0000pt;">
	小明现在住在第<span>N</span><span>楼，总共</span><span>K</span><span>个人要把</span><span>X</span><span>个大箱子搬上</span><span>N</span><span>楼。</span> 
</p>
<p style="text-indent:21.0000pt;">
	最开始<span>X</span><span>个箱子都在</span><span>1</span><span>楼，但是经过一段混乱的搬运已经乱掉了。最后大家发现这样混乱地搬运过程效率太低了，于是总结出了提高效率的方法。</span> 
</p>
<p style="text-indent:21.0000pt;">
	大家的速度都是每分钟上（或下）一层楼。所有向上走的人手中都拿一个箱子，所有向下走的人手中都不拿箱子。到达第<span>N</span><span>层立刻放下箱子向下走，到达第</span><span>1</span><span>层立刻拿起箱子向上走。当一个人向上走，另一人向下走而在楼道里相遇时，向上走的人将手中的箱子交给另一人，两人同时反向。即原来拿箱子向上走的人不拿箱子向下走，原来不拿箱子向下走的人现拿着箱子向上走。</span> 
</p>
<p style="text-indent:21.0000pt;">
	求将所有箱子搬完所需的最短时间。
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	第一行<span>N(N</span><span>≤</span><span>10^9)</span><span>，</span><span>K(K</span><span>≤</span><span>500000)</span><span>，</span><span>M(M</span><span>≤</span><span>10^9)</span><span>，分别表示楼层数、人数、还放在一楼地上的箱子数。</span> 
</p>
<p style="text-indent:21.0000pt;">
	接下来<span>K</span><span>行，每行两个数</span><span>Ai</span><span>，</span><span>Bi</span><span>。</span> 
</p>
<p style="text-indent:21.0000pt;">
	Ai<span>表示第</span><span>i</span><span>人现所在的楼层数，</span><span>Bi</span><span>为</span><span>0</span><span>或</span><span>1</span><span>，为</span><span>0</span><span>表示第</span><span>i</span><span>人正拿着箱子向上走，为</span><span>1</span><span>表示第</span><span>i</span><span>人不拿箱子向下走。</span> 
</p>
<p style="text-indent:21.0000pt;">
	输入满足没有任意两人正在同一楼层，在第<span>1</span><span>层的人一定正拿着箱子向上走，在第</span><span>N</span><span>层的人一定正不拿箱子向下走。</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	仅包含一个整数，为搬完箱子的时间。
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>5 2 4
1 0
3 0</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>20</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	对于<span>30%</span><span>的数据有</span><span>K</span><span>≤</span><span>100</span><span>，</span><span>M</span><span>≤</span><span>100</span><span>；</span> 
</p>
<p style="text-indent:21.0000pt;">
	对于<span>60%</span><span>的数据有</span><span>K</span><span>≤</span><span>1000</span><span>，</span><span>M</span><span>≤</span><span>l09;</span> 
</p>
<p style="text-indent:21.0000pt;">
	对于<span>l000/o</span><span>的数据有</span><span>K</span><span>≤</span><span>500000</span><span>，</span><span>M</span><span>≤</span><span>109</span><span>。</span> 
</p>
<p>
	<br/>
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">冲刺</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">NOIP2010</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">模拟试题与解析（五）</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（提高组复赛）</span> 
</p>
