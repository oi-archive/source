<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>物流公司要把一批货物从码头<span style="font-family: 'Times New Roman';">A</span><span style="">运到码头</span><span style="font-family: 'Times New Roman';">B</span><span style="">。由于货物量比较大，需要</span><span style="font-family: 'Times New Roman';">n</span><span style="">天才能运完。货物运输过程中一般要转停好几个码头。物流公司通常会设计一条固定的运输路线，以便对整个运输过程实施严格的管理和跟踪。由于各种因素的存在，有的时候某个码头会无法装卸货物。这时候就必须修改运输路线，让货物能够按时到达目的地。但是修改路线是一件十分麻烦的事情，会带来额外的成本。因此物流公司希望能够订一个</span><span style="font-family: 'Times New Roman';">n</span><span style="">天的运输计划，使得总成本尽可能地小。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是四个整数<span style="font-family: 'Times New Roman';">n</span><span style="">（</span><span style="font-family: 'Times New Roman';">1</span><span style="">≤</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤</span><span style="font-family: 'Times New Roman';">100</span><span style="">）、</span><span style="font-family: 'Times New Roman';">m</span><span style="">（</span><span style="font-family: 'Times New Roman';">1 </span><span style="">≤</span><span style="font-family: 'Times New Roman';">m</span><span style="">≤</span><span style="font-family: 'Times New Roman';">20</span><span style="">）、</span><span style="font-family: 'Times New Roman';">K</span><span style="">和</span><span style="font-family: 'Times New Roman';">e</span><span style="">。</span><span style="font-family: 'Times New Roman';">n</span><span style="">表示货物运输所需天数，</span><span style="font-family: 'Times New Roman';">m</span><span style="">表示码头总数，</span><span style="font-family: 'Times New Roman';">K</span><span style="">表示每次修改运输路线所需成本。接下来</span><span style="font-family: 'Times New Roman';">e</span><span style="">行每行是一条航线描述，包括了三个整数，依次表示航线连接的两个码头编号以及航线长度（＞</span><span style="font-family: 'Times New Roman';">0</span><span style="">）。其中码头</span><span style="font-family: 'Times New Roman';">A</span><span style="">编号为</span><span style="font-family: 'Times New Roman';">1</span><span style="">，码头</span><span style="font-family: 'Times New Roman';">B</span><span style="">编号为</span><span style="font-family: 'Times New Roman';">m</span><span style="">。单位长度的运输费用为</span><span style="font-family: 'Times New Roman';">1</span><span style="">。航线是双向的。再接下来一行是一个整数</span><span style="font-family: 'Times New Roman';">d</span><span style="">，后面的</span><span style="font-family: 'Times New Roman';">d</span><span style="">行每行是三个整数</span><span style="font-family: 'Times New Roman';">P (1</span><span style="">＜</span><span style="font-family: 'Times New Roman';">P</span><span style="">＜</span><span style="font-family: 'Times New Roman';">m</span><span style="">），</span><span style="font-family: 'Times New Roman';">a</span><span style="">，</span><span style="font-family: 'Times New Roman';">b (1 </span><span style="">≤</span><span style="font-family: 'Times New Roman';">a</span><span style="">≤</span><span style="font-family: 'Times New Roman';">b </span><span style="">≤</span><span style="font-family: 'Times New Roman';">n)</span><span style="">。表示编号为</span><span style="font-family: 'Times New Roman';">P</span><span style="">的码头从第</span><span style="font-family: 'Times New Roman';">a</span><span style="">天到第</span><span style="font-family: 'Times New Roman';">b</span><span style="">天无法装卸货物（含头尾）。同一个码头有可能在多个时间段内不可用。但任何时间都存在至少一条从码头</span><span style="font-family: 'Times New Roman';">A</span><span style="">到码头</span><span style="font-family: 'Times New Roman';">B</span><span style="">的运输路线。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp; 包括了一个整数表示最小的总成本。总成本＝<span style="font-family: 'Times New Roman';">n</span><span style="font-family: 宋体;">天运输路线长度之和</span><span style="font-family: 'Times New Roman';">+K*</span><span style="font-family: 宋体;">改变运输路线的次数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5 10 8</p>
<p>      1 2 1</p>
<p>      1 3 3</p>
<p>      1 4 2</p>
<p>      2 3 2</p>
<p>      2 4 4</p>
<p>      3 4 1</p>
<p>      3 5 2</p>
<p>      4 5 2</p>
<p>      4</p>
<p>      2 2 3</p>
<p>      3 1 1</p>
<p>      3 3 3</p>
<p>      4 4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p> 32</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>【样例输入说明】  </p>
<p><img height="163" src="../../../media/image/1365054308.650.101087867946.png" width="399"></p>
<p> </p>
<p>    上图依次表示第<span style="font-family: 'Times New Roman';">1</span><span style="">至第</span><span style="font-family: 'Times New Roman';">5</span><span style="">天的情况，阴影表示不可用的码头</span></p>
<p>    【样例输出说明】</p>
<p>    前三天走<span style="font-family: 'Times New Roman';">1-4-5</span><span style="">，后两天走</span><span style="font-family: 'Times New Roman';">1-3-5</span><span style="">，这样总成本为（</span><span style="font-family: 'Times New Roman';">2</span><span style="">＋</span><span style="font-family: 'Times New Roman';">2</span><span style="">）</span><span style="font-family: 'Times New Roman';">*3</span><span style="">＋（</span><span style="font-family: 'Times New Roman';">3</span><span style="">＋</span><span style="font-family: 'Times New Roman';">2</span><span style="">）</span><span style="font-family: 'Times New Roman';">*2</span><span style="">＋</span><span style="font-family: 'Times New Roman';">10</span><span style="">＝</span><span style="font-family: 'Times New Roman';">32</span><span style="">。</span></p>
</div>
</div>
</div>