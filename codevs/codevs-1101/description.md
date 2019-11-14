<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在平面上有 n 个点（n &lt;= 50），每个点用一对整数坐标表示。例如：当 n＝4 时，4个点的坐标分另为：p1（1，1），p2（2，2），p3（3，6），P4（0，7）</p>
<p>这些点可以用 k 个矩形（1&lt;=k&lt;4）全部覆盖，矩形的边平行于坐标轴。当 k=2 时，可用如图二的两个矩形 sl，s2 覆盖，s1，s2 面积和为 4。问题是当 n 个点坐标和 k 给出后，怎样才能使得覆盖所有点的 k 个矩形的面积之和为最小呢。约定：覆盖一个点的矩形面积为 0；覆盖平行于坐标轴直线上点的矩形面积也为0。各个矩形必须完全分开（边线与顶点也都不能重合）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>n k<br>xl y1</p>
<p>x2 y2<br>... ...<br>xn yn （0&lt;=xi,yi&lt;=500)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数，即满足条件的最小的矩形面积之和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2<br>1 1<br>2 2<br>3 6<br>0 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>k&lt;4</p>
<p>官方是k&lt;=4，但是标程解法在k=4时是有反例的。官方的数据也没有出现k=4的情况</p>
</div>
</div>