# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«问题描述：</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">有n件工作要分配给n个人做。第i 个人做第j 件工作产生的效益为c[i][j]  。试设计一个将</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">n件工作分配给n个人做的分配方案，使产生的总效益最大。</span><br/>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«编程任务：</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于给定的n件工作和n个人，计算最优分配方案和最差分配方案。</span><br/>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«数据输入：</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">由文件<span>job.in</span>提供输入数据。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">文件的第1 行有1 个正整数n，表示有n件工作要分配</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">给n 个人做。</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">接下来的n 行中，每行有n 个整数c[i][j] ，1≤i≤n，1≤j≤n，</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">表示第i 个人做</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第j件工作产生的效益为c[i][j] 。</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">«结果输出:</span> 
</h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">程序运行结束时，将计算出的最小总效益和最大总效益输出到文件<span>job.out</span>中。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入文件示例 输出文件示例</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>job.in</span></span><br/>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 2 2 1 2</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 3 1 2 4</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 0 1 1 1</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2 3 4 3 3</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">3 2 1 2 1</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span>job.out</span><br/>
</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5</span> 
</p>
<p>
14
</p>
<h3>
数据范围
</h3>
N&lt;=100<br/>
