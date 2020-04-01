<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定n个数 a<sub>1 </sub>, a<sub>2 </sub>, ... , a<sub>n</sub></p>
<p>定义 f<sub>i,j </sub>= a<sub>i </sub>+ a<sub>i+1 </sub>+ a<sub>i+2 </sub>+ ... + a<sub>j-1 </sub>+ a<sub>j  </sub>(1 ≤ i ≤ j ≤ n)</p>
<p>求 f<sub>i,j</sub> 的最大值</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有1个数，n</p>
<p>第二行有n个数，a<sub>1</sub> , a<sub>2</sub> , ... , a<sub>n</sub></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出只有一行，f<sub>i,j</sub>&nbsp;的最大值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>3 6 -8 9 -12 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例中当 i = 1 , j = 4 时，f<sub>i,j </sub>= a<sub>1 </sub>+ a<sub>2 </sub>+ a<sub>3 </sub>+ a<sub>4 </sub>= 3 + 6 - 8 + 9 = 10 为最大值</p>
<p> </p>
<p>数据规模：</p>
<p> </p>
<p>10%的数据   n = 7</p>
<p>30%的数据   n ≤ 1000</p>
<p>100%的数据 n ≤ 1000000 -1000 ≤ a<sub>i </sub>≤ 1000 (1 ≤ i ≤ n)</p>
<p> </p>
<p>Hint:</p>
<p>除了第1，2，20个点之外，数据完全随机</p>
<p>保证答案大于0且小于5000000</p>
</div>
</div>