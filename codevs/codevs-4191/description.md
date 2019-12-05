<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　小Z童鞋一日意外的看到小X写了一个正则表达式的高级程序，这个正则表达式程序仅仅由字符“0”,“1”，“.”和“*”构成，但是他能够匹配出所有在OJ上都AC的程序的核心代码！小Z大为颇感好奇，于是他决定入侵小X的电脑上去获得这个正则表达式的高级程序。 </p><p>　　在Internet网络中的每台电脑并不是直接一对一连通的，而是某些电脑之间存在单向的网络连接，也就是说存在A到B的连接不一定存在B到A的连接，并且有些连接传输速度很快，有些则很慢，所以不同连接传输所花的时间是有大有小的。另外，如果存在A到B的连接的同时也存在B到A的连接的话，那么A和B实际上处于同一局域网内，可以通过本地传输，这样花费的传输时间为0。 </p><p>　　现在小Z告诉你整个网络的构成情况，他希望知道从他的电脑（编号为1），到小X的电脑（编号为n）所需要的最短传输时间。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数n, m， 表示有n台电脑，m个连接关系。 </p><p>接下来m行，每行三个整数u,v,w，表示从电脑u到电脑v传输信息的时间为w。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅一行为最短传输时间。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>测试点#1</p><p>3 2</p><p>1 2 1</p><p>2 3 1</p><p>测试点#2</p><p>5 5</p><p>1 2 1</p><p>2 3 6</p><p>3 4 1</p><p>4 2 1</p><p>3 5 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>测试点#1</p><p>2<br></p><p>测试点#2</p><p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于40%的数据，1&lt;=n&lt;=1000, 1&lt;=m&lt;=10000</p><p>对于70%的数据，1&lt;=n&lt;=5000, 1&lt;=m&lt;=100000</p><p>对于100%的数据，1&lt;=n&lt;=200000, 1&lt;=m&lt;=1000000</p>
</div>
</div>