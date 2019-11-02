<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Tom写了一封信，为了防止被偷看，他设计了一个加密函数。 我们可以认为信是一个字符串 W，设 phi（W）为加密后的字符串：</p><p>1、 如果 W 的长度为 1，那么 phi(W)=W；</p><p>2、 设 W=w1w2…wN，令 K=N div 2（下取整）；</p><p>3、 phi(W) = phi(wNwN-1...wK+1) + phi(wKwK-1...w1)。 举个例子，phi(‘Ok’) = ‘kO’，phi(‘abcd’) = ‘cdab’。</p><p> </p><p>现在小 y 截获了Tom信，他想破译这封信。但是由于他太忙，现在他 交给你这个任务，询问原字符串的第 q 个字符在加密后的字符串中的位置。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入一行两个整数 N, q (1 &lt;= N &lt;= 10^9；1 &lt;= q &lt;= N)。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行一个整数，表示第 q 个字符加密后的位置。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>9 4<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据，N&lt;=1000</p><p>100%的数据，N&lt;=10^9<br></p>
</div>
</div>