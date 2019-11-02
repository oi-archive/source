<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有N个不同的正整数数x1, x2, ... xN 排成一排，我们可以从左边或右边去掉连续的i个数（只能从两边删除数），1&lt;=i&lt;=n，剩下N-i个数，再把剩下的数按以上操作处理，直到所有的数都被删除为止。<br>每次操作都有一个操作价值，比如现在要删除从i位置到k位置上的所有的数。操作价值为|xi – xk|*(k-i+1)，如果只去掉一个数，操作价值为这个数的值。<br>任务<br>如何操作可以得到最大值，求操作的最大价值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件remove.in 的第一行为一个正整数N，第二行有N个用空格隔开的N个不同的正整数。<br>N个操作数为1..1000 之间的整数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件remove.out 包含一个正整数，为操作的最大值</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6<br>54 29 196 21 133 118</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>768</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>3&lt;=N&lt;=100</p>
</div>
</div>