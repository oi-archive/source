<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个等差数列是一个能表示成a, a+b, a+2b,..., a+nb (n=0,1,2,3,...)的数列。</p>
<p>在这个问题中a是一个非负的整数，b是正整数。写一个程序来找出在双平方数集合(双平方数集合是所有能表示成p的平方 + q的平方的数的集合,其中p和q为非负整数)S中长度为n的等差数列。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行: N(3&lt;= N&lt;=25),要找的等差数列的长度。</p>
<p>第二行: M(1&lt;= M&lt;=250),搜索双平方数的上界0 &lt;= p,q &lt;= M。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果没有找到数列,输出`NONE'。</p>
<p>如果找到了，输出一行或多行, 每行由二个整数组成:a,b。</p>
<p>这些行应该先按b排序再按a排序。</p>
<p>所求的等差数列将不会多于10,000个。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>5
7</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>1 4
37 4
2 8
29 8
1 12
5 12
13 12
17 12
5 20
2 24</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>