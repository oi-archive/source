<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>已知n个点(n&lt;=100)，给你n*n的方阵，a[i,j]表示从第i个点到第j个点的直接距离。        </p>
<p>现在有Q个询问，每个询问两个正整数，a和b，让你求a到b之间的最短路程。        </p>
<p>满足a[i,j]=a[j,i];</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p> 第一行一个正整数n，接下来n行每行n个正整数，满足a[i,i]=0,再一行一个Q，接下来Q行，每行两个正整数a和b。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一共Q行，每行一个整数。</p>

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
<p> 0 1 1</p>
<p>1 0 3</p>
<p>1 3 0</p>
<p>1</p>
<p>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=100，Q可能非常大。g[i][j]均&gt;=0</p>
<p>请使用flyod算法</p>
<p><strong>使用C/C++的同学请注意：由于输入数据较大，使用cin和cout会导致程序超时。请使用scanf与printf进行输入和输出。</strong></p>
</div>
</div>