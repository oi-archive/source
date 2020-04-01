<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>     小白在图论课上学到了一个新的概念——最小割，下课后小白在笔记本上写下了如下这段话：</p>
<p>“对于一个图，某个对图中结点的划分将图中所有结点分成两个部分，如果结点s,t不在同一个部分中，则称这个划分是关于s,t的割。</p>
<p>对于带权图来说，将所有顶点处在不同部分的边的权值相加所得到的值定义为这个割的容量，而s,t的最小割指的是在关于s,t的割中容量最小的割”</p>
<p>现给定一张无向图，小白有若干个形如“<span style="text-decoration: underline;">图中有多少对点它们的最小割的容量不超过</span><span style="text-decoration: underline;">x</span>呢”的疑问，小蓝虽然很想回答这些问题，但小蓝最近忙着挖木块，于是作为仍然是小蓝的好友，你又有任务了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行有且只有一个正整数T，表示测试数据的组数。</p>
<p>     对于每组测试数据，</p>
<p>     第一行包含两个整数n,m，表示图的点数和边数。</p>
<p>     下面m行，每行3个正整数u,v,c(1&lt;=u,v&lt;=n,0&lt;=c&lt;=10<sup>6</sup>)，表示有一条权为c的无向边(u,v)</p>
<p>     接下来一行，包含一个整数q，表示询问的个数</p>
<p>     下面q行，每行一个整数x，其含义同题目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组测试数据，输出应包括q行，第i行表示第i个问题的答案。对于点对(p,q)和(q,p)，只统计一次（见样例）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>     5 0</p>
<p>     1</p>
<p>     0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据   n&lt;=40,m&lt;=400,q&lt;=10</p>
<p>对于100%的数据  T&lt;=10,n&lt;=150,m&lt;=3000,q&lt;=30，x在32位有符号整数类型范围内。</p>
<p>    <span style="text-decoration: underline;">图中两个点之间可能有多条边</span></p>
</div>
</div>