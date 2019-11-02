<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>若一个图的每一对不同顶点都恰有一条边相连，则称为完全图。</p>
<p>最小生成树MST在Smart的指引下找到了你，希望你能帮它变成一个最小完全图（边权之和最小的完全图）。</p>
<p>注意：必须保证这个最小生成树MST对于最后求出的最小完全图是唯一的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数<span style="font-family: Times New Roman;">n</span><span style="">，表示生成树的节点数。</span></p>
<p>接下来有<span style="font-family: Times New Roman;">n-1</span><span style="">行，每行有三个正整数，依次表示每条边的</span>顶点编号和边权。</p>
<p>（顶点的边号在<span style="font-family: Times New Roman;">1-n</span><span style="">之间，边权</span><span style="font-family: Times New Roman;">&lt;</span>2<sup>31</sup>）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个整数<span style="font-family: Times New Roman;">ans</span><span style="font-family: 宋体;">，表示以该树为最小生成树的最小完全图的边权之和</span>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>1 2 1</p>
<p>1 3 1</p>
<p>1 4 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%<span style="">的数据：</span><span style="font-family: Times New Roman;">n&lt;1000</span><span style="">；</span></p>
<p>100%<span style="">的数据：</span><span style="font-family: Times New Roman;">n</span>≤20000<span style="">，所有的</span>边权<span style="font-family: Times New Roman;">&lt;</span>2<sup>31</sup>。</p>
</div>
</div>