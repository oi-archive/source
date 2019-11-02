<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">Steve是一名矿工，他热衷于挖掘矿石。一天他来到了这片土地上，准备开采这里的矿产。他已经通过高(kai)科(wai)技(gua)手段了解到了这里的矿产分布，现在他想知道，在最多T个单位时间内，他能挖掘到的最大价值是多少？</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">Steve每个单位时间可以向左、右或下移动一格，并挖掘该格内的矿石。Steve不能向上移动、或是挖掘头顶的矿石。矿石不会被重复挖掘，意味着如果Steve经过一个格子多次，那么只有第一次经过可以获得相应价值的矿石。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">输入数据第一行为三个整数n，m，T，表示地图为n行m列，时间上限为T。</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">接下来n行，每行m个字符，含义如下：</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">0（数字零）：表示该方格价值为0</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">1~9：表示该方格的价值</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">P：表示该方格为Steve的初始位置</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">*：表示该方格不能被挖掘或行走</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">数据保证第2行由m-1个"0"和1个"P"组成，且第3至n+1行不会出现"P"。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 14px; line-height: 20px; background-color: rgb(255, 255, 255);">输出文件仅一行，一个整数，表示Steve在时限内能够获得的最大价值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">3 4 3</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">0P00</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">*663</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">*7**</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">5</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">[样例解释]</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><img src="/source/codevs/codevs-6064/img/aHR0cDovL3d3dy5nZGZ6b2ouY29tL3VwbG9hZC9mZXRjaF9pbWFnZS8xYzYzZjhhNTljNzgyYzkwMzJhZDJhN2IwNmI1YTBiMi5wbmc=.png" style=""></p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">如图，石头价值为0，金矿石价值为6，煤矿石价值为3，钻石矿石价值为7</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">第1个单位时间里，Steve可以向下挖掘并获得6点价值，他也可以选择向左或向右，但显然这两种方案并没有什么<img src="/source/codevs/codevs-6064/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy02MDY0L2h0dHA6Ly83eGs1OGwuY29tMS56MC5nbGIuY2xvdWRkbi5jb20vYWNjb3VudC91ZWRpdG9yL3RoZW1lcy9kZWZhdWx0L2ltYWdlcy9zcGFjZXIuZ2lm.gif" style="">用。</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">第2个单位时间里，Steve可以向下挖掘并获得7点价值，总共13点；或者向右挖掘并获得6点价值，共12点。</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">第3个单位时间里，若Steve挖掘了矿石6，7，则他不能进行任何行动，总价值为13；</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">若Steve挖掘了矿石6，6，则他可以向右挖掘并获得3点价值，共15点。</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">总价值最大为15点。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">对于100%的数据，1 &lt;= n,m &lt;= 10 ，1 &lt;= T &lt;= 10</span></p>
</div>
</div>