<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>逆时针给出<em>n</em>个凸多边形的顶点坐标，求它们交的面积</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有一个整数<em>n</em>，表示凸多边形的个数，以下依次描述各个多边形。第i个多边形的第一行包含一个整数<em>m<sub>i</sub></em>，表示多边形的边数，以下<em>m<sub>i</sub></em>行每行两个整数，逆时针给出各个顶点的坐标。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个实数，表示相交部分的面积，保留三位小数</p>

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
<p>6</p>
<p>-2 0</p>
<p>-1 -2</p>
<p>1 -2</p>
<p>2 0</p>
<p>1 2</p>
<p>-1 2</p>
<p>4</p>
<p>0 -3</p>
<p>1 -1</p>
<p>2 2</p>
<p>-1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5.233</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>50%的数据满足：<em>n</em>=2</p>
<p>100%的数据满足：2&lt;=<em>n</em>&lt;=10，3&lt;=<em>m<sub>i</sub></em>&lt;=50，每维坐标为[-1000,1000]内的整数</p>
</div>
</div>