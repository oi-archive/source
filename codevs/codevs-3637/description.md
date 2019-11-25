<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">【问题描述】</span></p><p><span style="">    </span><span style="">某国有n个城市，它们互相之间没有公路相通，因此交通十分不便。为解决这一“行路难”的问题，政府决定修建公路。修建公路的任务由各城市共同完成。</span></p><p><span style="">    </span><span style="">修建工程分若干轮完成。在每一轮中，每个城市选择一个与它最近的城市，申请修建通往该城市的公硌。政府负责审批这些申请以决定是否同意修建。</span></p><p><span style="">    </span><span style="">政府审批的规则如下：</span></p><p><span style="">    (1)</span><span style="">如果两个或以上城市申请修建同一条公路，则让它们共同修建；</span></p><p style=""><span style="">(2)</span><span style="">如果三个或以上的城市申请修建的公路成环。如下图，A中请修建公路AB,B申请修建公路BC。C申请修建公路CA。则政府将否决其中最短的一条公路的修建申请；</span></p><p><span style="">    (3)</span><span style="">其他情况的申请一律同意。</span></p><p><span style="">    </span><span style="">一轮修建结束后，可能会有若干城市可以通过公路直接或间接相连。这些可以互相连通的城市即组成“城市联盟”。在下一轮修建中，每个“城市联盟”将被看作一个城市，发挥一个城市的作用。</span></p><p><span style="">    </span><span style="">当所有城市被组合成一个“城市联盟”时，修建工程也就完成了。</span></p><p><span style="">    </span><span style="">你的任务是根据城市的分布和前面讲到的规则，计算出将要修建的公路总长度。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行一个整数n，表示城市的数量。(n≤5000)</span></p><p style=""><span style="">以下n行，每行两个整数x和y，表示一个城市的坐标（-1000000&lt;=x，y&lt;=1000000）</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style="font-family:宋体">一个实数，四舍五入保留两位小数，表示公路总长度。（保证有唯一解）</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">4 </span></p><p><span style="">0 0</span></p><p><span style="">1 2</span></p><p><span style="">-1 2</span></p><p><span style="font-family: Calibri, sans-serif;">0 4</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">6.47</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>上述</p>
</div>
</div>