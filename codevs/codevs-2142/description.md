<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一个关于n个元素的排列是指一个从{1, 2, …, n}到{1, 2, …, n}的一一映射的函数。这个排列p的秩是指最小的k，使得对于所有的i = 1, 2, …, n，都有p(p(…p(i)…)) = i（其中，p一共出现了k次）。</p>
<p>例如，对于一个三个元素的排列p(1) = 3, p(2) = 2, p(3) = 1，它的秩是2，因为p(p(1)) = 1, p(p(2)) = 2, p(p(3)) = 3。</p>
<p><strong>给定一个</strong><strong>n</strong><strong>，我们希望从</strong><strong>n!</strong><strong>个排列中，找出一个拥有最大秩的排列。例如，对于</strong><strong>n=5</strong><strong>，它能达到最大秩为</strong><strong>6</strong><strong>，这个排列是</strong><strong>p(1) = 4, p(2) = 5, p(3) = 2, p(4) = 1, p(5) = 3</strong><strong>。</strong><strong></strong></p>
<p><strong>当我们有多个排列能得到这个最大的秩的时候，我们希望你求出字典序最小的那个排列。对于</strong><strong>n</strong><strong>个元素的排列，排列</strong><strong>p</strong><strong>的字典序比排列</strong><strong>r</strong><strong>小的意思是：存在一个整数</strong><strong>i</strong><strong>，使得对于所有</strong><strong>j &lt; i</strong><strong>，都有</strong><strong>p(j) = r(j)</strong><strong>，同时</strong><strong>p(i) &lt; p(j)</strong><strong>。对于</strong><strong>5</strong><strong>来说，秩最大而且字典序最小的排列为：</strong><strong>p(1) = 2, p(2) = 1, p(3) = 4, p(4) = 5, p(5) = 3</strong><strong>。</strong><strong></strong></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行是一个整数T（T &lt;= 10），代表数据的个数。</p>
<p>每个数据只有一行，为一个整数N。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个N，输出秩最大且字典序最小的那个排列。即输出p(1), p(2),&hellip;,p(n)的值，用空格分隔。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>
<p>2</p>
<p>5</p>
<p>14</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>2 1 4 5 3</p>
<p>2 3 1 5 6 7 4 9 10 11 12 13 14 8</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>对于</strong><strong>40%</strong><strong>的数据，有</strong><strong>1</strong><strong>≤</strong><strong><em>N</em></strong><strong>≤</strong><strong>100</strong><strong>。</strong><strong></strong></p>
<p><strong>对于所有的数据，有</strong><strong>1</strong><strong>≤</strong><strong><em>N</em></strong><strong>≤</strong><strong>10000</strong><strong>。</strong><strong></strong></p>
</div>
</div>