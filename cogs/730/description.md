# 题目描述


<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:19px;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">描述  USACO 1.5.1</span> 
</h2>
<p style="font-size:13px;background-color:#FFFFFF;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">观察下面的数字金字塔。</span> 
</p>
<p style="font-size:13px;background-color:#FFFFFF;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">写一个程序来查找从最高点到底部任意处结束的路径，使路径经过数字的和最大。每一步可以走到左下方的点也可以到达右下方的点。</span> 
</p>
<pre>         7 
      3   8 
    8   1   0 
  2   7   4   4 
4   5   2   6   5 
</pre>
<p style="font-size:13px;background-color:#FFFFFF;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">在上面的样例中,从7 到 3 到 8 到 7 到 5 的路径产生了最大</span> 
</p>
<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:19px;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><br/>
格式</span> 
</h2>
<p style="font-size:13px;background-color:#FFFFFF;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">PROGRAM NAME</span></b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">: numtri</span> 
</p>
<p style="font-size:13px;background-color:#FFFFFF;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">INPUT FORMAT</span></b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">:</span> 
</p>
<p style="font-size:13px;background-color:#FFFFFF;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(file numtri.in)</span> 
</p>
<p style="font-size:13px;background-color:#FFFFFF;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一个行包含 R(1&lt;= R&lt;=1000) ,表示行的数目。</span> 
</p>
<p style="font-size:13px;background-color:#FFFFFF;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">后面每行为这个数字金字塔特定行包含的整数。</span> 
</p>
<p style="font-size:13px;background-color:#FFFFFF;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">所有的被供应的整数是非负的且不大于100。</span> 
</p>
<p style="font-size:13px;background-color:#FFFFFF;">
	<b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">OUTPUT FORMAT</span></b><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">:</span> 
</p>
<p style="font-size:13px;background-color:#FFFFFF;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(file numtri.out)</span> 
</p>
<p style="font-size:13px;background-color:#FFFFFF;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">单独的一行,包含那个可能得到的最大的和。</span> 
</p>
<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:19px;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><br/>
SAMPLE INPUT</span> 
</h2>
<pre>5
7
3 8
8 1 0
2 7 4 4
4 5 2 6 5 
</pre>
<h2 style="background-color:#FFFFFF;font-weight:normal;margin-left:0px;font-size:19px;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><br/>
SAMPLE OUTPUT</span> 
</h2>
<pre>30</pre>
