<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>给出一个包含N个数且互不相同的数列，要求支持以下两种操作：</p>
<p>1）删除某个数；</p>
<p>2）查询某个数左边和右边的数。</p>
<p>共包含M个操作，请输出其中操作2）的结果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入第一行包含两个正整数N和M。</p>
<p>接下来一行包含N个数，为初始时的数列。</p>
<p>接下来M行，每行三个正整数op，x，op表示操作编号，x表示操作的数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">对于每个操作2），输出查询结果，如果这个数没有左边或右边的数，请用-1代替。</p>

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
<p>1 2 3</p>
<p>2 2</p>
<p>1 2</p>
<p>2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 3</p>
<p>-1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>2≤M,N≤100000</p>
<p>保证数列中编号互不相同且为1~N。</p>
</div>
</div>