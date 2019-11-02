<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> 　　设有N堆沙子排成一排，其编号为1，2，3，…，N（N&lt;=300）。每堆沙子有一定的数量，可以用一个整数来描述，现在要将这N堆沙子合并成为一堆，每次只能合并相邻的两堆，合并的代价为这两堆沙子的数量之和，合并后与这两堆沙子相邻的沙子将和新堆相邻，合并时由于选择的顺序不同，合并的总代价也不相同，如有4堆沙子分别为 1 3 5 2 我们可以先合并1、2堆，代价为4，得到4 5 2 又合并 1，2堆，代价为9，得到9 2 ，再合并得到11，总代价为4+9+11=24，如果第二步是先合并2，3堆，则代价为7，得到4 7，最后一次合并代价为11，总代价为4+7+11=22；问题是：找出一种合理的方法，使总的代价最小。输出最小代价。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数N表示沙子的堆数N。<br> 第二行N个数，表示每堆沙子的质量。 &lt;=1000</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>合并的最小代价</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4<br>1 3 5 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>22</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>各个测试点1s</p>
</div>
</div>