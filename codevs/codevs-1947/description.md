<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在 W 星球上有 n 个国家。为了各自国家的经济发展，他们决定在各个国家 之间建设双向道路使得国家之间连通。但是每个国家的国王都很吝啬，他们只愿 意修建恰好 n – 1 条双向道路。 每条道路的修建都要付出一定的费用，这个费用等于道路长度乘以道路两端 的国家个数之差的绝对值。例如，在下图中，虚线所示道路两端分别有 2 个、4 个国家，如果该道路长度为 1，则费用为 1×|2 – 4|=2。图中圆圈里的数字表示国 家的编号。 <br>由于国家的数量十分庞大，道路的建造方案有很多种，同时每种方案的修建 费用难以用人工计算，国王们决定找人设计一个软件，对于给定的建造方案，计 算出所需要的费用。请你帮助国王们设计一个这样的软件。</p>

<img src="/source/codevs/codevs-1947/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xOTQ3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTk0Ny5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含一个整数 n，表示 W 星球上的国家的数量，国家从 1 到 n 编号。 接下来 n – 1 行描述道路建设情况，其中第 i 行包含三个整数 ai、bi和 ci，表 示第 i 条双向道路修建在 ai与 bi两个国家之间，长度为 ci。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，表示修建所有道路所需要的总费用。</p>

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
<p>1 2 1</p>
<p>1 3 1</p>
<p>1 4 2</p>
<p>6 3 1</p>
<p>5 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>20</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤ai, bi≤n</p>
<p>0≤ci≤10<sup>6</sup></p>
<p>2≤n≤10<sup>6</sup></p>
</div>
</div>