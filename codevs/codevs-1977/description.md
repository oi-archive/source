<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>我们知道，<span style="font-family: 'Lucida Console';">dl24wireless</span><span style="">的无线路由器分散在很多位置：如果我们在学校建立平面直角坐标系，则每个无线路由器能够覆盖的位置可看做一个矩形。</span></p>
<p>现在我们想知道，信号总共的覆盖面积是多少。</p>
<p>注意，如果从某个点想走到学校外，无论怎么走都要经过信号覆盖过的地方，则我们认为这个点也被信号覆盖了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个整数<span style="font-family: 'Lucida Console';">N</span><span style="">，代表无线路由器的个数。</span></p>
<p>接下来<span style="font-family: 'Lucida Console';">N</span><span style="">行，每行表示一个无线路由器。第</span><span style="font-family: 'Lucida Console';">i+1</span><span style="">行有四个整数</span><span style="font-family: 'Lucida Console';">Ai</span><span style="">，</span><span style="font-family: 'Lucida Console';">Bi</span><span style="">，</span><span style="font-family: 'Lucida Console';">Ci</span><span style="">，</span><span style="font-family: 'Lucida Console';">Di</span><span style="">，表示第</span><span style="font-family: 'Lucida Console';">i</span><span style="">个无线路由器所覆盖的面积，是左下角坐标（</span><span style="font-family: 'Lucida Console';">Ai</span><span style="">，</span><span style="font-family: 'Lucida Console';">Bi</span><span style="">），右上角坐标为（</span><span style="font-family: 'Lucida Console';">Ci</span><span style="">，</span><span style="font-family: 'Lucida Console';">Di</span><span style="">）的矩形。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">共一行，为一个整数，即所覆盖的总面积。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Input1:</p>
<p>2</p>
<p>100 100 500 500</p>
<p>300 300 700 700</p>
<p>Input2:</p>
<p>4</p>
<p>1 1 4 2</p>
<p>1 1 2 4</p>
<p>1 3 4 4</p>
<p>3 1 4 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Output1:</p>
<p>280000</p>
<p>Output2:</p>
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于<span style="font-family: 'Lucida Console';">20%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">N</span><span style="">≤</span><span style="font-family: 'Lucida Console';">50</span><span style="">，</span><span style="font-family: 'Lucida Console';">1</span><span style="">≤</span><span style="font-family: 'Lucida Console';">Ai</span><span style="">，</span><span style="font-family: 'Lucida Console';">Bi</span><span style="">，</span><span style="font-family: 'Lucida Console';">Ci</span><span style="">，</span><span style="font-family: 'Lucida Console';">Di</span><span style="">≤</span><span style="font-family: 'Lucida Console';">1000</span><span style="">。</span></p>
<p>对于<span style="font-family: 'Lucida Console';">50%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">N</span><span style="">≤</span><span style="font-family: 'Lucida Console';">1000</span><span style="">，</span><span style="font-family: 'Lucida Console';">1</span><span style="">≤</span><span style="font-family: 'Lucida Console';">Ai</span><span style="">，</span><span style="font-family: 'Lucida Console';">Bi</span><span style="">，</span><span style="font-family: 'Lucida Console';">Ci</span><span style="">，</span><span style="font-family: 'Lucida Console';">Di</span><span style="">≤</span><span style="font-family: 'Lucida Console';">1000</span><span style="">。</span></p>
<p>对于<span style="font-family: 'Lucida Console';">100%</span><span style="">的数据，</span><span style="font-family: 'Lucida Console';">1</span><span style="">≤</span><span style="font-family: 'Lucida Console';">N</span><span style="">≤</span><span style="font-family: 'Lucida Console';">1000</span><span style="">，</span><span style="font-family: 'Lucida Console';">1</span><span style="">≤</span><span style="font-family: 'Lucida Console';">Ai</span><span style="">，</span><span style="font-family: 'Lucida Console';">Bi</span><span style="">，</span><span style="font-family: 'Lucida Console';">Ci</span><span style="">，</span><span style="font-family: 'Lucida Console';">Di</span><span style="">≤</span><span style="font-family: 'Lucida Console';">1000000</span><span style="">。</span></p>
<p><span style="">数据保证，不会有任何两个矩形区域有且只有一个公共点。</span></p>
</div>
</div>