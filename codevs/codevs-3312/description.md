<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>读入一个正整数<span style="font-family: 'Times New Roman';">n</span>，判断整数是完数，亏数还是盈数。</p>
<p>•如果它的约数的和等于它本身，那它便是一个完数<span style="font-family: 'Times New Roman';">(Perfect)</span>（约数包含<span style="font-family: 'Times New Roman';">1</span>，但不包含它本身）。</p>
<p>•如果它的约数的和小于它本身，那它便是一个亏数<span style="font-family: 'Times New Roman';">(Deficient)</span>（约数包含<span style="font-family: 'Times New Roman';">1</span>，但不包含它本身）。</p>
<p>•如果它的约数的和大于它本身，那它便是一个盈数<span style="font-family: 'Times New Roman';">(Abundant)</span>（约数包含<span style="font-family: 'Times New Roman';">1</span>，但不包含它本身）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件共两行，</p>
<p>第一行为一个正整数n，</p>
<p>第二行为n个正整数，中间用空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出为n行，分别为第1..n个数的类别。</p>
<p>完数：Perfect</p>
<p>亏数：Deficient</p>
<p>盈数：Abundant</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>4 6 12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4 is a deficient number.<br>6 is a perfect number.<br>12 is an abundant number.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=2^31-1</p>
</div>
</div>