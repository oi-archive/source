<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    给定一个正N边形，可以通过连线将这个多边形分割成N-2个三角形，问这N-2个三角形中恰有k个等腰三角形的分割方法有多少？这个值可能很大，输出对9397取模的结果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数n和k。(3&lt;=n&lt;=50，0&lt;=k&lt;=n-2).</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数，表示正n边形切割成n-2个三角形，其中恰有k个等腰三角形的分割方法，结果模9397。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2</p>
<p>3 0</p>
<p>5 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p> 2</p>
<p>0</p>
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于第一种情况下，我们之间可以有一个顶点0和2或1和3之间的对角顶点。在这两种情况下，有2个等腰的三角形。<br>    对于第二个案件中，只有一个等边三角形的分割不含对角线，只有一等腰三角形（多边形本身）。<br>    对于第三种情况，一个正五边形有5个三角剖分。每个顶点都与它们不相邻的两点连接。</p>
</div>
</div>