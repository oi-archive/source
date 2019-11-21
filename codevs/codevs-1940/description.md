<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>YT市是一个规划良好的城市，城市被东西向和南北向的主干道划分为n×n个区域。简单起见，可以将YT市看作 一个正方形，每一个区域也可看作一个正方形。从而，YT城市中包括(n+1)×(n+1)个交叉路口和2n×(n+1)条双向道路（简称道路），每条双向 道路连接主干道上两个相邻的交叉路口。下图为一张YT市的地图(n = 2)，城市被划分为2×2个区域，包括3×3个交叉路口和12条双向道路。</p>
<p> </p>
<p>小Z作为该市的市长，他根据统计信息得到了每天上班高峰期间YT<span style="">市每条道路两个方向的人流量，即在高峰期间沿 着该方向通过这条道路的人数。每一个交叉路口都有不同的海拔高度值，YT市市民认为爬坡是一件非常累的事情，每向上爬h的高度，就需要消耗h的体力。如果 是下坡的话，则不需要耗费体力。因此如果一段道路的终点海拔减去起点海拔的值为h(注意h可能是负数)，那么一个人经过这段路所消耗的体力是</span><strong style="">max</strong><span style="">{0, h}（这里</span><strong style="">max</strong><span style="">{a, b}表示取a, b两个值中的较大值）。</span></p>
<p>小Z还测量得到这个城市西北角的交叉路口海拔为0，东南角的交叉路口海拔为1(如上图所示)，但其它交叉路口的海拔高度都无法得知。小Z想知道在最理想的情况下（即你可以任意假设其他路口的海拔高度），每天上班高峰期间所有人爬坡消耗的总体力和的最小值。</p>

<img src="/source/codevs/codevs-1940/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xOTQwL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NjM2ODI0NS42NTAuOTAxNTU0MzgwMTE2LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数n，含义如上文所示。</p>
<p>接下来4n(n + 1)行，每行包含一个非负整数分别表示每一条道路每一个方向的人流量信息。输入顺序：n(n + 1)个数表示所有从西到东方向的人流量，然后n(n + 1)个数表示所有从北到南方向的人流量，n(n + 1)个数表示所有从东到西方向的人流量，最后是n(n + 1)个数表示所有从南到北方向的人流量。对于每一个方向，输入顺序按照起点由北向南，若南北方向相同时由西到东的顺序给出(参见样例输入)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出仅包含一个数，表示在最理想情况下每天上班高峰期间所有人爬坡所消耗的总体力和（即总体力和的最小值），结果四舍五入到整数。</p>

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
<p>1</p>
<p>2</p>
<p>3</p>
<p>4</p>
<p>5</p>
<p>6</p>
<p>7</p>
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据：n ≤ 3；</p>
<p>对于50%的数据：n ≤ 15；</p>
<p>对于80%的数据：n ≤ 40；</p>
<p>对于100%的数据：1 ≤ n ≤ 500，0 ≤ 流量 ≤ 1,000,000且所有流量均为整数。</p>
<p>海拔高度不一定是整数。</p>
</div>
</div>