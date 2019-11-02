<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>若某个家族人员过于庞大，要判断两个是否是亲戚，确实还很不容易，现在给出某个亲戚关系图，求任意给出的两个人是否具有亲戚关系。 规定：x和y是亲戚，y和z是亲戚，那么x和z也是亲戚。如果x,y是亲戚，那么x的亲戚都是y的亲戚，y的亲戚也都是x的亲戚。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：三个整数n,m,p，（n&lt;=5000,m&lt;=5000,p&lt;=5000），分别表示有n个人，m个亲戚关系，询问p对亲戚关系。 以下m行：每行两个数Mi，Mj，1&lt;=Mi，Mj&lt;=N，表示Ai和Bi具有亲戚关系。 接下来p行：每行两个数Pi，Pj，询问Pi和Pj是否具有亲戚关系。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>P行，每行一个&rsquo;Yes&rsquo;或&rsquo;No&rsquo;。表示第i个询问的答案为&ldquo;具有&rdquo;或&ldquo;不具有&rdquo;亲戚关系。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 5 3</p>
<p>1 2</p>
<p>1 5</p>
<p>3 4</p>
<p>5 2</p>
<p>1 3</p>
<p>1 4</p>
<p>2 3</p>
<p>5 6</p>

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
<p>n&lt;=5000,m&lt;=5000,p&lt;=5000</p>
</div>
</div>