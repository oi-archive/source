<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>char哥要在n*n的网格内，每一个空的网格可以放一只鸽子，但是有m个网格不能放鸽子，每行每列都必须有且只有一只鸽子，任意两只鸽子交换位置算作同一种方案（即至少有一只鸽子位置不同，视为两种方案），char哥想考考你，问你有多少种方案<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行n、m，用空格隔开表示n*n的网格中有m个不能放的网格。<br></p><p>接下来m行，第i行给出第i个不能放鸽子的网格的坐标xi,yi。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数，即方案个数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1</p><p>6 7<br></p><p>1 1</p><p>2 1</p><p>2 2</p><p>3 3</p><p>3 4</p><p>4 3<br></p><p>4 4</p><p>样例2</p><p>3 3</p><p>1 1</p><p>1 2</p><p>1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1</p><p>184</p><p>样例2</p><p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据，n&lt;=20,m&lt;=10。数据保证答案小于2^63-1。</p>
</div>
</div>