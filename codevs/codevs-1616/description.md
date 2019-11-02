<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有n个位置和m个操作操作有两种，每次操作如果是 1 a b c 的形式，表 示往第a个位置到第b个位置<strong><span style="text-decoration: underline;">每个位置加入一个数c</span></strong>。如果操作形如 2a b c 的形 式，表示询问从第a个位置到第b个位置，第c大的数是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个数 n,m。意义如题目描述。<br>接下来m 行每行形如1 a b c 或者2 a b c 如题目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每个询问回答k大数是多少。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 5<br>1 1 2 1<br>1 1 2 2<br>2 1 1 2<br>2 1 1 1<br>2 1 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br>2<br>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>第一个操作后位置 1的数只有 1，位置2 的数也只有1。第二个操作后位置 1<br>的数有 1、2，位置2 的数也有1、2。第三次询问位置 1到位置 1第 2大的数是<br>1。第四次询问位置 1到位置 1 第1 大的数是2。第五次询问位置1 到位置2 第 3<br>大的数是 1。<br><br></p>
<p>30%的数据 n=m=1000<br>100%的数据n,m≤50000，并且后 7个点的数据 n，m 的范围从 32000到 50000<br>近似成等差数列递增。a≤b≤n,1操作中|c|≤n,2操作中|c|≤maxlongint</p>
<p> </p>
</div>
</div>