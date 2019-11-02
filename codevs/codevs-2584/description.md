<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出一个N个顶点、M条边的无向图，边(u,v)有权值w(u,v)，顶点i也有权值p(i)，<br>并且对于每条边(u,v)都满足p(u)+p(v)&gt;=w(u,v)。<br>现在要将顶点i的权值减去z(i)，其中0&lt;=z(i)&lt;=p(i)。<br>修改后设顶点i的权值p'(i)=p(i)-z(i)，对于每条边(u,v)都满足p'(u)+p'(v)=w(u,v)。<br>求sum{z(i)}的最小值和最大值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个正整数n,m (n&lt;=500,000, m&lt;=3,000,000)。<br>第二行n个整数，依次表示p(1),p(2),...,p(n) (0&lt;=p(i)&lt;=10^6)。<br>下面m行，每行三个整数u,v,w (1&lt;=u,v&lt;=n, 0&lt;=w&lt;=10^6)，表示存在一条权值为w的边(u,v)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>两个整数，分别表示sum{z(i)}的最小值和最大值，如果不存在方案就输出NIE。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Sample Input 1<br>3 2<br>5 10 5<br>1 2 5<br>2 3 3</p>
<p> </p>
<p>Sample Input 2<br>3 3<br>1 1 1<br>1 2 1<br>1 3 1<br>3 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Sample Output 1<br>12 15</p>
<p>Sample Output 2<br>NIE</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>有样例存在于测试数据中</p>
</div>
</div>