<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>双十字 运行时限：10s 内存:256MB 在C 部落，双十字是非常重要的一个部落标志。所谓双十字，如下面两个例子，由两条水 平的和一条竖直的“1”线段组成，要求满足以下几个限制：  两条水平的线段不能在相邻的两行。  竖直线段上端必须严格高于两条水平线段，下端必须严格低于两条水平线段。  竖直线段必须将两条水平线段严格划分成相等的两半。  上方的水平线段必须严格短于下方的水平线段。 所以上面右边的例子是满足要求的最小的双十字。 现在给定一个R×C 的01 矩阵，要求计算出这个01 矩阵中有多少个双十字。 例如下面这个例子，R=6,C=8，01 矩阵如下： 我们可以找到5 个满足条件的双十字，分别如下： 注意最终的结果可能很大，只要求输出双十字的个数mod 1,000,000,009 的值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行为用空格隔开的两个正整数R和C，分别表示 01矩阵的行数和列数。输入文件第二行是一个非负整数N,表示01矩阵中“0”的个数。接下来的 N行，每行为用空格隔开的两个正整数x和y(1≤x≤R,1≤y≤C)，表示(x,y)是一个“0”。数据 保证N个“0”的坐标两两不同。数据保证R,C,N≤10,000,R*C≤1,000,000.对于30%的数据 R,C≤50.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件仅包含一行，为D mod 1,000,000,009 的结果，其中D 为要求的01 矩阵中双十字的个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 8</p>
<p>12</p>
<p>1 2</p>
<p>1 3</p>
<p>1 4</p>
<p>1 6</p>
<p>2 2</p>
<p>3 2</p>
<p>3 3</p>
<p>3 4</p>
<p>3 7</p>
<p>6 4</p>
<p>6 6</p>
<p>4 8</p>

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
<p>无</p>
</div>
</div>