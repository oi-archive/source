<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某人喜欢按照自己的规则去市场买菜，他每天都列一个买菜的清单，自由市场的菜码放也有一个顺序，该人有一个特点，就是按顺序买菜，从不走回头路，当然，她希望能花最好的钱买到所有的菜，你能帮帮他吗？</p>
<p> </p>
<p>输入输出数据如下图：</p>

<img src="/source/codevs/codevs-1253/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzEyNTMuanBn.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行为两个整数M，N， M (1 £ M £ 100)时她的买菜单，N(1 £ N £100,000) 表示自由市场的所有菜单. </p>
<p>第二行为 M 整数，其中Xi (1 £Xi £ 100,000, 1 £ i £ M)表示她的菜单中的第i号菜. 接下来的N 行表示自由市场按顺序码放的菜，其中每行两个数，整数 K 和实数 P 分别表示编号为<span style="font-family: 'Times New Roman';">K</span><span style="">的菜价为</span>P (1 £ K £ 100,000). </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">如果他可以买到所有的菜，则输出付出的最小价值，否则输出&ldquo;Impossible&rdquo;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 8</p>
<p>1 1 2 20</p>
<p>2 0.29</p>
<p>1 0.30</p>
<p>20 0.15</p>
<p>1 1.00</p>
<p>5 0.05</p>
<p>2 10.00</p>
<p>20 20.00</p>
<p>20 10.00</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>21.30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
如描述
</div>
</div>