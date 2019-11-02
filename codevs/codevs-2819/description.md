<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　萌萌哒tangjz帮助OI村进行了初步的重建之后就急急忙忙的去下一个不和谐的地方了。 &gt;_&lt;</p>
<p>　　邪恶的Kinger Tangent却回来了。 QAQ</p>
<p>　　这一次Kinger Tangent拥有的毁灭力量更强大了，他试图将地心岩浆引导到地表，毁灭和谐的OI村。 QAQ</p>
<p>　　幸好村民们早有准备，在一些地方建立了避难所，在地震的时候，村民会选择离自己最近的避难所避难。</p>
<p>　　当然有可能<strong>某个村民有多个最近的避难所</strong>，这时候他就会犹豫，可选的方案越多，犹豫的时间越长，而时间长了就更容易被火山喷发出的岩石砸中，所以我们要及时的提醒那些犹豫时间<strong><span style="text-decoration: underline;">比较长</span></strong>的村民及时避难。</p>
<p>　　在本题中我们<strong>设犹豫的时间在数值上等于可选的方案数</strong>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行两个正整数N和K，表示避难所个数，<strong>可犹豫时间的最大值</strong>。</p>
<p>　　接下来N行，每行两个8位小数X<sub>i</sub>和Y<sub>i</sub>，表示第i个避难所的二维坐标。<strong>任意两个避难所之间的曼哈顿距离不小于10<sup>-3</sup>。</strong></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　第一行一个非负整数Cnt，表示有Cnt个地点的村民需要及时被提醒<strong>(犹豫时间不小于最大值)</strong>。</p>
<p>　　接下来Cnt行按照横坐标升序、横坐标相同则纵坐标升序的方式输出每个地点，每行两个实数X<sub>i</sub>和Y<sub>i</sub>，保留4位小数，表示第i个地点的坐标，即要求您的答案精度误差不超过10<sup>-4</sup>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3<br>0.00000000 0.00000000<br>4.00000000 0.00000000<br>2.00000000 4.00000000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br>2.0000 1.5000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据:<img src="/source/codevs/codevs-2819/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_TlxsZXEmYW1wO3NwYWNlOzEwLEsmYW1wO3NwYWNlOz0mYW1wO3NwYWNlOzM=.latex"><br>对于60%的数据:<img src="/source/codevs/codevs-2819/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_TlxsZXEmYW1wO3NwYWNlOzEwMCxLJmFtcDtzcGFjZTtcbGVxJmFtcDtzcGFjZTsxMDA=.latex"><br>对于100%的数据:<img src="/source/codevs/codevs-2819/img/06d543aa3906ff7ee2db97696180aa76.latex"></p>
</div>
</div>