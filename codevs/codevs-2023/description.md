<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       这天，小蛮进到了一个神奇的宫殿。这个宫殿有n个房间，其中任意两个房间之间都有唯一的一条路径相连。1号房间是宫殿的入口。对于其中的一些房间有道路相连，经过不同的道路需要不同的时间。</p>
<p>       每个房间里有一些宝物，对于第i个房间，里面有x[i]件宝物，获取第j块宝物需要时间c[j]并且获得价值v[j]。现在，小蛮已经站在了1号房间，她想要知道她能够获得多少价值的宝物。</p>
<p>       记住，大灰狼m时间之后就会过来，在那<strong><span style="text-decoration: underline;">之前</span></strong>，小蛮必须从1号房间出来，你不能让小蛮被大灰狼抓住。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入数据包含2n行。</p>
<p>       第一行为两个整数n和m，含义如题目所示。</p>
<p>       以下n行，每行包含若干个整数，每行的第一个整数x[i]表示第i个房间里放有的宝物数目，之后x[i]对整数v[j]，c[j]分别表示该宝物的价值和获取所需的时间。</p>
<p>       以下n-1行，每行三个整数a,b,t表示可以从房间a到房间b，时间为t，注意<strong><span style="text-decoration: underline;">在小蛮返回时还要用掉</span></strong><strong><span style="text-decoration: underline;">t</span></strong>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数，表示小蛮可以获得宝物的最大价值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 21</p>
<p>1 20 4</p>
<p>2 100 4 200 10</p>
<p>1 10 2</p>
<p>1 20 4</p>
<p>2 200 4 100 4</p>
<p>2 200 4 200 4</p>
<p>1 2 2</p>
<p>1 3 2</p>
<p>1 4 2</p>
<p>4 5 2</p>
<p>4 6 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>420</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，宫殿的结构是二叉树。</p>
<p>对于100%的数据，n&lt;=300，m&lt;=200，0&lt;c[j],t, x[i]&lt;=10，v[j]&lt;=10^9。</p>
<p>保证最后答案不超过maxlongint。</p>
</div>
</div>