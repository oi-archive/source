<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出一个N个顶点、M条边的无向图和一个不超过N的正整数K，要求去掉最少的边，使得编号为1~K的顶点都不在任何一个环中。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行三个整数N、M、K (1&lt;=N&lt;=1,000,000, 0&lt;=M&lt;=2,000,000, 1&lt;=K&lt;=N)。<br>下面M行，每行两个正整数a、b (1&lt;=a&lt;b&lt;=N)，表示无向图中的一条边(a,b)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行输出一个整数T，表示最少要去掉T条边，下面T行每行给出两个正整数a、b (1&lt;=a&lt;b&lt;=N)，表示去掉边(a,b)。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11 13 5<br>1 2<br>1 3<br>1 5<br>3 5<br>2 8<br>4 11<br>7 11<br>6 10<br>6 9<br>2 3<br>8 9<br>5 9<br>9 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br>2 3<br>5 9<br>3 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>第一个数据是样例</p>
</div>
</div>