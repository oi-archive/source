<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>CS有n个小区，并且任意小区之间都有两条单向道路（a到b，b到a）相连。因为最近下了很多暴雨，很多道路都被淹了，不同的道路泥泞程度不同。小A经过对近期天气和地形的科学分析，绘出了每条道路能顺利通过的时间以及这条路的长度。</span></p>
<p><span>现在小A在小区1，他希望能够很顺利地到达目的地小区n，请帮助小明找出一条从小区1出发到达小区n的所有路线中（总路程/总时间）最大的路线。请你告诉他这个值。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行包含一个整数n，为小区数。</span></p>
<p><span>接下来n*n的矩阵P，其中第i行第j个数表示从小区i到小区j的道路长度为Pi,j。第i行第i个数的元素为0，其余保证为正整数。</span></p>
<p><span>接下来n*n的矩阵T，第i行第j个数表示从小区i到小区j需要的时间Ti,j。第i行第i个数的元素为0，其余保证为正整数。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>写入一个实数S，为小区1到达n的最大答案，S精确到小数点后3位。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>3</span></p>
<p><span>0 8 7 </span></p>
<p><span>9 0 10 </span></p>
<p><span>5 7 0 </span></p>
<p><span>0 7 6 </span></p>
<p><span>6 0 6 </span></p>
<p><span>6 2 0</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>2.125</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>【数据说明】</span></p>
<p><span>30%的数据，n&lt;=20</span></p>
<p><span>100%的数据，n&lt;=100，p,t&lt;=10000</span></p>
</div>
</div>