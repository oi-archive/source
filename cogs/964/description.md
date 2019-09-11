# 题目描述


<p>
NOI2012 Day1
</p>
<p>
<img src="/upload/image/20140115/20140115222749_10743.jpg" alt=""/> 
</p>
<h2 style="font-family:arial, verdana, helvetica, sans-serif;color:blue;">
Description
</h2>
<p>
</p><p>
<span style="font-size:medium;">蛋蛋非常热衷于挑战自我，今年暑假他准备沿川藏线骑着自行车从成都前往拉萨。川藏线的沿途有着非常美丽的风景，但在这一路上也有着很多的艰难险阻，路况变化多端，而蛋蛋的体力十分有限，因此在每天的骑行前设定好目的地、同时合理分配好自己的体力是一件非常重要的事情。<br/>
由于蛋蛋装备了一辆非常好的自行车，因此在骑行过程中可以认为他仅在克服风阻做功（不受自行车本身摩擦力以及自行车与地面的摩擦力影响）。某一天他打算骑$N$段路，每一段内的路况可视为相同：</span>
</p>
<p>
<span style="font-size:medium;">对于第$i$段路，我们给出有关这段路况的$3$个参数 $s_i , k_i , v_{i&#39;}$ ，</span>
</p>
<p>
<span style="font-size:medium;">$s_i$ 表示这段路的长度， </span>
</p>
<p>
<span style="font-size:medium;">$k_i$ 表示这段路的风阻系数， </span>
</p>
<p>
<span style="font-size:medium;">$v_{i&#39;}$ 表示这段路上的风速（表示在这段路上他遇到了顺风，反之则意味着他将受逆风影响）。</span>
</p>
<p>
<span style="font-size:medium;">若某一时刻在这段路上骑车速度为v，则他受到的风阻大小为 $F = k_i ( v - v_{i&#39;} )^2$</span>
</p>
<p>
<span style="font-size:medium;">（这样若在长度为$s$的路程内保持骑行速度$v$不变，则他消耗能量（做功）$E = k_i ( v - v_{i&#39;} )^2 s）$。<br/>
设蛋蛋在这天开始时的体能值是 $Eu$ ，请帮助他设计一种行车方案，使他在有限的体力内用最短的时间到达目的地。请告诉他最短的时间$T$是多少。<br/>
<br/>
【评分方法】<br/>
本题没有部分分，你程序的输出只有和标准答案的差距不超过$0.000001$时，才能获得该测试点的满分，否则不得分。<br/>
<br/>
【数据规模与约定】<br/>
对于10%的数据，$N=1$<br/>
对于40%的数据，$N&lt;=2$<br/>
对于60%的数据，$N&lt;=100$<br/>
对于80%的数据，$N&lt;=1000$ <br/>
对于所有数据，$N &lt;= 10000，0 &lt;= Eu &lt;= 108，0 &lt; s_i &lt;= 100000，0 &lt; k_i &lt;= 1，-100 &lt; v_{i&#39;} &lt; 100。数据保证最终的答案不会超过10^5$。<br/>
<br/>
【提示】<br/>
必然存在一种最优的体力方案满足：蛋蛋在每段路上都采用匀速骑行的方式。<br/>
<br/>
</span> 
</p>
<p></p>
<h2 style="font-family:arial, verdana, helvetica, sans-serif;color:blue;">
Input
</h2>
<div style="font-family:arial, verdana, helvetica, sans-serif;background-color:#E4F0F8;margin:0px;padding:0px 20px;font-size:14px;">
<p>
<span>第一行包含一个正整数$N$和一个实数$Eu$，分别表示路段的数量以及蛋蛋的体能值。 接下来$N$行分别描述$N$个路段，每行有3个实数 $s_i , k_i , v_{i&#39;}$ ，分别表示第 $i$ 段路的长度，风阻系数以及风速。<br/>
</span> 
</p>
</div>
<h2 style="font-family:arial, verdana, helvetica, sans-serif;color:blue;">
Output
</h2>
<div style="font-family:arial, verdana, helvetica, sans-serif;background-color:#E4F0F8;margin:0px;padding:0px 20px;font-size:14px;">
<p>
<span>输出一个实数$T$，表示蛋蛋到达目的地消耗的最短时间，要求至少保留到小数点后6位。<br/>
</span> 
</p>
</div>
<h2 style="font-family:arial, verdana, helvetica, sans-serif;color:blue;">
Sample Input
</h2>
<div style="font-family:arial, verdana, helvetica, sans-serif;background-color:#E4F0F8;margin:0px;padding:0px 20px;font-size:14px;">
<span style="font-family:monospace;background-color:#8DB8FF;font-size:18px;"><br/>
3 10000<br/>
10000 10 5<br/>
20000 15 8<br/>
50000 5 6<br/>
<br/>
</span> 
</div>
<h2 style="font-family:arial, verdana, helvetica, sans-serif;color:blue;">
Sample Output
</h2>
<div style="font-family:arial, verdana, helvetica, sans-serif;background-color:#E4F0F8;margin:0px;padding:0px 20px;font-size:14px;">
<span style="font-family:monospace;background-color:#8DB8FF;font-size:18px;">12531.34496464 <br/>
【样例说明】 一种可能的方案是：蛋蛋在三段路上都采用匀速骑行的方式，其速度依次为5.12939919, 8.03515481, 6.17837967。</span> 
</div>
<p>
<br/>
</p>
