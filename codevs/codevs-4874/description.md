<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有n块白色墙壁，编号从1到n，排成一排，现进行m次染色操作，一个墙壁的颜色是最后染的颜色，如果未操作则是白色，输出0.在第i次染色操作中，把第（i*p+q）%n+1到第（i*q+p）%n+1块墙壁染成颜色i。最后输出1到n的颜色。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行n，m，p，q</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>从1到n的颜色</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3 2 4<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br></p><p>2</p><p>3</p><p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=1000000,m&lt;=10000000<br></p><p>m*p+q,m*q+p&lt;2的31次方-1</p><p>数据很水</p>
</div>
</div>