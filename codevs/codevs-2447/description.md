<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>从一个圆孔里看一个凸多边形，为了让看到的面积至少为S，孔的半径至少需要多大？假设孔的圆心固定在(0, 0)，且(0, 0)在多边形的内部（而不是外部或边界上）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数n和一个实数S（精确到小数点后两位），表示凸多边形的顶点数和需要看到的面积。保证S不超过凸多边形的面积。以下n行每行包含两个实数x, y（精确到小数点后6位），表示各顶点的坐标。顶点按<strong><span style="text-decoration: underline;">逆时针顺序或顺时针顺序</span></strong>给出。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个实数R，保留两位小数，表示孔的最小半径。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 1.60</p>
<p>-1 -1</p>
<p>1 -1</p>
<p>0 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.93</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据满足：3&lt;=n&lt;=10，输入凸多边形是正多边形，且中心在(0, 0)</p>
<p>100%的数据满足：3&lt;=n&lt;=50</p>
</div>
</div>