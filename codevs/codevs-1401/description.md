<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       我们说（i，j）是a1，a2，…，an的一个逆序对当且仅当i&lt;j且ai&gt;aj。例如2,4,1,3,5的逆序对有3个，分别为（1,3），（2,3），（2,4）。现在已知N和K，求1..N的所有特定排列，这些排列的逆序对的数量恰好为K。输出这些特定排列的数量。</p>
<p>       例如N=5，K=3的时候，满足条件的排列有15个，它们是：</p>
<p>1,2,5,4,3   1,3,4,5,2    1,3,5,2,4     1,4,2,5,3   1,4,3,2,5</p>
<p>1,5,2,3,4   2,1,4,5,3    2,1,5,3,4     2,3,1,5,4   2,3,4,1,5</p>
<p>2,4,1,3,5   3,1,2,5,4    3,1,4,2,5     3,2,1,4,5   4,1,2,3,5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行有两个整数N和K。其中（N&lt;=100,K&lt;=N*(N-1)/2）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>将1..N的逆序对数量为K的特定排列的数量输出，为了避免高精度计算，请将结果mod10000后再输出</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】</p>
<p>5 3</p>
<p> </p>
<p>【样例输入2】</p>
<p>10 7</p>
<p> </p>
<p>【样例输入3】</p>
<p>10 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】</p>
<p>15</p>
<p> </p>
<p>【样例输出2】</p>
<p>4489</p>
<p> </p>
<p>【样例输出3】</p>
<p>1670</p>
<p> </p>
<p> </p>
<p> </p>

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