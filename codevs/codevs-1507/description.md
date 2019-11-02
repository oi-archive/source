<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Abstinence（戒酒）岛的居民们酷爱一种无酒精啤酒。以前这种啤酒都是从波兰进口，但今年居民们想建一个自己的啤酒厂。岛上所有的城市都坐落在海边，并且由一条沿海岸线的环岛高速路连接。酒厂的投资者收集了关于啤酒需求量的信息，即每天各城市消费的啤酒桶数。另外还知道相邻城市之间的距离。每桶啤酒每英里的运费是<span style="font-family: 'Times New Roman';">1</span><span style="">元。日运费是将所需要的啤酒从酒厂运到所有城市所必需的运费之和。日运费的多少和酒厂的选址有关。投资者想找到一个合适的城市来修建酒厂，以使得日运费最小。</span></p>
<p>请设计一个程序：从文件<span style="font-family: 'Times New Roman';">bre.in</span> 读入城市的数目、相邻两城市间的距离以及每个城市消费的啤酒桶数，计算最小的日运费，将结果写到输出文件<span style="font-family: 'Times New Roman';">bre.out</span><span style="">中。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个整数n（5 &lt;= n &lt;= 10000） ，表示城市的数目。 城市沿高速路编号，使得相邻的城市的编号也相邻（城市1和n也被认为是相邻）。 以下的<span style="font-family: 'Times New Roman';">n</span><span style="">行，每行有两个非负整数。第</span>I+1<span style="">行的数</span> zi、di分别是城市I每日的啤酒消费量（桶）和从城市I沿高速路到下一个城市的距离（英里）。高速路的总长不会超过<span style="font-family: 'Times New Roman';">65535</span> 英里。每座城市的日消费量不会超过<span style="font-family: 'Times New Roman';">255</span><span style="">桶。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个整数，表示所需的最小日运费（元）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>1 2</p>
<p>2 3</p>
<p>1 2</p>
<p>5 2</p>
<p>1 10</p>
<p>2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>41</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>