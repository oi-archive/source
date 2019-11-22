<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>设有N*N的方格图(N&lt;=10,我们将其中的某些方格中填入正整数,而其他的方格中则放入数字0。如下图所示（见样例）：</p>
<p> </p>
<p>某人从图的左上角的A 点出发，可以向下行走，也可以向右走，直到到达右下角的B点。在走过的路上，他可以取走方格中的数（取走后的方格中将变为数字0）。</p>
<p>此人从A点到B 点共走两次，试找出2条这样的路径，使得取得的数之和为最大。</p>
<p> </p>

<img src="/source/codevs/codevs-1043/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMDQzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMDQzLnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行为一个整数N（表示N*N的方格图），接下来的每行有三个整数，前两个表示位置，第三个数为该位置上所放的数。一行单独的0表示输入结束。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp;&nbsp;只需输出一个整数，表示2条路径上取得的最大的和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>      8</p>
<p>      2  3  13</p>
<p>      2  6   6</p>
<p>      3  5   7</p>
<p>      4  4  14</p>
<p>      5  2  21</p>
<p>      5  6   4</p>
<p>      6 3  15</p>
<p>      7 2  14</p>
<p>      0 0  0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>      67</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
如描述
</div>
</div>