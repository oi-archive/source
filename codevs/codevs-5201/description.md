<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>潍坊一中大道上有n个雕塑，依次排列。每个雕塑都有一个美观度Di。DYP是一个审美奇特的人，他要将这n个雕塑分成X（A&lt;=X&lt;=B）组，每组雕塑必须是连续的一片。比如有雕塑1,2,3,4,5,6，可以分成（1,2,3），（4,5），（6）。每一组的美观度是组内所有雕塑美观度的和。而整个大道的美观度是各组美观度的“或运算”的结果（两个数字的“或运算”你懂的）。</p><p>DYP现在想通过一定的分组方式，得到最小的总美观度。你能帮帮帅气的DYP吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行3个数字n，A,B,含义如题目所述。</p><p>第二行一共n个数，第i个数为Di，含义如题目所述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个数字，表示最大的总美观度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 1 3</p><p>8 1 2 1 5 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，1&lt;=n&lt;=10,A=1;</p><p>对于40%的数据，1&lt;=n&lt;=10;</p><p>对于70%的数据，1&lt;=n&lt;=100;</p><p>对于100%的数据，1&lt;=n&lt;=1000;</p><p>对于所有数据，都有1&lt;=A&lt;=B&lt;=n，Di&lt;=10^9;</p>
</div>
</div>