<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>对于一个递归函数w(a, b, c)。</p>
<p><br>如果a &lt;= 0 or b &lt;= 0 or c &lt;= 0就返回值1。</p>
<p><br>如果a &gt; 20 or b &gt; 20 or c &gt; 20就返回W(20,20,20)。</p>
<p><br>如果a &lt; b并且b &lt; c 就返回w(a, b, c − 1) + w(a, b − 1, c − 1) − w(a, b − 1, c)，</p>
<p><br>其它别的情况就返回w(a − 1, b, c) + w(a − 1, b − 1, c) + w(a − 1, b, c − 1) − w(a −1, b - 1, c - 1)</p>
<p>这是个简单的递归函数，但实现起来可能会有些问题。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>会有若干行.每行三个数，表示a, b, c。并以−1, −1, −1结束</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出若干行，注意各种中的空格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 1 1<br>2 2 2<br>-1 -1 -1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>w(1, 1, 1) = 2<br>w(2, 2, 2) = 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>a, b, c &lt; 30, Task &lt; 11</p>
</div>
</div>