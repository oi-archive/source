<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>人们的恋爱关系与如下特点：两个人a，b，如果a爱着b，那么b一定不爱a；如果a不爱b，那么b一定爱着a（yh的研究成果果然与众不同……）。</p>
<p>现在，yh想知道，在n个人当中，是否存在三角恋现象（即a爱着b，b爱着c，c爱着a）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>本题有多组测试数据</p>
<p>第一行一个整数t，表示有t组测试数据。</p>
<p>对于每组数据，第一行为一个整数n，表示共有n人。</p>
<p>接下来为n*n的0,1矩阵a，如果a[i，j]=1,则i爱着j，否则表示i不爱j;数据保证a[i,j]&lt;&gt;a[j,i]。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">每组数据输出一行，如果存在三角恋，输出&rsquo;Yes&rsquo;，否则输出&rsquo;No&rsquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>5</p>
<p>00100</p>
<p>10000</p>
<p>01001</p>
<p>11101</p>
<p>11000</p>
<p>5</p>
<p>01111</p>
<p>00000</p>
<p>01000</p>
<p>01100</p>
<p>01110</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Yes</p>
<p>No</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于40%的数据，n≤10</p>
<p>对于100%的数据，n≤2000, t≤5</p>
</div>
</div>