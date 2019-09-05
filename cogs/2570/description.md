# 题目描述


<h3>
【题目描述】
</h3>
<p>
 
</p>
<p>
农夫约翰的N头奶牛（1≤N≤50000）在FJ农场前方的路上疯狂奔跑，但他们实际上只是在赛跑，看哪头牛是最快的。
</p>
<p>
从上面看，每头奶牛被表示为一个单位长度的线段，其左上角点的坐标时间t = 0。例如，（-3，6）将表示一只牛，在时间t = 0时，
</p>
<p>
这头牛在从（-3，6）到（-2，6）的线段上。每头奶牛按一定速度向右移动（在+x方向），在指定的整数时间内她向右移动1单位的距离。
</p>
<p>
FJ不是特别兴奋，他的牛只是在外面跑，而不是在谷仓产奶。他计划在比赛结束后给他们讲一堂课。为了确定哪些他的牛是参与了比赛，FJ将自己定位在（0,0），在+Y方向沿射线进行观察。随着比赛开展，FJ能看到一些牛，因为他沿着射线在看。也就是说，某一头奶牛会不可见，如果在她穿越视线FJ的视线的整个时间内，另一头母牛始终在她的&#34;前面&#34;。
</p>
<p>
请计算FJ在整个比赛期间可以看到的奶牛数量。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
 
</p>
<p>
输入的第一行包含N，以下有N行，分别用三个整数x y r，描述了一头奶牛，对应于奶牛在时间t = 0时，她的左端点是在（x，y），移动1单位距离的速度是r单位时间。x的取值的范围是-1000..-1，y的取值范围是1..1000000（明显每头奶牛会防止任何可能的碰撞），r值的范围在1..1000000。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
一个整数，FJ在整个比赛可以看到的（T = 0起）奶牛数量。
</p>
<h3>
【样例输入】
</h3>
<pre>3
-2 1 3
-3 2 3
-5 100 1</pre>
<h3>
【样例输出】
</h3>
<pre>2</pre>
<h3>
【提示】
</h3>
<p>
FJ可以看到牛1、牛2而看不到牛3。
</p>
<p>
题目原文：
</p>
<p>
Farmer John&#39;s N cows (1 &lt;= N &lt;= 50,000) appear to be stampeding along the road at the front of FJ&#39;s farm, but they are actually just running in a foot race to see which cow is the fastest. Viewed from above, each cow is represented by a unit-length horizontal line segment, specified by the coordinates of its left corner point at time t=0. For example, (-3,6) would specify a cow who at time t=0 is represented by the segment from (-3,6) to (-2,6). Each cow is moving to the right (in the +x direction) at a certain rate, specified by the integer amount of time it takes her to move 1 unit to the right. FJ is not particularly thrilled that his cows are outside running instead of in the barn producing milk. He plans to admonish them with a stern lecture after the race ends. In order to determine which of his cows are participating in the race, FJ situates himself at (0,0) and looks along a ray extending in the +y direction. As the race unfolds, FJ sees a cow if she is ever the first cow visible along this ray. That is, a cow might not be visible if another cow is &#34;in front&#34; of her during the entire time she crosses FJ&#39;s line of sight. Please compute the number of cows FJ can see during the entire race.
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>
