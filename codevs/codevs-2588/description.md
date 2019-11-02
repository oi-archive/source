<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>设有n个互不相同的正整数{X1,X2,...Xn}，任取两个Xi,Xj(i≠j)，能算出Xi+Xj。<br>现在所有取法共n*(n-1)/2个和，要你求出X1,X2,...Xn。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正整数n (3&lt;=n&lt;=300)。<br>第二行n*(n-1)/2个正整数(每个正整数不超过10^8)，表示任取两个Xi,Xj(i≠j)算出的n*(n-1)/2个和。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行一个正整数k，表示方案数。测试数据保证至少存在一种方案。<br />下面k行每行给出递增的n个正整数。方案按照{Xi}的最小值从大到小输出。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Sample Input 1<br>4<br>3 5 4 7 6 5</p>
<p> </p>
<p>Sample Input 2<br>4<br>11 17 12 20 21 15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Sample Output 1<br>1<br>1 2 3 4</p>
<p>Sample Output 2<br>2<br>4 7 8 13<br>3 8 9 12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例存在于测试数据中</p>
</div>
</div>