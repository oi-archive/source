<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个迷宫中，一开始全是缩进去的，但是他会在每一定时间将标号为xi的柱子改变状态（即缩进的变为升起，升起的变为缩进）。然后如果你在迷宫变化时站在要升起来的柱子上，你就会跟着柱子一起起来，然后你只能走已经升起的柱子了，想下来就只能站在即将要落下的柱子上了，人的速度为1秒/格，柱子升起,缩进所需时间为1秒。你的起点一定在（1，1）</p><p><br></p><p>当你将要走上一个柱子上时，如果这个格子也在变化状态，你就不能走上去</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行 n,m,k,a,b（n,m表示矩阵大小,k表示有多少种柱子,a,b表示终点坐标）<br></p><p>接下来一个n*m的矩阵，矩阵里会有0到9的数字表示各种柱子</p><p>接下来还有k行，每行表示有xi,si（si是柱子改变状态的时间，如果为0则不改变）</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果能走出迷宫，则输出最短时间</p><p>如果不能走出去，则输出-1;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 3 3 3<br></p><p>1 1 1</p><p>1 2 2</p><p>1 2 3</p><p>1 0</p><p>2 3</p><p>3 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>0&lt;n,m&lt;1000</p><p>0&lt;k&lt;11</p>
</div>
</div>