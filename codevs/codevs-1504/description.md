<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近老师教了狗狗怎么算组合数，狗狗又想到了一个问题。。。</p>
<p>狗狗定义C(N,K)表示从N个元素中不重复地选取K个元素的方案数。</p>
<p>狗狗想知道的是C(N,K)的奇偶性。</p>
<p>当然，这个整天都老是用竖式算123456789*987654321=？的人不会让你那么让自己那么轻松，它说：“N和K都可能相当大。”</p>
<p>但是狗狗也犯难了，所以它就找到了你，想请你帮他解决这个问题。</p>
<p> </p>
<p> </p>
<p><strong>数据范围(高精度)</strong></p>
<p>对于30% 的数据，n&lt;=10^2 t&lt;=10^4</p>
<p>对于50% 的数据，n&lt;=10^3 t&lt;=10^5</p>
<p>对于100%的数据，n&lt;=10^8 t&lt;=10^5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：一个正整数t，表示数据的组数。</p>
<p>第2~2+t-1行：两个非负整数N和K。（保证k&lt;=n）</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">每一组输入，如果C(N,K)是奇数则输出1，否则输出0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 1</p>
<p>1 0</p>
<p>2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>1</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>预备知识</p>
<p>C(n, 0) = C(n, n) = 1 (n &gt; 0;)<br>C(n, k) = C(n − 1, k − 1) + C(n − 1, k) (0 &lt; k &lt; n)</p>
<p>需要高精度优化</p>
</div>
</div>