# 题目描述


<h3>
【题目描述】
</h3>
<p>
$Hoshizora\ Rin$是个特别好动的少女。
</p>
<p>
一天$Rin$来到了一个遥远的都市。这个都市有$N$个建筑，编号从$1$到$N$，其中市中心编号为$1$，这个都市有$M$条双向通行的街道，每条街道连接着两个建筑，其中某些街道首尾相连连接成了一个环。$Rin$通过长时间的走访，已经清楚了这个都市的两个特点：
</p>
<ol>
<li>
从市中心出发可以到达所有的建筑物。
</li>
<li>
任意一条街道最多存在与一个简单环中。
</li>
</ol>
<p>
令$Rin$心花怒放的是，每个建筑物都会有拉面售卖。拉面有很多不同的种类，但对于$Rin$而言只有油腻程度的不同，因此我们把油腻程度相同的拉面看做同一种拉面。由于不同建筑物的拉面的油腻程度可能不同，我们用一个正整数来表示拉面的油腻程度。
</p>
<p>
要知道，拉面可是$Rin$的最爱，但是现在到了下班高峰期，都市的交通变得非常的堵塞。$Rin$只能通过没有被堵死的街道通行，去品尝所在建筑物的拉面。
</p>
<p>
现在$Rin$想知道，如果她正在编号为$x$的建筑物，那么在从市中心到$x$的所有简单路径经过的街道都被堵死的情况下，$Rin$可以品尝到的拉面中（注意没有出现的拉面是不能算在里面的）：
</p>
<ol>
<li>
油腻程度$\leq y$且品尝次数为<strong>奇数</strong>次的拉面有多少种？
</li>
<li>
油腻程度$\leq y$且品尝次数为<strong>偶数</strong>次的拉面有多少种？
</li>
</ol>
<h3>
【输入格式】
</h3>
<p>
第一行两个正整数$N,M$，含义如题所示。
</p>
<p>
第二行一共$N$个正整数，第$i$个数$A_i$表示第$i$个建筑物出售的拉面的油腻程度。
</p>
<p>
接下来$M$行，每行两个正整数$x,y$，表示在建筑物$x,y$之间有一条双向通行的街道。数据保证$1 \leq x &lt; y \leq N$。
</p>
<p>
接下来一行一个正整数$Q$，表示询问个数。
</p>
<p>
接下来$Q$行每行三个非负整数$ty,x,y$，$x$表示询问的建筑物编号，$y$表示油腻程度的限制，$ty=0$时表示询问偶数，$ty=1$表示询问奇数。
</p>
<h3>
【输出格式】
</h3>
<p>
一共$Q$行，对于每个询问输出一个答案。
</p>
<h3>
【样例输入】
</h3>
<pre>5 6
2 1 6 7 7
1 2
1 3
2 4
4 5
4 5
1 3
3
0 3 2
0 3 1
0 1 7
</pre>
<h3>
【样例输出】
</h3>
<pre>0
0
1
</pre>
<h3>
【样例解释】
</h3>
<p>
$3$号建筑物只能到达它自己，而$1$号建筑物可以到达所有建筑物。
</p>
<h3>
【数据范围】
</h3>
<p>
提示：请注意数据范围中的$\leq$，特殊条件中提到的$y$均为询问中的$y$，对于$100\%$的数据，有$y \leq 10^6$。
</p>
<p>
<img alt="" src="/upload/image/20160424/20160424081956_99917.png"/> 
</p>
<h3>
【来源】
</h3>
<p>
HAOI2016上午第三题 部分题面由ck进行调整
</p>
