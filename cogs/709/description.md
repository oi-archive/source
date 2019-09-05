# 题目描述


<p>
	<b><span style="font-family:宋体;">问题：</span><span></span></b> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:宋体;font-size:10.5pt;">现给定</span><span style="font-size:10.5pt;">n</span><span style="font-family:宋体;font-size:10.5pt;">个闭区间</span><span style="font-size:10.5pt;">[a<sub>i</sub>, b<sub>i</sub>]</span><span style="font-family:宋体;font-size:10.5pt;">，</span><span style="font-size:10.5pt;">1 </span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-size:10.5pt;"> i </span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-size:10.5pt;"> n</span><span style="font-family:宋体;font-size:10.5pt;">。这些区间的并可以表示为一些不相交的闭区间的并。你的任务就是在这些表示方式中找出包含最少区间的方案。你的输出应该按照区间的升序排列。这里如果说两个区间</span><span style="font-size:10.5pt;">[a, b]</span><span style="font-family:宋体;font-size:10.5pt;">和</span><span style="font-size:10.5pt;">[c, d]</span><span style="font-family:宋体;font-size:10.5pt;">是按照升序排列的，那么我们有</span><span style="font-size:10.5pt;">a </span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-size:10.5pt;"> b &lt; c </span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-size:10.5pt;"> d</span><span style="font-family:宋体;font-size:10.5pt;">。</span> 
</p>
<p>
	<span style="font-family:黑体;">任务：</span><span><span> </span></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:宋体;font-size:10.5pt;">请写一个程序：</span><span style="font-size:10.5pt;"></span> 
</p>
<p style="text-indent:-21pt;margin-left:45pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span>l<span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;">在文本文件</span><span style="font-size:10.5pt;">minprz.in</span><span style="font-family:宋体;font-size:10.5pt;">中读入这些区间；</span><span style="font-size:10.5pt;"></span> 
</p>
<p style="text-indent:-21pt;margin-left:45pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span>l<span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;">计算满足给定条件的不相交闭区间；</span><span style="font-size:10.5pt;"></span> 
</p>
<p style="text-indent:-21pt;margin-left:45pt;">
	<span style="font-family:Wingdings;"><span>l<span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;">把这些区间按照升序输出到文件</span><span style="font-size:10.5pt;">minprz.out</span><span style="font-family:宋体;font-size:10.5pt;">中。</span><span style="font-family:宋体;"></span> 
</p>
<p>
	<span style="font-family:黑体;">输入格式(minprz.in</span><span style="font-family:黑体;">：</span><span></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:宋体;font-size:10.5pt;">在文本文件<span>PRZ.IN</span>的第一行包含一个整数<span>n</span>，<span>3 </span></span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-family:宋体;font-size:10.5pt;"> n </span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-family:宋体;font-size:10.5pt;"> 50000</span><span style="font-family:宋体;font-size:10.5pt;">，为区间的数目。以下<span>n</span>行为对区间的描述，第<span>i</span>行为对第<span>i</span>个区间的描述，为两个整数<span>1 </span></span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-family:宋体;font-size:10.5pt;"> a<sub>i</sub> </span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-family:宋体;font-size:10.5pt;"> b<sub>i</sub> </span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-family:宋体;font-size:10.5pt;"> 1000000</span><span style="font-family:宋体;font-size:10.5pt;">，表示一个区间<span>[a<sub>i</sub>, b<sub>i</sub>]</span>。<span></span></span> 
</p>
<p>
	<span style="font-family:黑体;">输出格式</span><span style="font-family:黑体;">：</span><span></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:宋体;font-size:10.5pt;">你应该在文本文件<span>PRZ.OUT</span>中输出计算出来的不相交的区间。每一行都是对一个区间的描述，包括两个用空格分开的整数，为区间的上下界。你应该把区间按照升序排序。<span></span></span> 
</p>
<p>
	<span style="font-family:黑体;">样例：</span><span></span> 
</p>
<p>
	<span style="font-family:宋体;">输入（</span><span>minprz.in</span><span style="font-family:宋体;">）</span><span>:</span> 
</p>
<pre><span style="font-family:&#39;Courier New&#39;;">5</span></pre>
<pre><span style="font-family:&#39;Courier New&#39;;">5 6</span></pre>
<pre><span style="font-family:&#39;Courier New&#39;;">1 4</span></pre>
<pre><span style="font-family:&#39;Courier New&#39;;">10 10</span></pre>
<pre><span style="font-family:&#39;Courier New&#39;;">6 9</span></pre>
<pre><span style="font-family:&#39;Courier New&#39;;">8 10</span></pre>
<pre><span style="font-family:宋体;font-size:10.5pt;">输出（</span><span style="font-family:&#39;Times New Roman&#39;;font-size:10.5pt;">minprz.out</span><span style="font-family:宋体;font-size:10.5pt;">）：</span><span style="font-family:&#39;Times New Roman&#39;;font-size:10.5pt;"></span></pre>
<pre><span style="font-family:&#39;Courier New&#39;;">1 4</span></pre>
<pre><span style="font-family:&#39;Courier New&#39;;"></span><span style="font-family:&#39;Courier New&#39;;">5 10</span><span style="font-family:黑体;font-size:16pt;"></span></pre>
