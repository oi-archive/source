<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>平面上，一个圆，圆的边上按顺时针放着n个点。现在要连m条边，比如a，b，那<br>么a到b可以从圆的内部连接，也可以从圆的外部连接。问能不能连接这m条边，使<br>这些边都不相交。（比如两条边分别是1 -2，2 - 3，则可以连接。若有三条边分<br>别时1 -5，2 - 6，3 - 7则一定会出现相交）。<br>输入数据会有多组：防止骗分</p>
<p>对于每一组输入数据，如果可以存在的话，则输出true，如果不能存在的话，则输<br>出false</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数q，表示数据的组数。<br>对于每组数据，第一行为两个数n和m，n指点的个数，m指要连的边的个数。<br>2到m + 1行,每行两个数字a，b表示要连的边的两个端点。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>若可以，则输出true，否则，输出false。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1<br>4 2<br>0 1<br>3 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>true</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%数据，q ≤ 30, n ≤ 1000, m ≤ 1000</p>
</div>
</div>