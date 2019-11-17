<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定无向带权连通图G，我们希望通过修改边的权值，使它最小生成树唯一。已知减小、增加一条边的权值的单位代价分别为a和b，且修改后的权值必须为非负整数。<br>例如，对某个图G，如果将一条边的权值减3、另一条边的权值加2之后，它的最小生成树唯一，则此时的代价之和是3a+2b。试计算代价之和。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含数据编号，对于第 i 个数据，第一行将包含字<span style="">符串  "mst i"。 </span></p>
<p>第二行包含 4 个正整数 n,  m,  a,  b，分别表示图 G 顶点的个数、边的条数， <span style="">以及对一条边的权值减 1、加 1 的代价。 </span></p>
<p>接下来 m 行，每行 3 个正整数 x, y, w，表示顶点 x 和顶点 y 之间连有一条初<span style="">始权值为 w 的边。顶点由 1 至 n 编号。 </span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">仅包含一行，包含一个非负整数，即要求的最小值。如果<span style="font-size: 10px;">无需修改，即图本身的最小生成树就是唯一的，则输出&nbsp;0。&nbsp;</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>mst 0<br>4 5 2 3<br>1 2 1<br>1 3 1<br>2 3 1<br>2 4 2<br>3 4 2</p>

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
<p>n ≤ 500,000 ，m ≤ 1,000,000, a,b ≤ 10^9</p>
</div>
</div>