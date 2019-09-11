# 题目描述


<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【背景</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">随着新版百度空间的下线，Blog宠物绿豆蛙完成了它的使命，去寻找它新的归宿。</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【题目描述</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">给出一个有向无环的连通图，起点为1终点为N，每条边都有一个长度。绿豆蛙从起点出发，走向终点。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">到达每一个顶点时，如果有K条离开该点的道路，绿豆蛙可以选择任意一条道路离开该点，并且走向每条路的概率为 1/K 。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">现在绿豆蛙想知道，从起点走到终点的所经过的路径总长度期望是多少？</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输入格式</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">】</span> 
</h3>
<p>
<br/>
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第一行: 两个整数 N M，代表图中有N个点、M条边</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第二行到第 1+M 行: 每行3个整数 a b c，代表从a到b有一条长度为c的有向边</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输出格式</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">从起点到终点路径总长度的期望值，四舍五入保留两位小数。</span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输入样例</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">】</span> 
</h3>
<pre>4 4
1 2 1
1 3 2
2 3 3
3 4 4 </pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【输出样例</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">】</span> 
</h3>
<pre>7.00</pre>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【时限</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">各个测试点1s</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"></span> 
</p>
<h3>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">【数据范围】</span> 
</h3>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">对于20%的数据   N&lt;=100<br/>
对于40%的数据   N&lt;=1000<br/>
对于60%的数据   N&lt;=10000<br/>
对于100%的数据  N&lt;=100000，M&lt;=2*N</span> 
</p>
<p>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"></span> 
</p>
