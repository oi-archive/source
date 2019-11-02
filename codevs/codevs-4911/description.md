<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>来源：usaco-2015-dec<br>Farm John 最近新建了一批巨大的牛棚。这些牛棚构成了一个N*N的矩形网络。（1&lt;n&lt;100)<br>然而bessie十分怕黑，他想计算可以把多少个牛棚的灯打开。</p><p>有N*N个房间，组成了一张N*N的网格图，Bessie一开始位于左上角(1,1)，并且只能上下左右行走。</p><p><br></p><p>一开始，只有(1,1)这个房间的灯是亮着的，Bessie只能在亮着灯的房间里活动。</p><p><br></p><p>有另外M条信息，每条信息包含四个数a,b,c,d，表示房间(a,b)里有房间(c,d)的灯的开关。</p><p><br></p><p>请计算出最多有多少个房间的灯可以被打开</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，两个数：N，M（1&lt;m&lt;200000);<br>第2-m+1行：坐标（x1，y1），（x2，y2）代表房间的坐标（x1，y1）及可以点亮的·房间的坐标(x2,y2);</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数，最多可以点亮的房间数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 6<br>1 1 1 2<br>2 1 2 2<br>1 1 1 3<br>2 3 3 1<br>1 3 1 2<br>1 3 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>注意时间限制和空间限制。</p><p>注意输入方式，c++的朋友们我可以告诉你用cin必爆。</p><p>这里，如果你看得懂英文的话，这里有样例的说明。<br>Here, Bessie can use the switch in (1,1)to turn on lights in (1,2)and (1,3). She can then walk to (1,3)and turn on the lights in (2,1)，from which she can turn on the lights in (2,2). The switch in (2,3)is inaccessible to her, being in an unlit room. She can therefore illuminate at most 5 rooms.</p><p>4M空间能过，水算法2M，神算法1M就够了。不要乱开空间，相信我4个1000*1000足够了。</p>
</div>
</div>