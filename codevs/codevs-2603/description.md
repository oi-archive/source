<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某国有n<span style="">个城市</span>，它们互相之间没有公路相通，因此交通十分不便。为解决这一"<span style="">行路难"</span><span style="">的问题</span>，政府决定修建公路，修建公路的任务由各城市共同完成。</p>
<p>修建工程分若干轮完成。在每一轮中，每个城市选择一个与它最近的城市，申请修建通往该城市的公路。政府负责审批这些申请以决定是否同意修建。</p>
<p>政府审批的规则如下：</p>
<p>(1)<span style="">如果两个或以上城市申请修建同一条公路</span>，则让它们共同修建；</p>
<p>(2)<span style="">如果三个或以上的城市申请修建的公路成环</span>。如，A<span style="">申请修建公路AB</span>，B<span style="">申请修建公路BC</span>，C<span style="">申请修建公路CA</span>，则政府将否决其中最短的一条公路的修建申请；</p>
<p> (3)<span style="">其他情况的申请一律同意</span>。</p>
<p>一轮修建结束后，可能会有若干城市可以通过公路直接或间接相连。这些可以互相：连通的城市即组成"<span style="">城市联盟"</span>。在下一轮修建中，每个"<span style="">城市联盟"</span><span style="">将被看作一个城市</span>，发挥一个城市的作用。</p>
<p>当所有城市被组合成一个"<span style="">城市联盟"</span><span style="">时</span>，修建工程也就完成了。</p>
<p>你的任务是根据城市的分布和前面讲到的规则，计算出将要修建的公路总长度。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n(n≤5000),<span style="">表示城市的数量</span>。</p>
<p>以下n<span style="">行</span>，每行两个整数x<span style="">和y(-10</span>6≤x、y≤106)，表示一个城市的坐标。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个实数，四舍五入保留两位小数，表示公路总长。(<span style="font-family: 宋体;">保证有惟一解</span>，答案小于108)</p>

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
<p>0 0</p>
<p>1 2</p>
<p>-1 2</p>
<p>0 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6.47</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n≤5000</p>
</div>
</div>