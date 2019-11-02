<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>假定海岸线是一条无限延伸的直线，陆地在海岸线的一边，大海在另一侧。海中有许多岛屿，每一个小岛我们可以认为是一个点。现在要在海岸线上安装雷达，雷达的覆盖范围是d，也就是说大海中一个小岛能被安装的雷达覆盖，那么它们之间的距离最大为d。</p>
<p> </p>
<p>我们使用平面直角坐标系，定义海岸线是x轴，大海在x轴上方，陆地在下方。给你海中每一个岛屿的坐标位置（x,y）和要安装的雷达所覆盖的范围d，你的任务是写一个程序计算出至少安装多少个雷达能将所有的岛屿覆盖。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数n（1≤n≤100000）和d，分别表示海中岛屿的数目和雷达覆盖的范围半径d。</p>
<p>接下来n行，每行两个整数，表示每个岛屿的坐标位置（x,y）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个整数，即能将所有岛屿全部覆盖至少安装的雷达个数，如果无解则输出&ldquo;-1&rdquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>3 2</pre>
<pre>1 2</pre>
<pre>-3 1</pre>
<pre>2 1</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>（1≤n≤100000）</p>
<p>注意会输出-1</p>
</div>
</div>