<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>N(N&lt;5000) 张矩形的海报，照片和其他同样形状的图片贴在墙上。它们的边都是垂直的或水平的。每个矩形可以部分或者全部覆盖其他矩形。所有的矩形组成的集合的轮廓称为周长。写一个程序计算周长。</p>
<p>图 1 是一个有 7 个矩形的例子：</p>
<p><img src="/source/codevs/codevs-2149/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yMTQ5L2h0dHA6Ly9hY2UuZGVsb3MuY29tL3VzYWNvL3BpY3R1cmUtMS5naWY=.gif"></p>
<p>图 1.一个 7 个矩形的集合</p>
<p>对应的轮廓为图 2 所示的所有线段的集合：</p>
<p><img src="/source/codevs/codevs-2149/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yMTQ5L2h0dHA6Ly9hY2UuZGVsb3MuY29tL3VzYWNvL3BpY3R1cmUtMi5naWY=.gif"></p>
<p>图 2. 矩形集合的轮廓</p>
<p>所有矩形的顶点坐标均为整数。所有的坐标都在 [-10000，10000] 的范围内，并且任何一个矩形面积都为整数。结果的值可能需要 32 位有符号整数表示。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第1行: N，张贴在墙上的矩形的数目。 </span></p>
<p><span style="">第 2..N+1行 接下来的N行中，每行都有两个点的坐标，分别是矩形的左下角坐标和右上角坐标。每一个坐标由 X 坐标和 Y 坐标组成。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>只有一行，为一个非负整数，表示输入数据中所有矩形集合的轮廓长度。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>7
-15 0 5 10
-5 8 20 25
15 -4 24 14
0 -6 16 4
2 15 10 22
30 10 36 20
34 0 40 16</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>228</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>范围如题所述</p>
</div>
</div>