<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一个M行N列的01矩阵，以及Q个A行B列的01矩阵，你需要求出这Q个矩阵哪些在<br>原矩阵中出现过。 <br> 所谓01矩阵，就是矩阵中所有元素不是0就是1。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行为M、N、A、B，参见题目描述。 <br>接下来M行，每行N个字符，非0即1，描述原矩阵。 <br>接下来一行为你要处理的询问数Q。 <br>接下来Q个矩阵，一共Q*A行，每行B个字符，描述Q个01矩阵。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>你需要输出Q行，每行为0或者1，表示这个矩阵是否出现过，0表示没有出现过，1表<br />示出现过。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 2 2 <br>111 <br>000 <br>111 <br>3 <br>11 <br>00 <br>11 <br>11 <br>00 <br>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 <br>0 <br>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的实际测试数据，M、N ≤ 1000，Q = 10 </p>
</div>
</div>