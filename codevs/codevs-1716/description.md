<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    将一个a*b的数字矩阵进行如下分割：将原矩阵沿某一条直线分割成两个矩阵，再将生成的两个矩阵继续如此分割（当然也可以只分割其中的一个），这样分割了（n-1)次后，原矩阵被分割成了n个矩阵。（每次分割都只能沿着数字间的缝隙进行）</p>
<p>    原矩阵中每一位置上有一个分值，一个矩阵的总分为其所含各位置上分值之和。现在需要把矩阵按上述规则分割成n个矩阵，并使各矩阵总分的均方差最小。</p>
<p>请编程对给出的矩阵及n，求出均方差的最小值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行为3个整数，表示a,b,n(1&lt;a,b&lt;=10,1&lt;n&lt;=10）的值。</p>
<p>    第二行至第n+1行每行为b个小于100的非负整数，表示矩阵中相应位置上的分值。每行相邻两数之间用一个空格分开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp; &nbsp; 仅一个数，为均方差的最小值（四舍五入精确到小数点后2位）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 4 4</p>
<p>2 3 4 6</p>
<p>5 7 5 1</p>
<p>10 4 0 5</p>
<p>2 0 2 3</p>
<p>4 1 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.50</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>