<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某乡有n个村庄<strong>(1&lt;n&lt;＝15)</strong>，有一个售货员，他要到各个村庄去售货，各村庄之间的路程s(0&lt;s&lt;1000)是已知的，且A村到B村与B村到A村的路大多不同。为了提高效率，他从商店出发到每个村庄一次，然后返回商店所在的村，假设商店所在的村庄为1，他不知道选择什么样的路线才能使所走的路程最短。请你帮他选择一条最短的路。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>村庄数n和各村之间的路程(均是整数)</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">最短的路程</p>

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
<p>0 2 1</p>
<p>1 0 2</p>
<p>2 1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>本题可用最短路思想、搜索来解决，但是可能无法通过一组极限数据（且效率较低）。建议按树状DP考虑！</p>
</div>
</div>