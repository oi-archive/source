<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在研究过Nim游戏及各种变种之后，Orez又发现了一种全新的取石子游戏，这个游戏是这样的：</p>
<p>有n堆石子，将这n堆石子摆成一排。游戏由两个人进行，两人轮流操作，每次操作者都可以从最左或最右的一堆中取出若干颗石子，可以将那一堆全部取掉，但不能不取，不能操作的人就输了。</p>
<p>Orez问：对于任意给出一个初始一个局面，是否存在先手必胜策略。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件的第一行为一个整数T，表示有 T组测试数据。对于每组测试数据，第一行为一个整数n，表示有n堆石子；第二行为n个整数a<sub>i</sub>，依次表示每堆石子的数目。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组测试数据仅输出一个整数0或1。其中1表示有先手必胜策略，0表示没有。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>4</p>
<p>3 1 9 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据  n≤5  a<sub>i</sub>≤10<sup>5</sup></p>
<p>对于100%的数据  T≤10 n≤1000 每堆的石子数目≤10<sup>9</sup></p>
</div>
</div>