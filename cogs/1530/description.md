# 题目描述


<h3>
【题目描述】
</h3>
<p>
防御墙是一种保护城市或定居点免遭潜在侵略者袭击的工事。从古至今，人们都在定居点周围修建这些墙。
</p>
<p>
通常，它们被称为城墙。虽然这样，我们的祖先决定修建长城来保护中原免遭各种游牧部落的入侵。
</p>
<p>
<img src="/upload/image/20140223/20140223174220_60322.png" alt=""/> 
</p>
<p>
地图是一个给定的N*M矩形区域。每一个格子是一块空地，一座城市或者一支敌军。长城是一个边沿着格线的简单多边形，围住了所有的城市，将所有的敌军挡在外面。
</p>
<p>
长城并不容易建造，因此我们必须让长城尽可能短。现在你的任务是计算围住所有城市但不围住任意一支敌军的长城的最短长度。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行是一个整数T(1&lt;=T&lt;=50)，代表数据组数。
</p>
<p>
每组数据有若干行。
</p>
<p>
数据的第一行有两个正整数H,W(1&lt;=H,W&lt;=8)，代表地图的行数和列数。
</p>
<p>
接下来H行每行有W个字符，代表相应的格子。&#39;o&#39;代表城市，&#39;.&#39;代表空地，&#39;x&#39;代表敌军。
</p>
<p>
保证至少有一座城市。
</p>
<h3>
【输出格式】
</h3>
<p>
对每组数据，输出一行&#34;Case #X: Y&#34;，其中X是数据编号（从1开始），Y是长城的最短长度（如果无法建造，输出-1）。
</p>
<h3>
【样例输入】
</h3>
<p>
3
</p>
<p>
3 3
</p>
<p>
.o.
</p>
<p>
.x.
</p>
<p>
o.o
</p>
<p>
4 4
</p>
<p>
....
</p>
<p>
.ox.
</p>
<p>
.xo.
</p>
<p>
....
</p>
<p>
5 5
</p>
<p>
.ooo.
</p>
<p>
.x...
</p>
<p>
..xoo
</p>
<p>
x.xoo
</p>
<p>
.ox.x
</p>
<h3>
【样例输出】
</h3>
<p>
Case #1: 14
</p>
<p>
Case #2: -1
</p>
<p>
Case #3: 28
</p>
<h3>
【提示】
</h3>
<p>
一个简单多边形是平面上一系列线段围成的封闭区域，这些线段之间除了相邻边之外没有公共点。
</p>
<p>
样例的第一组数据的解见图1.
</p>
<p>
样例的第二组数据没有解，因为无论如何修建长城，它的非相邻边总会相交。
</p>
<p>
<img src="/upload/image/20140223/20140223175757_41149.png" alt=""/> 
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=573&amp;page=show_problem&amp;problem=4247" target="_blank">UVa1501 Construct the Great Wall</a> 
</p>
