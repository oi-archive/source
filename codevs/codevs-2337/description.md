<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span> 我们称一个长度为2n的数列是有趣的，当且仅当该数列满足以下三个条件：</span></p>
<p><span> </span><span> </span><span> </span><span> (1)它是从1到2n共2n个整数的一个排列{a<sub>i</sub>}；</span></p>
<p><span> </span><span> </span><span> </span><span> (2)所有的奇数项满足a<sub>1</sub>&lt;a<sub>3</sub>&lt;…&lt;a<sub>2n-1</sub>，所有的偶数项满足a<sub>2</sub>&lt;a<sub>4</sub>&lt;…&lt;a<sub>2n</sub>；</span></p>
<p><span> </span><span> </span><span> </span><span> (3)任意相邻的两项a<sub>2i-1</sub>与a<sub>2i</sub>(1≤i≤n)满足奇数项小于偶数项，即：a<sub>2i-1</sub>&lt;a<sub>2i</sub>。</span></p>
<p><span> </span><span> </span><span> </span><span> 现在的任务是：对于给定的n，请求出有多少个不同的长度为2n的有趣的数列。因为最后的答案可能很大，所以只要求输出答案 mod P的值。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>输入文件只包含用空格隔开的两个整数n和P。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅含一个整数，表示不同的长度为2n的有趣的数列个数mod P的值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span> 3 10 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span> 5</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>输入数据保证，50%的数据满足n≤1000，100%的数据满足n≤1000000且P≤1000000000。</p>
</div>
</div>