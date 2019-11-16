<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>克里特岛以野人群居而著称。岛上有排列成环行的M个山洞。这些山洞顺<br>时针编号为1,2,…,M。岛上住着N个野人，一开始依次住在山洞C1,C2,…,CN中，<br>以后每年，第i个野人会沿顺时针向前走Pi个洞住下来。每个野人i有一个寿命<br>值Li，即生存的年数。下面四幅图描述了一个有6个山洞，住有三个野人的岛上<br>前四年的情况。三个野人初始的洞穴编号依次为1，2，3；每年要走过的洞穴数<br>依次为3，7，2；寿命值依次为4，3，1。</p>
<p>奇怪的是，虽然野人有很多，但没有任何两个野人在有生之年处在同一个山<br>洞中，使得小岛一直保持和平与宁静，这让科学家们很是惊奇。他们想知道，至<br>少有多少个山洞，才能维持岛上的和平呢？</p>

<img src="/source/codevs/codevs-1747/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzQ3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTc0Ny5ibXA=.bmp" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件savage.in的第1行为一个整数N(1&lt;=N&lt;=15)，即野人的数目。第2<br>行到第N+1每行为三个整数Ci, Pi, Li (1&lt;=Ci,Pi&lt;=100, 0&lt;=Li&lt;=106 )，表示每个野<br>人所住的初始洞穴编号，每年走过的洞穴数及寿命值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件savage.out 仅包含一个数M，即最少可能的山洞数。输入数据保证<br />有解，且M不大于106。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>1 3 4<br>2 7 3<br>3 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>该样例对应于题目描述中的例子。</p>
</div>
</div>