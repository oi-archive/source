# 题目描述


<p>
	<b><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第三题：</span></b><b><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">work</span></b> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">当前有</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">n&lt;=12</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">）个工作，和</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">8</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个工人。现在每个工作需要占用一个工人的从</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">[a</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">b]</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">这个区间的时间（一个工人自然不可能在同一个时间做</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个不同的工作），且一个工作不一定是所有工人都能够完成的。现在给出每个工作的描述，问是否存在一种安排方案使得所有工作都能完成。</span><span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件（</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">worka.in</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">）</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出文件有多组数据。第一行一个数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">tot</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">表示数据的组数，后面紧接</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">tot</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">组数据。</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于每一组数据的第一行有一个整数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，表示工作的数目。后面</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">行每行描述一个工作。</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于一个工作，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">a</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">b</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">k</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">h1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">h2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">……</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">hk</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">来描述，表示这个工作需要占用一个工人</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">[a</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">b]</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">的时间，并且能够完成这个工作的工人只有</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">k</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个，标号分别是</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">h1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">h2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">……</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">hk</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">。</span><span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出文件（</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">worka.out</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">）</span><span></span> 
</p>
<p style="text-indent:21.75pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于每组输入数据，输出一行</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">YES</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（如果可以安排一种方案使得工作完成）或者是</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">NO</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">（无法安排一种方案）</span><span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">样例：</span><span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">input</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 1 1 1 </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 2 1 1</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 2 1 1 </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 2 1 1</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> </span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">output</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">YES</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">NO</span> 
</p>
