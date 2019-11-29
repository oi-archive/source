<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个由自然数组成的数列按下式定义：</p>
<p>对于i &lt;= k：ai = bi</p>
<p>对于i &gt; k: ai = c1ai-1 + c2ai-2 + ... + ckai-k</p>
<p>其中bj 和 cj （1&lt;=j&lt;=k）是给定的自然数。写一个程序，给定自然数m &lt;= n, 计算am + am+1 + am+2 + ... + an, 并输出它除以给定自然数p的余数的值。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个自然数k。</p>
<p>第二行包含k个自然数b1, b2,...,bk。</p>
<p>第三行包含k个自然数c1, c2,...,ck。</p>
<p>第四行包含三个自然数m, n, p。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅包含一行：一个正整数，表示(<em>a<sub>m</sub></em> + <em>a<sub>m+1</sub></em> + <em>a<sub>m+2</sub></em> + ... + <em>a<sub>n</sub></em>) mod <em>p</em>的值。</p>

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
<p>1 1</p>
<p>1 1</p>
<p>2 10 1000003</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>142</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的测试数据： 1&lt;= k &lt;=15     1 &lt;= m &lt;= n &lt;= 10<sup>18</sup></p>
<p>对于20%的测试数据：  1&lt;= k &lt;=15     1 &lt;= m &lt;= n &lt;= 10<sup>6</sup></p>
<p>对于30%的测试数据：  k=1            1 &lt;= m &lt;= n &lt;= 10<sup>18</sup></p>
<p>对于所有测试数据： 0&lt;= b1, b2,... bk, c1, c2,..., ck&lt;=10<sup>9</sup>     1 &lt;= p &lt;= 10<sup>8</sup></p>
</div>
</div>