<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一天，由于某种穿越现象作用，你来到了传说中的小人国。小人国的布局非常奇特，整个国家的交通系统可以被看成是一个2行C列的矩形网格，网格上的每个点代表一个城市，相邻的城市之间有一条道路，所以总共有2C个城市和3C-2条道路。</p>
<p>小人国的交通状况非常槽糕。有的时候由于交通堵塞，两座城市之间的道路会变得不连通，直到拥堵解决，道路才会恢复畅通。初来咋到的你决心毛遂自荐到交通部某份差事，部长听说你来自一个科技高度发达的世界，喜出望外地要求你编写一个查询应答系统，以挽救已经病入膏肓的小人国交通系统。</p>
<p>小人国的交通部将提供一些交通信息给你，你的任务是根据当前的交通情况回答查询的问题。交通信息可以分为以下几种格式：</p>
<p>Close r1 c1 r2 c2：相邻的两座城市(r1,c1)和(r2,c2)之间的道路被堵塞了；</p>
<p>Open r1 c1 r2 c2：相邻的两座城市(r1,c1)和(r2,c2)之间的道路被疏通了；</p>
<p>Ask r1 c1 r2 c2：询问城市(r1,c1)和(r2,c2)是否连通。如果存在一条路径使得这两条城市连通，则返回Y，否则返回N； </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行只有一个整数C，表示网格的列数。接下来若干行，每行为一条交通信息，以单独的一行“Exit”作为结束。我们假设在一开始所有的道路都是堵塞的。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个查询，输出一个&ldquo;Y&rdquo;或&ldquo;N&rdquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>Open 1 1 1 2</p>
<p>Open 1 2 2 2</p>
<p>Ask 1 1 2 2</p>
<p>Ask 2 1 2 2</p>
<p>Exit</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Y</p>
<p>N</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对30%测试数据，我们保证C≤1000，信息条数≤1000；</p>
<p>对100%测试数据，我们保证 C≤100000，信息条数≤100000。</p>
</div>
</div>