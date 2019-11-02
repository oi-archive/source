<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定N（小于等于8）个点的地图，以及地图上各点的相邻关系，请输出用4种颜色将地图涂色的所有方案数（要求相邻两点不能涂成相同的颜色）</p>
<p>数据中0代表不相邻，1代表相邻</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n，代表地图上有n个点</p>
<p>接下来n行，每行n个整数，每个整数是0或者1。第i行第j列的值代表了第i个点和第j个点之间是相邻的还是不相邻，相邻就是1，不相邻就是0.</p>
<p>我们保证a[i][j] = a[j][i] （a[i,j] = a[j,i]）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>染色的方案数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8<br>0 0 0 1 0 0 1 0 <br>0 0 0 0 0 1 0 1 <br>0 0 0 0 0 0 1 0 <br>1 0 0 0 0 0 0 0 <br>0 0 0 0 0 0 0 0 <br>0 1 0 0 0 0 0 0 <br>1 0 1 0 0 0 0 0 <br>0 1 0 0 0 0 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>15552</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=8</p>
</div>
</div>