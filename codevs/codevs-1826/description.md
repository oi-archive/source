<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在<span style="font-family: 'Times New Roman';">2xyz</span><span style="">年，人类已经移民到了火星上。由于工业的需要，人们开始在火星上采矿。火星的矿区是一个边长为</span><span style="font-family: 'Times New Roman';">N</span><span style="">的正六边形，为了方便规划，整个矿区被分为</span><span style="font-family: 'Times New Roman';">6*N*N</span><span style="">个正三角形的区域（如图</span><span style="font-family: 'Times New Roman';">1</span><span style="">）。</span></p>
<p> </p>
<p>整个矿区中存在<span style="font-family: 'Times New Roman';">A</span><span style="">矿，</span><span style="font-family: 'Times New Roman';">B</span><span style="">矿，</span><span style="font-family: 'Times New Roman';">C</span><span style="">矿三个矿场，和</span><span style="font-family: 'Times New Roman';">a</span><span style="">厂，</span><span style="font-family: 'Times New Roman';">b</span><span style="">厂，</span><span style="font-family: 'Times New Roman';">c</span><span style="">厂三个炼矿厂。每个三角形的区域可以是一个矿场、炼矿厂、山地、或者平地。现在矿区管理局要求建立一个交通系统，使得矿场和对应炼矿厂之间存在一条公路，并且三条公路互不交叉</span><span style="font-family: 'Times New Roman';">(</span><span style="">即一个三角形区域中不存在两条以上运输不同矿的公路</span><span style="font-family: 'Times New Roman';">)</span><span style="">。两个三角形区域是相邻的当且仅当这两个三角形存在公共边，只有相邻的两个区域之间才能建一段路，建这段路的费用为</span><span style="font-family: 'Times New Roman';">1</span><span style="">。注意，山地上是不能建公路的。由于火星金融危机的影响，矿区管理局想知道建立这样一个交通系统最少要花多少费用。更多的，当局向知道有多少种花费最小的方案。</span></p>

<img src="/source/codevs/codevs-1826/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xODI2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTgyNi5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第<span style="font-family: 'Times New Roman';">1</span><span style="">行一个整数</span><span style="font-family: 'Times New Roman';">N</span><span style="">。表示这个矿区是边长为</span><span style="font-family: 'Times New Roman';">N</span><span style="">的正六边形。</span></p>
<p>接下来有<span style="font-family: 'Times New Roman';">6*N*N</span><span style="">的整数，分为</span><span style="font-family: 'Times New Roman';">2*N</span><span style="">行，表示矿区当前区域的情况。</span><span style="font-family: 'Times New Roman';">0</span><span style="">表示平地，</span><span style="font-family: 'Times New Roman';">1,2,3</span><span style="">表示对应的矿区或者炼矿厂，</span><span style="font-family: 'Times New Roman';">4</span><span style="">表示山地。（样例</span><span style="font-family: 'Times New Roman';">1</span><span style="">对应图</span><span style="font-family: 'Times New Roman';">2</span><span style="">）。可能有多组数据，请处理到文件结尾</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对于每组数据，包含两个整数，表示最小费用和达到最小费用的方案数。如果找不到符合要求的方案，输出<span style="font-family: 'Times New Roman';">-1&nbsp;-1</span><span style="font-family: 宋体;">。由于方案数可能过大，所以请把方案数</span><span style="font-family: 'Times New Roman';">mod&nbsp;1000000007</span><span style="font-family: 宋体;">。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>  0 1 0 0 0</p>
<p>0 0 2 0 4 0 0</p>
<p>0 0 4 3 0 3 2</p>
<p>  0 0 0 1 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>18 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Times New Roman';">50%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">N≤4</span></p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">N≤6</span></p>
</div>
</div>