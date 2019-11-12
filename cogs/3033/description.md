# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
Farmer John和他的私人教练Bessie正在徒步攀登温哥牛山。基于他们的目的（也是你的目的），这座山可以用一条长为L米（1≤L≤10^6）的长直路径表示。Farmer John会沿着这条路径以每米rF秒（1≤rF≤10^6）的固定速度攀登。由于他正在训练他的耐力，他在途中不会进行任何的休息。
</p>
<p>
<br/>
</p>
<p>
然而Bessie可以在休息站休息，在那里她能够找到一些美味的嫩草。当然，她也不能在任何地方都休息！在路径上总共有N个休息站（1≤N≤10^5）；第i个休息站距离路径的起点xi米（0&lt;xi&lt;L），美味值为ci（1≤ci≤10^6）。如果Bessie在休息站i休息了t秒，她能够得到ci*t个美味单位。
</p>
<p>
<br/>
</p>
<p>
不在休息站的时候，Bessie会以每米rB秒（1≤rB≤10^6）的固定速度攀登。由于Bessie年轻而健康，rB严格小于rF。
</p>
<p>
<br/>
</p>
<p>
Bessie想要吃到最多的美味嫩草。然而她也担心Farmer John；她认为如果在任何时候她位于Farmer John身后，Farmer John可能就会失去前进的动力了！
</p>
<p>
<br/>
</p>
<p>
帮助Bessie求出，在确保Farmer John能够完成登山的情况下，她能够获得的最多的美味单位。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
输入的第一行包含四个整数：L，N，rF，以及rB。下面N行描述了休息站。对于1至N之间的每一个i，第i+1行包含了两个整数xi和ci，描述了第i个休息站的位置和那里的草的美味值。
</p>
<p>
输入保证rF&gt;rB，并且0&lt;x1&lt;⋯&lt;xN&lt;L。注意rF和rB的单位为秒每米！
</p>
<h3>
【输出格式】
</h3>
<p>
输出一个整数：Bessie可以获得的最多的美味单位。
</p>
<h3>
【样例输入】
</h3>
<pre>10 2 4 3
7 2
8 1
</pre>
<h3>
【样例输出】
</h3>
<pre>15</pre>
<h3>
【提示】
</h3>
<p>
在这个样例中，Bessie的最佳方案是在位于x=7的休息站停留7秒（获得14个美味单位），再在位于x=8的休息站停留1秒（再获得1个美味单位，总共是15个美味单位）。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://www.usaco.org/index.php?page=feb18results" target="_blank">USACO 2018 February Contest</a> SILVER Problem 1
</p>
<p>
供题：Dhruv Rohatgi
</p>
