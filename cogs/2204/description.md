# 题目描述


<h3>
【题目描述】
</h3>
<p>
奶牛Bessie设计了一款电子游戏:”愤怒的奶牛”，她认为这将是下一个非常热门的游戏。前提是，她认为这个游戏是她完全原创的：玩家在一个一维场景中用弹弓射奶牛，还包括位于这条数轴上不同位置的几堆干草。奶牛Bessie使用足够的能量去引爆她所在位置的干草。
</p>
<p>
这将会造成一系列连锁反应使得额外的干草爆炸。<strong>Bessie目标是令所有干草爆炸.</strong> 
</p>
<p>
有$N$堆在数轴上不同的位置的干草，坐标为$x_1,x_2,x_3……x_n$.如果奶牛在位置$x$释放$R$的能量，将会引起$[X-R,X+R]$范围内的干草堆发生爆炸，这些干草堆将会同时爆炸，释放$R-1$的能量，将会引起$[X-(R-1),X+(R-1)]$范围内的干草堆发生爆炸，这些干草堆将会继续同时爆炸，释放$R-2$的能量，以此类推。
</p>
<p>
译者注：能量不会小于0，最少衰减到0
</p>
<p>
请找出$R$的最小值
</p>
<h3>
【输入格式】
</h3>
<p>
第一行有一个整数$n$
</p>
<p>
接下来$n$行每行一个整数$x_i$
</p>
<h3>
【输出格式】
</h3>
<p>
只有一个<strong>实数</strong>，为半径的最小值,精确到小数点后1位
</p>
<h3>
【样例输入】
</h3>
<p>
5
</p>
<p>
8
</p>
<p>
10
</p>
<p>
3
</p>
<p>
11
</p>
<p>
1
</p>
<h3>
【样例输出】
</h3>
<p>
3.0
</p>
<h3>
【提示】
</h3>
<p>
<br/>
</p>
<p>
<img src="/upload/image/20160401/20160401110219_63321.png" alt=""/> 
</p>
<p>
<img src="/upload/image/20160401/20160401110225_80619.png" alt=""/> 
</p>
<p>
<img src="/upload/image/20160401/20160401110229_98968.png" alt=""/> 
</p>
<p>
在这个例子中，奶牛在位置5释放3的能量使得位置3和位置8的干草堆爆炸，能量衰减为2，位置3和位置8的干草堆使得位置1和位置10的干草堆爆炸，能量衰减为1，使得位置11爆炸，能量衰减为0
</p>
<p>
In this example, a cow launched with power 3 at, say, location 5, will cause
</p>
<p>
immediate detonation of  hay bales at positions 3 and 8.  These then explode
</p>
<p>
(simultaneously) each with blast radius 2, engulfing bales at positions 1 and
</p>
<p>
10, which next explode (simultaneously) with blast radius 1, engulfing the final
</p>
<p>
bale at position 11, which finally explodes with blast radius 0.
</p>
<p>
数据范围：
</p>
<p>
对于20%的数据$N&lt;=20$
</p>
<p>
对于100%的数据$N&lt;=50000,X_i&lt;=1000000000$
</p>
<h3>
【来源】
</h3>
<p>
USACO 2016 Jan contest Gold
</p>
