# 题目描述


<h3>
【题目描述】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">一个无向连通图，顶点从1编号到N，边从1编号到M。 <br/>
小Z在该图上进行随机游走，初始时小Z在1号顶点，每一步小Z以相等的概率随机选 择当前顶点的某条边，沿着这条边走到下一个顶点，获得等于这条边的编号的分数。当小Z 到达N号顶点时游走结束，总分为所有获得的分数之和。 <br/>
现在，请你对这M条边进行编号，使得小Z获得的总分的期望值最小。 </span> 
</p>
</div>
<h3>
【输入格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">第一行是正整数N和M，分别表示该图的顶点数 和边数，接下来M行每行是整数u，v(1≤u,v≤N)，表示顶点u与顶点v之间存在一条边。 输入保证30%的数据满足N≤10，100%的数据满足2≤N≤500且是一个无向简单连通图。 </span> 
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">仅包含一个实数，表示最小的期望值，保留3位小数。 </span> 
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>  3  3                
  2  3
  1  2
  1  3
  </pre>
<h3>
【样例输出】
</h3>
<pre>3.333</pre>
<h3>
【提示】
</h3>
<p class="content">
<br/>
</p>
<p align="left" class="content" style="margin:0.25pt -1.5pt 0pt 39pt;line-height:12.75pt;">
<span style="font-size:11pt;color:black;">边</span><span style="font-size:11pt;color:black;">(1,2)</span><span style="font-size:11pt;color:black;">编号为</span><span style="font-size:11pt;color:black;">1</span><span style="font-size:11pt;color:black;">，边</span><span style="font-size:11pt;color:black;">(1,3)</span><span style="font-size:11pt;color:black;">编号</span><span style="font-size:11pt;color:black;">2</span><span style="font-size:11pt;color:black;">，边</span><span style="font-size:11pt;color:black;">(2,3)</span><span style="font-size:11pt;color:black;">编号为</span><span style="font-size:11pt;color:black;">3</span><span style="font-size:11pt;color:black;">。</span> 
</p>
<p align="left" class="content" style="margin:0.25pt -1.5pt 0pt 39pt;line-height:12.75pt;">
<span style="font-size:11pt;color:black;"><br/>
</span> 
</p>
<p align="left" class="content" style="margin:0.25pt -1.5pt 0pt 39pt;line-height:12.75pt;">
<span style="font-size:11pt;color:black;">由于搬运者发现官方数据没有程序能跑对最后两个点，遂修改其结果。</span> 
</p>
<p align="left" class="content" style="margin:0.25pt -1.5pt 0pt 39pt;line-height:12.75pt;">
<br/>
</p>
<p class="content">
<br/>
</p>
