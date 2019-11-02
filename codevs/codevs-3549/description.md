<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Mimori知道了，只有毁灭掉神树，才能保护Yuuna和大家。但是，想要到神树那里需要</p><p>穿越树海，树海非常危险，需要携带一定量的精灵才能通过。</p><p>她把树海抽象为一张有n个点和m条边的无向连通图，无重边和自环(三无图)，结点编号为</p><p>1~n，结点之间有双向道路连接。</p><p>每个结点有一个精灵需求数，u结点的精灵需求数记作w[u]。</p><p>通过这些边要支付一定数量的精灵！费用规定如下：</p><p>①若是普通道路(记作类别0)，她需要支付1只精灵。</p><p>②若是特殊道路(记作类别1)，她需要支付自己当前携带的精灵数的1/20，若不满20</p><p>只则按20只计算。(例如、若她身上此时有10只精灵，则需要支付1只；若有69只精灵，</p><p>则需要支付4只。)</p><p>她定义了一个整数S，令S等于每对结点之间的最优路径长度之和。我们用d(u,v)表示u,v</p><p>之间的最优路径长度，d(u,v)被定义为从u沿路径到达v，且身上至少还有w[v]只精灵的</p><p>前提下，初始携带的的最少精灵数(注意!仅仅在边上要支付精灵,在结点处不支付,但是你需要满足</p><p>终点的精灵需求数)。(例如、结点数等于3时，</p><p>S=d(1,1)+d(1,2)+d(1,3)+d(2,1)+d(2,2)+d(2,3)+d(3,1)+d(3,2)+d(3,3))</p><p>那么问题来了，她想删除一条边后使得新的S值S’最大。当然，你必须保证删除后图仍</p><p>然连通才行。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包括2个整数n，m，分别表示图的顶点数和边数。</p><p>第二行包括n个整数w1...wn，表示n个结点的精灵需求数。</p><p>接下来m行，每行包括三个整数u，v，op，代表一条连接u、v的无向边，其类别为op(参</p><p>见题目描述)。</p><p>保证图连通，且无重边和自环。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一行，包括2个整数，为S和最大的S’。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入样例1】</p><p>5 6</p><p>15 14 10 14 12</p><p>1 2 0</p><p>2 3 0</p><p>3 4 1</p><p>2 5 1</p><p>3 5 1</p><p>3 1 1</p><p><br></p><p>【输入样例2】</p><p>20 40</p><p>19 78 16 89 1 19 85 18 44 36 69 56 50 30 60 100 31 70 8 13</p><p>1 2 1</p><p>1 3 0</p><p>2 4 1</p><p>4 5 0</p><p>4 6 0</p><p>1 7 0</p><p>3 8 0</p><p>8 9 1</p><p>7 10 1</p><p>2 11 1</p><p>5 12 0</p><p>3 13 0</p><p>10 14 0</p><p>2 15 1</p><p>4 16 0</p><p>3 17 0</p><p>8 18 0</p><p>11 19 1</p><p>12 20 0</p><p>15 8 1</p><p>10 9 1</p><p>2 13 0</p><p>13 4 0</p><p>14 15 1</p><p>7 14 0</p><p>15 18 1</p><p>3 19 1</p><p>6 9 1</p><p>11 7 0</p><p>20 14 1</p><p>5 7 0</p><p>16 10 1</p><p>12 19 1</p><p>19 14 1</p><p>8 11 0</p><p>15 20 0</p><p>16 17 0</p><p>19 7 0</p><p>5 19 0</p><p>8 5 0</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【输出样例1】</p><p>353 357</p><p><br></p><p>【输出样例2】</p><p>18918 19068</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=110，<br></p><p>1&lt;=m&lt;=1100，</p><p>1&lt;=u&lt;=n，</p><p>1&lt;=v&lt;=n，u≠v，</p><p>0&lt;=op&lt;=1，</p><p>1&lt;=wi&lt;=100(1&lt;=i&lt;=n)，</p><p>保证图连通，且无重边和自环。</p><p>特殊数据：</p><p>测试点 n m 备注</p><p>0 &lt;=5 &lt;=8 op=0</p><p>1 &lt;=5 &lt;=8 op=0</p><p>2 &lt;=70 &lt;=140 op=0</p><p>3 &lt;=70 &lt;=140 op=0</p><p>4 &lt;=70 &lt;=140</p><p>5 &lt;=70 &lt;=140</p><p>6 &lt;=110 &lt;=1100</p><p>7 &lt;=110 &lt;=1100</p><p>8 &lt;=110 &lt;=1100</p><p>9 &lt;=110 &lt;=1100</p><p><br></p>
</div>
</div>