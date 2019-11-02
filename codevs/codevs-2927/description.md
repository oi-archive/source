<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    给出n个集合，每个集合中有若干个数。</p>
<p>    有m个询问，每次询问两个数a,b，判断a、b是否同时存在于某一个集合中。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行为n。</p>
<p>    接下来的n行，每行描述一个集合，每行的第一个数为该集合中数的个数k，接下来有k个数。数字可能有重复。</p>
<p>    第n+2行为m。</p>
<p>    接下来的m行，每行两个数a、b，表示一个询问。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp; &nbsp;&nbsp;对于每次询问，输出一行。若a、b同时存在于某一个集合中，输出Y，否则输出N。</p>

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
<p>2 1 2</p>
<p>3 2 3 4</p>
<p>3 2 5 7</p>
<p>2</p>
<p>1 3</p>
<p>2 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>N</p>
<p>Y</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div><span style="">n&lt;=1000,k&lt;=10000,m&lt;=2000000，集合中的数字小于10000,a、b&lt;=32767,不保证a!=b。不保证任意两个集合不同。集合中的数与询问的数均为非负整数。</span></div>
</div>
</div>