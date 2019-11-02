<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>**请留意本题数据范围**本题卡常数**</p><p>有1024个数，初始值为1，有N次操作，每次操作给定a,b,c，当a=1时，意为将第b(1&lt;=b&lt;=1024)个数乘以c(0&lt;=c&lt;=45,000)，当a=2时，意为询问第b个数到第c(1&lt;=b&lt;=c&lt;=1024)个数的和值。需要对45679取模。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为N。<br></p><p>接下来N行每行a,b,c。</p><p>数据皆为整数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每次a=2，输出相应的区间和值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p><p>2 1 10</p><p>1 100 45678</p><p>1 500 999</p><p>1 1024 0</p><p>2 1 1024</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p><p>2019</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N&lt;=1,000,000。</p>
</div>
</div>