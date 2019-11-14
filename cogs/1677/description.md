# 题目描述


<h3>
【题目描述】
</h3>
<p>
两只青蛙在网上相识了，它们聊得很开心，于是觉得很有必要见一面。它们很高兴地发现它们住在同一条纬度线上，于是它们约定各自朝西跳，直到碰面为止。可是它们出发之前忘记了一件很重要的事情，既没有问清楚对方的特征，也没有约定见面的具体位置。不过青蛙们都是很乐观的，它们觉得只要一直朝着某个方向跳下去，总能碰到对方的。但是除非这两只青蛙在同一时间跳到同一点上，不然是永远都不可能碰面的。为了帮助这两只乐观的青蛙，你被要求写一个程序来判断这两只青蛙是否能够碰面，会在什么时候碰面。
</p>
<p>
我们把这两只青蛙分别叫做青蛙A和青蛙B，并且规定纬度线上东经 $0$ 度处为原点，由东往西为正方向，单位长度 $1$ 米，这样我们就得到了一条首尾相接的数轴。设青蛙A的出发点坐标是 $x$，青蛙B的出发点坐标是 $y$。青蛙A一次能跳 $m$ 米，青蛙B一次能跳 $n$ 米，两只青蛙跳一次所花费的时间相同。纬度线总长 $L$ 米。现在要你求出它们跳了几次以后才会碰面。
</p>
<h3>
【输入格式
</h3>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">输入只包括一行 $5$ 个整数 $x,y,m,n,L$，其中 $x≠y\lt2000000000$，$0\lt m,n\lt 2000000000$，$0\lt L\lt 2100000000$。</span> 
</p>
<h3>
【输出格式】
</h3>
<p>
<span style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;">输出碰面所需要的跳跃次数，如果永远不可能碰面则输出一行&#34;Impossible&#34;</span> 
</p>
<h3>
【样例输入】
</h3>
<pre class="sio">1 2 3 4 5</pre>
<h3>
【样例输出】
</h3>
<pre class="sio">4</pre>
<h3>
【题目来源】
</h3>
<p>
<a style="font-family:serif;font-size:16px;font-weight:normal;background-color:white;" href="http://poj.org/problem?id=1061">POJ 1061</a> 
</p>
<p>
数据已加强，未全部重测，部分原来 AC 的代码可能会 WA 或 TLE。「把刷榜的全踢下去了2333」2018.09.08
</p>
