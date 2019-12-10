<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小H发誓要做21世纪最伟大的数学家。他认为，做数学家与做歌星一样，第一步要作好包装，不然本事再大也推不出去。为此他决定先在自己的住所上下功夫，让人一看就知道里面住着一个“未来的大数学家”。<br>为了描述方便，我们以向东为x轴正方向，向北为y轴正方向，建立平面直角坐标系。小H的小屋东西长为100Hil（Hil是小H自己使用的长度单位，至于怎样折合成“m”，谁也不知道）。东墙和西墙均平行于y轴，北墙和南墙分别是斜率为k1和k2的直线，k1和k2为正实数。北墙和南墙的墙角处有很多块草坪，每块草坪都是一个矩形，矩形的每条边都平行于坐标轴。相邻两块草坪的接触点恰好在墙上，接触点的横坐标被称为它所在墙的“分点”，这些分点必须是1到99的整数。<br>小H认为，对称与不对称性的结合才能充分体现“数学美”。因此，在北墙角要有m块草坪，在南墙角要有n块草坪，并约定m≤n。如果记北墙和南墙的分点集合分别为X1，X2，则应满足X2包含X1，即北墙的任何一个分点一定是南墙的分点。<br>由于小H目前还没有丰厚的收入，他必须把草坪的造价降到最低，即草坪的占地总面积最小。你能编程帮他解决这个难题吗？</p>

<img src="/source/codevs/codevs-1756/img/aHR0cDovL2NvZGV2cy5jbi9tZWRpYS9pbWFnZS9wcm9ibGVtLzE3NTYuZ2lm.gif" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>仅一行，包含4个数<em>k</em><sub>1</sub>，<em>k</em><sub>2</sub>，<em>m</em>，<em>n</em>。<em>k</em><sub>1</sub>和<em>k</em><sub>2</sub>为正实数，分别表示北墙和南墙的斜率，精确到小数点后第一位。<em>m</em>和<em>n</em>为正整数，分别表示北墙角和南墙角的草坪的块数。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个实数，表示草坪的最小占地总面积。精确到小数点后第一位。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>0.5 0.2 2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3000.0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<ul>
<li>南北墙距离很远，不会出现南墙草坪和北墙草坪重叠的情况</li>
<li>2≤m≤n≤100</li>
</ul>
</div>
</div>