<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个老式计算器，只能显示n位数字。有一天，你无聊了，于是输入一个整数k，然后反复平方，直到溢出。每次溢出时，计算器会显示出结果的最高n位和一个错误标记。然后清除错误标记，继续平方。如果一直这样做下去，能够得到的最大数是多少？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行是一个整数T(1&lt;=T&lt;=300)，即测试数据的数量。以下T行，每行包括两个整数n(1&lt;=n&lt;=9)和k(1&lt;=10^n)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每组数据，输出能够得到的最大数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p><p>1 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>当n=1,k=6的时候，计算器将会依次显示：6、3、9、8，6、3、9、8...</p>
</div>
</div>