# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">某乡有</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">个村庄</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(1</span><n<40)，有一个售货员，他要到各个村庄去售货，各村庄之间的路程<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">s(0</span><s<1000)是已知的，且<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">A</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">村到</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">B</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">村与</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">B</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">村到</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">A</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">村的路大多不同。为了提高效率，他从商店出发到每个村庄一次，然后返回商店所在的村，假设商店所在的村庄为</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">，他不知道选择什么样的路线才能使所走的路程最短。请你帮他选择一条最短的路。</span> </s<1000)是已知的，且<span></n<40)，有一个售货员，他要到各个村庄去售货，各村庄之间的路程<span> 
</p>
<n<40)，有一个售货员，他要到各个村庄去售货，各村庄之间的路程<span><s<1000)是已知的，且<span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span><span></span></s<1000)是已知的，且<span></n<40)，有一个售货员，他要到各个村庄去售货，各村庄之间的路程<span> 
<p>
<br/>
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">村庄数</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">n</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">和各村之间的路程</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">(均是整数)。</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">最短的路程。</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>3
0 2 1
1 0 2
2 1 0</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>3</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【提示】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3    	{村庄数} </span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">0 2 1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">     {</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">村庄</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">到各村的路程</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">}</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 0 2    {</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">村庄</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">到各村的路程</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">}</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 1 0    {</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">村庄</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">到各村的路程</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">}</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">n&lt;=18，状压dp的同学随意切掉……<br/>
</span> 
</p>
<p>
<br/>
</p>
