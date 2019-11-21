<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Up主家终于买电脑了，但是接下来有各种问题要处理。首要解决的问题就是网络问题。他要从移动公司开始，通过一些基站来传递网络到他家。</p><p>为了简化问题，我们假设移动公司，所有的基站，up主家位于同一条直线上，他们都位于这一条直线上的某一点x，这些点不会重合。每个基站发射和接收的范围都是一个切于地面的圆，发射的半径r1是固定的，接收半径r2是可调的的。如下图：</p><p> </p><p>一个点<span style="font-family: 'Times New Roman';">i</span><span style="">如果能从另一个点</span><span style="font-family: 'Times New Roman';">j</span><span style="">接收到信号</span>(当且仅当x[j] &lt; x[i])，必须满足<span style="font-family: 'Times New Roman';">i</span><span style="">的接收范围与</span><span style="font-family: 'Times New Roman';">j</span><span style="">的发射范围相切，并且需要付</span>sqrt(r2[i])的额外费用。同时启动每一个点i都需要费用v[i].</p><p>当然一个点如果能够发射的up主家只需要这个点的发射范围与up主家所在的竖线相切或相交即可，如下图：</p><p> </p><p>当然费用越少就越好咯，于是up主想要请你帮他的忙。</p>

<img src="/source/codevs/codevs-1807/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xODA3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTgwNy5qcGc=.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数n,m.表示基站个数(包括移动公司)，up主家的坐标。<span style="font-family: 'Times New Roman';">(</span><span style="">保证大等于所以基站的坐标</span><span style="font-family: 'Times New Roman';">)</span></p><p>记下来n行，每行三个整数x[i],r1[i],v[i],表示每个基站的坐标，发射范围以及费用。</p><p>X[i]是按照坐标从小到大输入的，移动公司位于最小的那个坐标。</p><p>R为1..n的排列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个实数，保留小数点后三位。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 33</p><p>5 4 660</p><p>10 2 2040</p><p>11 6 3207</p><p>14 5 2006</p><p>18 3 6130</p><p>19 9 3363</p><p>22 1 1265</p><p>25 8 2836</p><p>27 10 7961</p><p>29 7 9075</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3501.000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据n&lt;=2000</p><p>对于60%的数据n&lt;=100000</p><p>对于100%的数据 n&lt;=5*1000000,x[i],m &lt;= 10^12,v[i] &lt;= 10000</p>
</div>
</div>