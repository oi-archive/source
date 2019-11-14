# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span> 
</h3>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">A地区在地震过后，连接所有村庄的公路都造成了损坏而无法通车。政府派人修复这些公路。</span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">给出A地区的村庄数N，和公路数M，公路是双向的。并告诉你每条公路的连着哪两个村庄，并告诉你什么时候能修完这条公路。问最早什么时候任意两个村庄能够通车，即最早什么时候任意两条村庄都存在至少一条修复完成的道路（可以由多条公路连成一条道路）</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span> 
</h3>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第1行两个正整数N，M（N&lt;=1000，M&lt;=100000）</span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">下面M行，每行3个正整数x, y, t，告诉你这条公路连着x,y两个村庄，在时间t时能修复完成这条公路。（x&lt;=N，y&lt;=N，t&lt;=100000）</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">如果全部公路修复完毕仍然存在两个村庄无法通车，则输出-1，否则输出最早什么时候任意两个村庄能够通车。</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span> 
</h3>
<pre>4 4
1 2 6
1 3 4
1 4 5
4 2 3</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span> 
</h3>
<pre>5</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【来源】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">福州NOIP2010培训 Day5</span> 
</p>
