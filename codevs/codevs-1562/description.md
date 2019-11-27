<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>你第一天接手三鹿牛奶公司就发生了一件倒霉的事情：公司不小心发送了一批有三聚氰胺的牛奶。很不幸，你发现这件事的时候，有三聚氰胺的牛奶已经进入了送货网。这个送货网很大，而且关系复杂。你知道这批牛奶要发给哪个零售商，但是要把这批牛奶送到他手中有许多种途径。送货网由一些仓库和运输卡车组成，每辆卡车都在各自固定的两个仓库之间单向运输牛奶。在追查这些有三聚氰胺的牛奶的时候，有必要保证它不被送到零售商手里，所以必须使某些运输卡车停止运输，但是停止每辆卡车都会有一定的经济损失。你的任务是，在保证坏牛奶不送到零售商的前提下，制定出停止卡车运输的方案，使损失最小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行<span style="font-family: Times New Roman;">: </span><span style="">两个整数</span><span style="font-family: Times New Roman;">N(2&lt;=N&lt;=32)</span><span style="">、</span><span style="font-family: Times New Roman;">M(0&lt;=M&lt;=1000), N</span><span style="">表示仓库的数目，</span><span style="font-family: Times New Roman;">M</span><span style="">表示运输卡车的数量。仓库</span><span style="font-family: Times New Roman;">1</span><span style="">代 表发货工厂，仓库</span><span style="font-family: Times New Roman;">N</span><span style="">代表有三聚氰胺的牛奶要发往的零售商。 第</span><span style="font-family: Times New Roman;">2..M+1</span><span style="">行</span><span style="font-family: Times New Roman;">: </span><span style="">每行</span><span style="font-family: Times New Roman;">3</span><span style="">个整数</span><span style="font-family: Times New Roman;">Si,Ei,Ci</span><span style="">。其中</span><span style="font-family: Times New Roman;">Si,Ei</span><span style="">表示这 辆卡车的出发仓库，目的仓库。</span><span style="font-family: Times New Roman;">Ci(0 &lt;= C i &lt;= 2,000,000) </span><span style="">表示让这辆卡车停止运输的损失。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">两个整数<span style="font-family: Times New Roman;">C</span><span style="font-family: 宋体;">、</span><span style="font-family: Times New Roman;">T</span><span style="font-family: 宋体;">：</span><span style="font-family: Times New Roman;">C</span><span style="font-family: 宋体;">表示最小的损失，</span><span style="font-family: Times New Roman;">T</span><span style="font-family: 宋体;">表示在损失最小的前提下，最少要停止的卡车数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5</p>
<p>1 3 100</p>
<p>3 2 50</p>
<p>2 4 60</p>
<p>1 2 40</p>
<p>2 3 80</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>60 1</p>

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