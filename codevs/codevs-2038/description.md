<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农夫John发现做出全威斯康辛州最甜的黄油的方法：糖。把糖放在一片牧场上，他知道N（1&lt;=N&lt;=500）只奶牛会过来舔它，这样就能做出能卖好价钱的超甜黄油。当然，他将付出额外的费用在奶牛上。</p>
<p>农夫John很狡猾。他知道他可以训练这些奶牛，让它们在听到铃声时去一个特定的牧场。他打算将糖放在那里然后下午发出铃声，以至他可以在晚上挤奶。</p>
<p>农夫John知道每只奶牛都在各自喜欢的牧场呆着（一个牧场不一定只有一头牛）。给出各头牛在的牧场和牧场间的路线，找出使所有牛到达的路程和最短的牧场（他将把糖放在那）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行: 三个数：奶牛数N，牧场数P（2&lt;=P&lt;=800），牧场间道路数C(1&lt;=C&lt;=1450).</p>
<p>第二行到第N+1行: 1到N头奶牛所在的牧场号.</p>
<p>第N+2行到第N+C+1行： 每行有三个数：相连的牧场A、B，两牧场间距（1&lt;=D&lt;=255），当然,连接是双向的.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>一行 输出奶牛必须行走的最小的距离和.</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>3 4 5
2
3
4
1 2 1
1 3 5
2 3 7
2 4 3<br>3 4 5</pre>
<pre><strong>样例图形</strong></pre>
<pre>         P2
P1 @--1--@ C1
\    |\
\   | \
5  7  3
\ |   \
\|    \ C3
C2 @--5--@
P3    P4</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>8</pre>
<pre><span>{说明： 放在4号牧场最优. }</span></pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>