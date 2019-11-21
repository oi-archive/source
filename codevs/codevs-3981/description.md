<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>题目还是简单一点好... </p><p>有n个数，a[1]到a[n]。</p><p>接下来q次查询，每次动态指定两个数l,r，求a[l]到a[r]的最大子段和。</p><p>子段的意思是连续非空区间。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个数n。</p><p>第二行n个数a[1]~a[n]。</p><p>第三行一个数q。</p><p>以下q行每行两个数l和r。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>q行，每行一个数，表示a[l]到a[r]的最大子段和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7<br>2 3 -233 233 -23 -2 233<br>4<br>1 7<br>5 6<br>2 5<br>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>441<br>-2<br>233<br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于50%的数据，q*n&lt;=10000000。</p><p>对于100%的数据，1&lt;=n&lt;=200000，1&lt;=q&lt;=200000。</p><p>a[1]~a[n]在int范围内，但是答案可能超出int范围。</p><p>数据保证1&lt;=l&lt;=r&lt;=n。</p><p>空间128M，时间1s。</p><p><span style="text-decoration: line-through;">我不会告诉你数据里有样例</span></p>
</div>
</div>