# 题目描述


<p style="text-indent:21.25pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">拜特兰并不总是一个非常民主的国家，也有一些阴暗的历史。一个美好的日子，拜特将军（该国的统帅）作了一个用以结束长期内战的决定，释放被关押的反对派。然而，他并未让反对派的领袖拜特萨直接自由，而是用一根“拜特链”将拜特萨锁在墙边</span><span style="font-size:14px;font-family:&#39;Microsoft YaHei&#39;;">.</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">该链子由很多环和固定在墙上栅栏组成。尽管环并未和栅栏融合在一起，但想除去它们却非常困难。</span><span style="font-size:10.5pt;"> <span></span></span> 
</p>
<p style="text-indent:21.25pt;">
	<span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">“将军，你为什么要用链子将我锁在墙边而不让我自由！”拜特萨大叫道。</span><span></span></span> 
</p>
<p style="text-indent:21.25pt;">
	<span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">“拜特萨，你并未完全被链子锁住，我可以坦率的告诉你，你完全可以从栅栏上解下环。”拜特将军回答，同时他补充说，“但是，你必须在夜里工作，一个小时之内完成，不能弄出任何声音，否则，我将按有关法律治罪。”</span><span></span></span> 
</p>
<p style="text-indent:21.25pt;">
	<span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">为了帮助拜特萨！链子上的环按整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1,2,…,n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">进行了编号。我们可以按照以下规则解开环：</span><span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:42.25pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">l</span><span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">只有一个环时可以被连接到栅栏或从栅栏上拆开。 </span><span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:42.25pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">l</span><span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">号环总能进行连接或拆开 </span><span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:42.25pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">l</span><span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">如果</span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1,...,</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">k</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">-1 (1&lt;=</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">k</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">&lt;</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">)</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">环都被拆开，第</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">k</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">个环被连接时</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">, </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">此时我们能连接或拆开 第</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">k</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">+1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">个环</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">. </span></span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">写一个程序：</span><span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:42.25pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">l</span><span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">文本文件</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">lan.in</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">描述了拜特链的构成</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">, </span></span> 
</p>
<p style="text-indent:-21pt;margin-left:42.25pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">l</span><span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">计算拆除拜特链上全部环的最少操作次数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">, </span></span> 
</p>
<p style="text-indent:-21pt;margin-left:42.25pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">l</span><span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">将结果写入文本文件</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">lan.out. </span></span> 
</p>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输入</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">(lan.in):</span></span></b> 
</p>
<p style="text-indent:21.25pt;">
	<span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">在文本文件</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">lan.in </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">中的第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">行有一个整数</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span></i><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">, 1&lt;=</span><i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span></i><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">&lt;=1 000.</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">在第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">行有</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">个用一个空格分隔的整数</span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> o</span><sub><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1</span></sub><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">,o</span><sub><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">2</span></sub><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">,...,o</span><sub><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">n</span></sub><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> (</span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">每个都是</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">0</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">或</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">1)</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">，如果</span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> o</span><sub><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">i</span></sub><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">=1, </span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">那么第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">个环和栅栏相连，如果</span><span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> o</span><sub><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">i</span></sub><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">=0, </span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">那么第</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">i</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">环没有和栅栏相连。 </span><span></span></span> 
</p>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">(lan.out):</span></span></b> 
</p>
<p style="text-indent:21.25pt;">
	<span style="font-family:宋体;font-size:10.5pt;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">文本文件</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> lan.out</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">中只包含一个整数，为解开拜特链的全部环的最少操作次数。</span><span></span></span> 
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输入示例</span></b><b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">(lan.in)</span><span></span></b> 
</p>
<p>
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><br/>
</span></b>
</p>
<pre>4
1 0 1 0
</pre>
<p>
	<b><span style="font-family:宋体;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出示例</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">(lan.out)</span></span></b>
</p><pre>6</pre>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><img src="/upload/image/20121004/20121004100253_68362.png" alt=""/><br/>
</span> 
<p></p>
