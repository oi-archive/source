<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>二维平面中，给定N个等腰直角三角形（每个三角形的两条直角边分别平行于坐标轴，斜边从左上到右下）。我们用三个非负整数(x, y, d)来描述这样一个三角形，三角形三个顶点的坐标分别为(x, y), (x + d, y)和(x, y + d)。要求计算这N个三角形所覆盖的总面积。例如，下图有3个三角形，覆盖的总面积为11.0。  </p>
<p><img height="376" src="/source/codevs/codevs-2242/img/aHR0cDovL3AxMy5mcmVlcC5jbi9wLmFzcHg_dT12MjBfcDEzX3Bob3RvXzEzMDUwMTEwMzcxNDczNzBfMC5qcGc=.jpg" width="419"></p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行为一个正整数</span><em><span>N</span></em><span>，表示三角形的个数。接下来的</span><em><span>N</span></em><span>行每行有用空格隔开的三个非负整数，</span><em><span>x</span></em><span>, <em>y</em>, <em>d</em></span><span>，描述一个三角形的顶点坐标，分别为</span><span>(<em>x</em>, <em>y</em>), (<em>x</em> + <em>d</em>, <em>y</em>), (<em>x</em>, <em>y</em>+<em>d</em>)</span><span>，其中</span><em><span>x</span></em><span>, <em>y</em>, <em>d</em> </span><span>满足</span><span>0</span><span>≤</span><em><span>x</span></em><span>, <em>y</em>, <em>d</em></span><span>≤</span><span>1000000</span><span>。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>仅包含一行，为一个实数</span><em><span lang="EN-US">S</span></em><span>，表示所有三角形所覆盖的总面积，输出恰好保留一位小数。输入数据保证</span><em><span lang="EN-US">S</span></em><span lang="EN-US">&le;</span><span lang="EN-US">2<sup>31</sup></span><span>。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>1 1 4<br>2 0 2<br>3 2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11.0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span>50%</span>的数据，<span>1</span><span>≤</span><em><span>N</span></em><span>≤</span><span>500</span>；</p>
<p><span style="">    100%</span><span style="">的数据，</span><span style="">1</span><span style="">≤</span><em style=""><span>N</span></em><span style="">≤</span><span style="">10000</span><span style="">。</span></p>
</div>
</div>