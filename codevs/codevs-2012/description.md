<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给你K个序列（编号从0到K-1），并且第i个序列有N<sub>i</sub>个元素。然后将会有一个由(0~K-1)组成的字符串S=(s<sub>1</sub>,s<sub>2</sub>,...,s<sub>n</sub>)。如果s<sub>i</sub>=p，那么把第p个序列增加到这个大的序列上。</p>
<p>例如：</p>
<p>如果你有小的序列：</p>
<p>0.{1,2,3}</p>
<p>1.{-1,2,0}</p>
<p>2.{3,4,5,-6}</p>
<p>字符串S="1021",那么这个大的序列是{-1,2,0,1,2,3,3,4,5,-6,-1,2,0}</p>
<p>接下来，对于大的序列将会有M组询问如下：</p>
<p>Query(x, y) = Max{a[i] + a[i + 1] + ... + a[j] ; 1 &lt;= x &lt;= i &lt;= j &lt;= y &lt;= len(大序列的长度)}.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有两个整数K, M。</p>
<p>接下来K行，每行开始用一个整数N<sub>i</sub>，表示小的序列的个数，接下来N<sub>i</sub>个整数每个整数的绝对值范围不超过100,000 。</p>
<p>然后是有一个由(0~K-1)组成的字符串S。</p>
<p>接下来M行，每行两个整数x, y代表每组询问。(1 &lt;= x &lt;= y &lt;= len(大序列的长度))。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组询问输出答案。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>
<p>3 1 -2 3</p>
<p>3 5 6 -7</p>
<p>4 2 0 6 8</p>
<p>0120</p>
<p>1 3</p>
<p>4 6</p>
<p>4 13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 11 22</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>20%的数据中1&lt;=K&lt;=3,1&lt;=M&lt;=10,1&lt;=Ni&lt;=10,1&lt;=S&lt;=10;</p>
<p>40%的数据中1&lt;=K&lt;=10,1&lt;=M&lt;=1000,1&lt;=Ni&lt;=100,1&lt;=S&lt;=100;</p>
<p>60%的数据中1&lt;=K&lt;=10,1&lt;=M&lt;=10000,1&lt;=Ni&lt;=1000,1&lt;=S&lt;=1000;</p>
<p>100%的数据中1&lt;=K&lt;=10,1&lt;=M&lt;=100000,1&lt;=Ni&lt;=10000,1&lt;=S&lt;=100000;</p>
</div>
</div>