<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>维护一个序列，要求支持下列2种操作：</p><p>add a b c:区间[a,b]中每个数加上c</p><p>count a b:查询区间[a,b]中有多少数是k的倍数（k为给定常数）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行三个数n,m,k,分别表示序列长度、操作数和count中的k<br></p><p>接下来一行n个整数，表示原始序列</p><p>接下来m行，每行是题面中的操作之一</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个count操作，输出一行答案</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10 10 5</p><p>5 5 8 3 5 6 7 8 3 0</p><p>add 2 7 1</p><p>count 3 4</p><p>add 2 5 4</p><p>count 1 5</p><p>count 2 6</p><p>count 1 3</p><p>add 4 8 3</p><p>count 3 7</p><p>add 4 8 2</p><p>count 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p><p>3</p><p>2</p><p>2</p><p>1</p><p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>10%:n,m&lt;=10,k&lt;=10000;</p><p>另外的20%:n,m&lt;=100000,k&lt;=10;</p><p>另外的20%:n,m&lt;=50000,k&lt;=100;</p><p>100%:n,m&lt;=200000,k&lt;=200000.</p>
</div>
</div>