<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农夫JOHN的农场上有很多小山丘，他想要在那里布置一些保镖（……）去保卫他的那些相当值钱的奶牛们。 他想知道如果在一座小山丘上布置一名保镖的话，他总共需要招聘多少名保镖。他现在手头有一个用数字矩阵来表示地形的地图。这个矩阵有N行（ 1 &lt; N &lt;= 100 )和M列( 1 &lt; M &lt;= 70 )。矩阵中的每个元素都有一个值H_ij(0&lt;=H_ij&lt;=10,000)来表示该地区的海拔高度。请你帮助他统计出地图上到底有多少个小山丘。 小山丘的定义是：若地图中一个或多个相邻接的相同海拔的元素所邻接的所有元素都比这些元素高度要小（或它邻接的是地图的边界），则该元素和其周围所有按照这样顺序排列的元素的集合称为一个小山丘。这里邻接的意义是：若一个元素与另一个横坐标纵坐标和它的横纵坐标相差不超过1，则称这两个元素邻接。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：两个由空格隔开的整数N和M * 第二行到第N+1行：第I+1行描述了地图上的第I行，有M个由空格隔开的整数：H_ij. </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;第一行：小山丘的个数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8 7<br>4 3 2 2 1 0 1<br>3 3 3 2 1 0 1<br>2 2 2 2 1 0 0<br>2 1 1 1 1 0 0<br>1 1 0 0 0 1 0<br>0 0 0 1 1 1 0<br>0 1 2 2 1 1 0<br>0 1 1 1 2 1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输出样例解释：地图上有三个小山丘：每个小山丘的山峰位置分别在左上角（高度为4），右上角（高度为1）和底部（高度为2）。</p>
</div>
</div>