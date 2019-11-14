<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出N个数，要求做M次区间翻转（如1 2 3 4变成4 3 2 1），求出最后的序列</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数N，下一行N个数表示原始序列，在下一行一个数M表示M次翻转，之后的M行每行两个数L，R表示将区间[L,R]翻转。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行N个数 ， 表示最终序列。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>1 2 3 4</p>
<p>2</p>
<p>1 2</p>
<p>3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 1 4 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据满足n&lt;=100 , m &lt;= 10000</p>
<p>对于100%的数据满足n &lt;= 150000 , m &lt;= 150000</p>
<p>对于100%的数据满足n为2的幂，且L = i * 2^j + 1 , R = (i + 1) * 2^j</p>
</div>
</div>