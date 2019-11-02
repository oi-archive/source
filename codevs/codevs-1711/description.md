<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> 将一个８×８的棋盘进行如下分割：将原棋盘割下一块矩形棋盘并使剩下部 分也是矩形，再将剩下的部分继续如此分割，这样割了(n-1)次后，连同最后剩 下的矩形棋盘共有 n 块矩形棋盘。(每次切割都只能沿着棋盘格子的边进行) </p>
<p>原棋盘上每一格有一个分值，一块矩形棋盘的总分为其所含各格分值之和。现在需要把棋盘按上述规则分割成n块矩形棋盘，并使各矩形棋盘总分的均方差最小。 <br>请编程对给出的棋盘及 n，求出方差的最小值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行为一个整数 n(1&lt;n&lt;15)。 <br>第 2 行至第 9 行每行为 8 个小于 100 的非负整数，表示棋盘上相应格子的分 值。每行相邻两数之间用一个空格分隔。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一个数，为方差（四舍五入精确到小数点后三位）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 1 1 1 1 1 1 3</p>
<p>1 1 1 1 1 1 1 1</p>
<p>1 1 1 1 1 1 1 1</p>
<p>1 1 1 1 1 1 1 1</p>
<p>1 1 1 1 1 1 1 1</p>
<p>1 1 1 1 1 1 1 1</p>
<p>1 1 1 1 1 1 1 0</p>
<p>1 1 1 1 1 1 0 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1.633</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<pre>若x1,x2,x3......xn的平均数为m<br>则方差s^2=1/n[(x1-m)^2+(x2-m)^2+.......+(xn-m)^2] <br>方差即偏离平方的均值，称为标准差或均方差，方差描述波动程度。</pre>
</div>
</div>