# 题目描述


<p>
问题描述
</p>
<p>
古老的Byte山上有一处神秘的连环洞穴。考古学家们为了对这个洞穴进行研究，组织了一次探险活动。他们花了几天的时间仔细地翻阅了前人留下的资料，对该连环洞穴有了大致的了解。
</p>
<p>
这是一个有许多不同的小溶洞组成的连环洞穴，每个小溶洞都分布在不同的地层中，并且可能通过洞穴隧道与其他小溶洞相通。
</p>
<p>
考古学家们已经发现了作为连环洞穴的入口的一个小溶洞，并且根据前人的资料，绘制出了洞穴的地图，标明了哪些小溶洞之间是有洞穴隧道相连的。
</p>
<p>
富有冒险和激情的考古学家们都期望自己能够独自进行探险活动。于是，他们又提出了这样的要求：<strong>从入口的溶洞出发时，每个人都选择一条不同的 洞穴隧道前进；探险结束时，每个人都是通过不同的洞穴隧道抵达最底层的小溶洞。</strong>当然了，这些考古学家也达成了妥协：在探险的过程中，可以有不止一名的考古 学家通过同一条洞穴隧道。 为了体现这次探险活动的一往直前的精神，考古学家们还决定，要从小溶洞入口进入，一直抵达最底层的溶洞！每个考古学家探险路线上通过的小溶洞所在的地层必 须比该路线上前一个溶洞的地层低。
</p>
<p>
考古学家提出来如此多的要求使得本次探险活动的组织者犯了愁，他究竟最多能邀请多少位考古学家来参加这项活动呢？
</p>
<p>
输入文件
</p>
<p>
第一行是一个数N（2&lt;=N&lt;=200），表示小溶洞的总数。每个小溶洞用一个数字标号，标号越大，该小溶洞的所在地层越低。入口的小溶洞标号为1，最底层的小溶洞标号为N。
</p>
<p>
以下共有N-1行，第i+1行表示的是标号为i个溶洞与哪些溶洞相连。每行第一个数字是Mi，表示共与Mi个溶洞相连，随后是Mi个数字，为这些溶洞的标号。
</p>
<p>
输出文件
</p>
<p>
输出文件只有一行，为一个整数，表示的是最多能有多少位考古学家参加这次活动。
</p>
<p>
样例输入
</p>
<pre>12
4 3 4 2 5
1 8
2 9 7
2 6 11
1 8
2 9 10
2 10 11
1 12
2 10 12
1 12
1 12
</pre>
<p>
该数据描述的是下面这样一个连环洞穴：
</p>
<p>
<span><img width="196" height="336" alt="Image:Gro.png" src="../../mw/images/b/be/Gro.png" border="0"/></span> 
</p>
<p>
样例输出
</p>
<pre>3
</pre>