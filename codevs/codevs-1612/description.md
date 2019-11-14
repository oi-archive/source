<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Sam和他的妹妹Sara 有一个包含n × m 个方格的<br>表格。她们想要将其的每个方格都染成红色或蓝色。<br>出于个人喜好，他们想要表格中每个2 × 2 的方形区<br>域都包含奇数个（1 个或3 个）红色方格。例如，右<br>图是一个合法的表格染色方案（在打印稿中，深色代<br>表蓝色，浅色代表红色）。<br>可是昨天晚上，有人已经给表格中的一些方格染上了颜色！现在Sam 和Sara<br>非常生气。不过，他们想要知道是否可能给剩下的方格染上颜色，使得整个表格<br>仍然满足她们的要求。如果可能的话，满足他们要求的染色方案数有多少呢？</p>

<img src="/source/codevs/codevs-1612/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNjEyL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTYxMi5qcGc=.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含三个整数n, m 和k，分别代表表格的行数、列数和已被染色的方块数<br>之后的k 行描述已被染色的方格。其中第i 行包含三个整数xi, yi 和ci，分别<br>代表第i 个已被染色的方格的行编号、列编号和颜色。ci 为1 表示方格被染成红<br>色，ci 为0 表示方格被染成蓝色。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，表示可能的染色方案数目W 模10<sup>9</sup> 得到的值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 4 3<br>2 2 1<br>1 2 0<br>2 3 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于所有的测试数据，2 ≤ n, m ≤ 10<sup>6</sup>，0 ≤ k ≤ 10<sup>6</sup>，1 ≤ xi ≤ n，1 ≤ yi ≤ m。</p>
</div>
</div>