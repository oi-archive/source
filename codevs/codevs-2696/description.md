<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">    话说小</span><span style="font-family: 'Calibri','sans-serif';">X</span><span style="">在孩提时，都会做标准的蛇形矩阵了，发现很好<span style="">玩</span>。现在的小</span><span style="font-family: 'Calibri','sans-serif';">X</span><span style="">很</span><span style="">想对其进行改版，变为如下图类型的一个无限大蛇形数阵.</span></p>
<p>    令 S(x)表示以1为左上角，x为右下角的矩形内所有数之和。例如 S(12)就是 具有深色背景的数之和。</p>
<p>    给定 n，对于“以1为左上角，n为右下角的矩形”内的每一个数i，计算所有 S(i)之和。例如，当 n=8 时，所求结果为S(1)+S(2)+S(9)+S(4)+S(3)+S(8)=1+3+<span style="">12+5+10+27=58。</span></p>

<img src="/source/codevs/codevs-2696/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yNjk2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8yNjk2LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件仅包含一个整数n。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出所求结果除以1,000,000,007的余数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
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
<p>58</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，1&lt;=<em>n</em>&lt;=100<sub>；</sub>；</p>
<p>对于40%的数据，1&lt;=<em>n</em>&lt;=5000；</p>
<p>对于60%的数据，1&lt;=<em>n</em>&lt;=1e6；</p>
<p>对于100%的数据，1&lt;=<em>n</em>&lt;=1e10。</p>
</div>
</div>