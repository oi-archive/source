<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个国家有n个城市。若干个城市之间有电话线连接，现在要增加m条电话线（电话线当然是双向的了），使得任意两个城市之间都直接或间接经过其他城市有电话线连接，你的程序应该能够找出最小费用及其一种连接方案。</p>

<img src="/source/codevs/codevs-1003/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzEwMDMucG5n.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件的第一行是n的值（n&lt;=100）.</p>
<p>    第二行至第n+1行是一个n*n的矩阵，第i行第j列的数如果为0表示城市i与城市j有电话线连接，否则为这两个城市之间的连接费用（范围不超过10000）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;输出文件的第一行为你连接的电话线总数m，第二行至第m+1行为你连接的每条电话线，格式为i j，（i&lt;j）， i j是电话线连接的两个城市。输出请按照Prim算法发现每一条边的顺序输出，起始点为1.</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 第m+2行是连接这些电话线的总费用。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5</span></p>
<p>0 15 27 6 0</p>
<p>15 0 33 19 11</p>
<p>27 33 0 0 17</p>
<p>6 19 0 0 9</p>
<p>0 11 17 9 0</p>

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
<p>1 4</p>
<p>2 5</p>
<p>17</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=100</p>
</div>
</div>