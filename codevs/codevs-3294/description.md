<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一条单向的铁路线上，依次有编号为1, 2, &amp;hellip;, n的n个火车站。每个火车站都有一个级别，最低为1级。现有若干趟车次在这条线路上行驶，每一趟都满足如下要求：如果这趟车次停靠了火车站x，则始发站、终点站之间所有级别大于等于火车站x的都必须停靠。（注意：起始站和终点站自然也算作事先已知需要停靠的站点）<br>例如，下表是5趟车次的运行情况。其中，前4趟车次均满足要求，而第5趟车次由于停靠了3号火车站（2级）却未停靠途经的6号火车站（亦为2级）而不满足要求。</p><p> </p><p>现有m趟车次的运行情况（全部满足要求），试推算这n个火车站至少分为几个不同的级别。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含2个正整数n, m，用一个空格隔开。<br>第i+1行（1&amp;le;i&amp;le;m）中，首先是一个正整数s_i（2&amp;le;s_i&amp;le;n），表示第i趟车次有s_i个停靠站；接下来有s_i个正整数，表示所有停靠站的编号，从小到大排列。每两个数之间用一个空格隔开。输入保证所有的车次都满足要求。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，包含一个正整数，即n个火车站最少划分的级别数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>[Sample 1]<br>9 2<br>4 1 3 5 6<br>3 3 5 6<br>[Sample 2]<br>9 3<br>4 1 3 5 6<br>3 3 5 6<br>3 1 5 9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>[Sample 1]<br>2<br>[Sample 2]<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，1 &amp;le; n, m &amp;le; 10；<br>对于50%的数据，1 &amp;le; n, m &amp;le; 100；<br>对于100%的数据，1 &amp;le; n, m &amp;le; 1000。</p>
</div>
</div>