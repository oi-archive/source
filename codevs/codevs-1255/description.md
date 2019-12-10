<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>一种积木搭建方式，高为H的积木，最底层有M个积木，每一层的积木数是他的低一层的积木数<span style="font-family: 'Times New Roman';">+1</span><span style="">或</span><span style="font-family: 'Times New Roman';">-1</span><span style="">。总共有</span>N个积木。（且每行积木数不超过<span style="font-family: 'Times New Roman';">10</span><span style="">）</span></p>
<p> </p>
<p>比如下图N=13 H=6 M=2。</p>
<p><span style=""><br></span></p>

<img src="/source/codevs/codevs-1255/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzEyNTUuanBn.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为三个整数、N、<span style="font-family: 'Times New Roman';">H</span><span style="">、</span><span style="font-family: 'Times New Roman';">M</span><span style="">。</span></p>
<p>第二行以后每行一个整数K，<span style="font-family: 'Times New Roman';">-1</span><span style="">为结束符。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">第一行为满足N、H、M的积木搭建方案总数（1&lt;=N&lt;=540&nbsp;H&lt;=60&nbsp;M&lt;=10）</p>
<p class="p0">以后每一行对于对应的K，给出顺序排列的第K种方案（最小的排列为第一种）。</p>
<p class="p0">（如样例中，2 1 2 3 2 3是一种方案，代表一层的积木分别为212323，232321也是一种方案，212323比232321要小，每个状态之间是可比的，第一个数小的排前面，第一个数相等的就看第二个数。那么所有方案就有一个顺序了，这里的K就是求第K个按顺序排列的方案）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>13 6 2</p>
<p>1</p>
<p>3</p>
<p> -1</p>

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
<p>2 1 2 3 2 3</p>
<p>2 3 2 3 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>如描述</p>
</div>
</div>