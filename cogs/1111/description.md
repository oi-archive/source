

# 题目描述


<p style="text-indent:21.0000pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">给出N个点，M条无向边的简单图，问所有点对之间的最短路。</span>
</p>

# 输入格式


<p style="text-indent:21.0000pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第1行两个正整数N，M（N&lt;=100，M&lt;=5000）</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">下面M行，每行3个正整数x, y, w，为一条连接顶点x与y的边权值为w。(x&lt;=n，y&lt;=n，w&lt;=1000)</span>
</p>

# 输出格式</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">



# 样例输入


<pre>5 10
3 2 1
2 4 7
5 3 4
4 1 2
5 1 8
3 4 10
5 4 9
2 5 2
1 2 1
3 1 10</pre>

# 样例输出


<pre>0 1 2 2 3
1 0 1 3 2
2 1 0 4 3
2 3 4 0 5
3 2 3 5 0</pre>

# 来源


<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">福州NOIP2010培训Day5</span>
</p>
