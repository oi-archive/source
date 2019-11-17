<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出n个正整数X1,X2,...Xn，可以进行不超过m次操作，每次操作选择一个非零的Xi，并将它减一。<br>最终要求存在某个k满足Xk=0，并且z=max{|Xi - Xi+1|}最小。<br>输出最小的z和此时最小的k。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个正整数n, m (1&lt;=n&lt;=1,000,000, 1&lt;=m&lt;=10^18)。第二行n个正整数X1,X2,...Xn (Xi&lt;=10^9)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出k和z。数据保证方案一定存在。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>16 15<br>8 7 6 5 5 5 5 5 6 6 7 8 9 7 5 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>将X序列变为<br>0 2 4 5 5 5 5 5 6 6 7 8 9 7 5 5<br>此时k=1，z=2，共操作了8+5+2=15次。</p>
</div>
</div>