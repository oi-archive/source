# 题目描述


<h1 style="text-align:center;">
	<b><span style="font-family:Microsoft YaHei;">黑魔法师之门</span></b> 
</h1>
<p align="center" style="text-align:center;">
	<br/>
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">题目描述</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:Microsoft YaHei;">经过了</span><span style="font-family:&#39;Microsoft YaHei&#39;;">16</span><span style="font-family:Microsoft YaHei;">个工作日的紧张忙碌，未来的人类终于收集到了足够的能源。然而在与</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Violet</span><span style="font-family:Microsoft YaHei;">星球的战争中，由于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Z</span><span style="font-family:Microsoft YaHei;">副官的愚蠢，地球的领袖</span><span style="font-family:&#39;Microsoft YaHei&#39;;">applepi</span><span style="font-family:Microsoft YaHei;">被邪恶的黑魔法师</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Vani</span><span style="font-family:Microsoft YaHei;">囚禁在了</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Violet</span><span style="font-family:Microsoft YaHei;">星球。为了重启</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Nescafé</span><span style="font-family:Microsoft YaHei;">这一宏伟的科技工程，人类派出了一支由</span><span style="font-family:&#39;Microsoft YaHei&#39;;">XLk</span><span style="font-family:Microsoft YaHei;">、</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Poet_shy</span><span style="font-family:Microsoft YaHei;">和</span><span style="font-family:&#39;Microsoft YaHei&#39;;">lydrainbowcat</span><span style="font-family:Microsoft YaHei;">三人组成的精英队伍，穿越时空隧道，去往</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Violet</span><span style="font-family:Microsoft YaHei;">星球拯救领袖</span><span style="font-family:&#39;Microsoft YaHei&#39;;">applepi</span><span style="font-family:Microsoft YaHei;">。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;">applepi</span><span style="font-family:Microsoft YaHei;">被囚禁的地点只有一扇门，当地人称它为“黑魔法师之门”。这扇门上画着一张无向无权图，而打开这扇门的密码就是图中</span><b><u><span style="font-family:Microsoft YaHei;">每个点的度数大于零且都是偶数的子图</span></u></b><span style="font-family:Microsoft YaHei;">的个数对</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1000000009</span><span style="font-family:Microsoft YaHei;">取模的值。此处子图</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> (V, E) </span><span style="font-family:Microsoft YaHei;">定义为：点集</span><span style="font-family:&#39;Microsoft YaHei&#39;;">V</span><span style="font-family:Microsoft YaHei;">和边集</span><span style="font-family:&#39;Microsoft YaHei&#39;;">E</span><span style="font-family:Microsoft YaHei;">都是原图的任意子集，其中</span><span style="font-family:&#39;Microsoft YaHei&#39;;">E</span><span style="font-family:Microsoft YaHei;">中的边的端点都在</span><span style="font-family:&#39;Microsoft YaHei&#39;;">V</span><span style="font-family:Microsoft YaHei;">中。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:Microsoft YaHei;">但是</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Vani</span><span style="font-family:Microsoft YaHei;">认为这样的密码过于简单，因此门上的图是动态的。起初图中只有</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:Microsoft YaHei;">个顶点而没有边。</span><span style="font-family:&#39;Microsoft YaHei&#39;;">Vani</span><span style="font-family:Microsoft YaHei;">建造的门控系统共操作</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:Microsoft YaHei;">次，每次往图中添加一条边。你必须在每次操作后都填写正确的密码，才能够打开黑魔法师的牢狱，去拯救伟大的领袖</span><span style="font-family:&#39;Microsoft YaHei&#39;;">applepi</span><span style="font-family:Microsoft YaHei;">。</span><span></span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">输入格式</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:Microsoft YaHei;">第一行包含两个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:Microsoft YaHei;">和</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:Microsoft YaHei;">。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:Microsoft YaHei;">接下来</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:Microsoft YaHei;">行，每行两个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;">A</span><span style="font-family:Microsoft YaHei;">和</span><span style="font-family:&#39;Microsoft YaHei&#39;;">B</span><span style="font-family:Microsoft YaHei;">，代表门控系统添加了一条无向边</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> (A, B)</span><span style="font-family:Microsoft YaHei;">。</span><span></span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">输出格式</span></b><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:Microsoft YaHei;">输出一共</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:Microsoft YaHei;">行，表示每次操作后的密码。</span><span></span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">样例输入</span><span></span></b> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">4
8</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">3
1</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">3
2</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">2
1</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">2
1</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">1
3</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">1
4</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">2
4</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">2
3</span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">样例输出</span><span></span></b> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">0</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">0</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">1</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">3</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">7</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">7</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">15</span> 
</p>
<p>
	<span style="font-family:Microsoft YaHei;">31</span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">样例说明</span></b><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:Microsoft YaHei;">第三次添加之后，存在一个满足条件的子图</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> {1, 2, 3}</span><span style="font-family:Microsoft YaHei;">（其中</span><span style="font-family:&#39;Microsoft YaHei&#39;;">1, 2, 3</span><span style="font-family:Microsoft YaHei;">是数据中边的标号）。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:Microsoft YaHei;">第四次添加之后，存在三个子图</span><span style="font-family:&#39;Microsoft YaHei&#39;;"> {1, 2, 3}</span><span style="font-family:Microsoft YaHei;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">{1, 2, 4}</span><span style="font-family:Microsoft YaHei;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">{3, 4}</span><span style="font-family:Microsoft YaHei;">。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:Microsoft YaHei;">……</span><span></span> 
</p>
<p>
	<b><span style="font-family:Microsoft YaHei;">数据范围与约定</span><span></span></b> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">30% </span><span style="font-family:Microsoft YaHei;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N, M</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">10</span><span style="font-family:Microsoft YaHei;">。</span><span></span> 
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:Microsoft YaHei;">对于</span><span style="font-family:&#39;Microsoft YaHei&#39;;">100% </span><span style="font-family:Microsoft YaHei;">的数据，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">200000</span><span style="font-family:Microsoft YaHei;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;">M</span><span style="font-family:Microsoft YaHei;">≤</span><span style="font-family:&#39;Microsoft YaHei&#39;;">300000</span><span style="font-family:Microsoft YaHei;">。</span><span></span> 
</p>
