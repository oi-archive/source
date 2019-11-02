<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    有一个立方体被分成n*n*n的单位，坐标用(X,Y,Z)表示（1&lt;=X,Y,Z&lt;=n）。每个单位立方体内有一个绝对值不超过10<sup>9</sup>的整数。统计有多少个子立方体的所有数之和是m的倍数。子立方体即满足x<sub>1</sub>&lt;=X&lt;=x<sub>2</sub>, y<sub>1</sub>&lt;=Y&lt;=y<sub>2</sub>, z<sub>1</sub>&lt;=Z&lt;=z<sub>2</sub>的所有单位立方体集合，其中1&lt;=x<sub>1</sub>,x<sub>2</sub>,y<sub>1</sub>,y<sub>2</sub>,z<sub>1</sub>,z<sub>2</sub>&lt;=n。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个整数n, m，表示立方体的边长和作除数的正整数。以下n*n行，每行有n个整数。首先是X=1, Y=1的n个单位立方体，然后是X=1, Y=2的n个, …最后是X=n, Y=n-1的n个和X=n和Y=n的n个，共n<sup>3</sup>个整数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一个数，即所有整数和为m的倍数的子立方体的个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 5</p>
<p>1 2</p>
<p>3 4</p>
<p>5 6</p>
<p>7 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
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
<p>30%的数据满足1&lt;=n&lt;=10</p>
<p>100%的数据满足1&lt;=n&lt;= 40</p>
<p>对于所有的数据满足 1&lt;=m&lt;=1000000</p>
</div>
</div>