<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给定一个长度为n的序列a，回答m个询问，每个询问包含一个序列，回答这个序列是否是原序列的一个可不连续的子序列<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个正整数n，表示序列长度<br></p><p>第二行有n个正整数，每个正整数小于等于10<sup>6</sup>。</p><p>第三行包含一个正整数m</p><p>接下来2*m行每两行为一组询问</p><p>每组的第一行为序列长度l</p><p>第二行为l个正整数，每个正整数小于等于10<sup style="">6</sup>。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共m行，对于每组询问，如果是原序列的一个可不连续的子序列则输出“YES”，否则输出“NO”，均不含引号。<br/><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p><p>1 2 3 4 5</p><p>3</p><p>2</p><p>1 2</p><p>3</p><p>1 3 4</p><p>3</p><p>1 4 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>YES</p><p>YES</p><p>NO</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n,m&lt;=1000000,0&lt;ai&lt;=1000000</p>
</div>
</div>