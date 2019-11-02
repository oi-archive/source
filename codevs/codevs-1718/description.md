<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    为了增添公园的景致，现在需要在公园中修筑一个花坛，同时在画坛四周修建一片绿化带，让花坛被绿化带围起来。</p>
<p>    如果把公园看成一个M*N的矩形，那么花坛可以看成一个C*D的矩形，绿化带和花坛一起可以看成一个A*B的矩形。</p>
<p>    如果将花园中的每一块土地的“肥沃度”定义为该块土地上每一个小块肥沃度之和，那么，</p>
<p>    绿化带的肥沃度=A*B块的肥沃度-C*D块的肥沃度</p>
<p>    为了使得绿化带的生长得旺盛，我们希望绿化带的肥沃度最大。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行有6个正整数M,N,A,B,C,D</p>
<p>    接下来一个M*N的数字矩阵，其中矩阵的第i行j列元素为一个整数Xij,表示该花园的第i行第j列的土地“肥沃度”。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp; &nbsp; 一个正整数，表示绿化带的最大肥沃程度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5 4 4 2 2</p>
<p>20 19 18 17 16</p>
<p>15 14 13 12 11</p>
<p>10 9 8 7 6</p>
<p>5 4 3 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>132</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据，1&lt;=M,N&lt;=50</p>
<p>100%的数据，1&lt;=M,N&lt;=1000,1&lt;=A&lt;=M,1&lt;=B&lt;=N,1&lt;=C&lt;=A-2,1&lt;=D&lt;=B-2，1&lt;=“肥沃度”&lt;=100</p>
</div>
</div>