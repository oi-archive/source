<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有n个正整数X1,X2,...,Xn，再给出m1+m2个限制条件，限制分为两类：<br>1. 给出a,b (1&lt;=a,b&lt;=n)，要求满足Xa + 1 = Xb<br>2. 给出c,d (1&lt;=c,d&lt;=n)，要求满足Xc &lt;= Xd<br>在满足所有限制的条件下，求集合{Xi}大小的最大值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行三个正整数n, m1, m2 (2&lt;=n&lt;=600, 1&lt;=m1+m2&lt;=100,000)。<br>接下来m1行每行两个正整数a,b (1&lt;=a,b&lt;=n)，表示第一类限制。<br>接下来m2行每行两个正整数c,d (1&lt;=c,d&lt;=n)，表示第二类限制。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个正整数，表示集合{Xi}大小的最大值。<br />如果无解输出NIE。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 2 2<br>1 2<br>3 4<br>1 4<br>3 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">X3=1, X1=X4=2, X2=3</span><br>这样答案为3。容易发现没有更大的方案。</p>
<p>第一个数据是样例。</p>
</div>
</div>