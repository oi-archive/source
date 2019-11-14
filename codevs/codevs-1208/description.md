<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>到了难得的暑假，为了庆祝Eric在数学考试不及格，Kevin决定带Eric出去旅游~~<br>经过一番抉择，两人决定将T国作为他们的目的地。T国的国土可以用一个凸N边形来表示，N个顶点表示N个入境/出境口。T国包含N-2个城市，每个城市都是顶点均为N边形顶点的三角形(换而言之，城市组成了关于T国的一个三角剖分)。两人的旅游路线可以看做是连接N个顶点中不相邻两点的线段。<br>为了能够买到最好的纪念品，Eric希望旅游路线上经过的城市尽量多。作为Kevin的好友，你能帮帮Kevin吗？</p>

<img src="/source/codevs/codevs-1208/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMjA4L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMjA4LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>每个输入文件中仅包含一个测试数据。</p>
<p>第一行包含两个由空格隔开的正整数<span style="font-family: Calibri;">N</span><span style="">，</span><span style="font-family: Calibri;">N</span><span style="">的含义如题目所述。</span></p>
<p>     接下来有<span style="font-family: Calibri;">N-2</span><span style="">行，每行包含三个整数 </span><span style="font-family: Calibri;">p,q,r</span><span style="">，表示该城市三角形的三个顶点的编号</span><span style="font-family: Calibri;">(T</span><span style="">国的</span><span style="font-family: Calibri;">N</span><span style="">个顶点按顺时间方向从</span><span style="font-family: Calibri;">1</span><span style="">至</span><span style="font-family: Calibri;">n</span><span style="">编号</span><span style="font-family: Calibri;">)</span><span style="">。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件共包含<span style="font-family: Calibri;">1</span><span style="font-family: 宋体;">行，表示最多经过的城市数目。</span><span style="font-family: Calibri;">(</span>一个城市被当做经过当且仅当其与线路有至少两个公共点)</p>

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
<p>1 2 4</p>
<p>2 3 4</p>
<p>1 4 5</p>
<p>1 5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: Calibri;">20%</span><span style="">的数据，N&lt;=2000</span></p>
<p>对于<span style="font-family: Calibri;">100%</span><span style="">的数据，4&lt;=N&lt;=200000</span></p>
</div>
</div>