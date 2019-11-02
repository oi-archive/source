<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> 一个公司有三个移动服务员。如果某个地方有一个请求，某个员工必须赶到那个地方去（那个地方没有其他员工），某一时刻只有一个员工能移动。被请求后，他才能移动，不允许在同样的位置出现两个员工。从p到q移动一个员工，需要花费c(p,q)。这个函数没有必要对称，但是c(p,p)=0。公司必须满足所有的请求。目标是最小化公司花费。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> 第一行有两个整数L,N(3&lt;=L&lt;=200, 1&lt;=N&lt;=1000)。L是位置数；N是请求数。每个位置从1到L编号。下L行每行包含L个非负整数。第i+1行的第j个数表示c(i,j) ，并且它小于2000。最后一行包含N个数，是请求列表。一开始三个服务员分别在位置1，2，3。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数M，表示最小服务花费。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 9<br>0 1 1 1 1<br>1 0 2 3 2<br>1 1 0 4 1<br>2 1 5 0 1<br>4 2 3 4 0<br>4 2 4 1 5 4 3 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>各个测试点1s</p>
</div>
</div>