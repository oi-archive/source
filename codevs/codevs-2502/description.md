<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>      H城市举办马拉松比赛。比赛区域有N个补给站 ，2≤N≤1000。为了方便说明，我们将N个补给站名称以正整数 1,2,…,N来表示。N个补给站有街道来连接，使得选手可从任一个补给站出发，经由几条街道抵达另一个补给站。我们可以用图形来表示这些补给站跟街道之间的关系：节点表示补给站，而连接节点的连结线则代表连接两个补给站之间的街道 (如图一所示，其中补给站名称以圆圈内的数字来表示，而街道上的数字则代表跑完此街道所需花费的时间)  。我们以符号(I,J)来表示连接补给站I和补给站的街道J(连结线 ) 。每一条街道(I,J)都结合一个整数的权重值 c(I,J) 来代表跑完(I,J)这条街道所要花费的时间 ，其中c(I,J) 需满足1≤c(I,J)≤999 。令 Nodd代表那些与奇数条街道相接的补给站个数，则 H城市有一个重要特性： Nodd  为偶数且  0 ≤ Nodd ≤20 。</p>
<p>     给定一个起点补给站 S和终点补给站 T   (S ≠T)  ，请写一个程式计算选手从起 始补给站S 出发，把每条街道都跑过至少一次且到达终点补给站T所需花费的最短时间。注意：这个城市中所有的街道都是双向道，同一个补给站和街道可被重复经过。</p>
<p>      在图一的例子中，Nodd  =0  ，S=1  ，T=6 。图二说明其中一种跑法为：S=1→3→2→1→2→4→3→5→2→4→5→6→4→6=T ，可在15单位时间从起点出发，将所有街道都跑过至少一次，且到达终点。然而此种跑法所需的时间并非最短。事实上，此例中花费时间为最短的跑法如图三所示，为1→2→3→1→3→4→2→5→3→5→4→6→5→6  ，所花费时间为14单位。</p>

<img src="/source/codevs/codevs-2502/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yNTAyL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8yNTAyLnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>     第一行有四个数字，连续两个数字之间以 空白符号做区隔。第一个数字 N(2≤N≤1000)代表图形的节点个数；第二个数字 M (1≤M≤N(N-1)/2) 代表图形的连结线个数；第叁个数字则代表起点名称；第四个数字则代表终点名称。从第二行起连续有 M行，表示 M条连结线，每行有叁个数字，连续两个数字之间以空白符号做区隔：前二个数字代表连结线的两个端点，第叁个数字代表连结线的权重值。输入保证任两个补给站之间都有路径相连， Nodd 为偶数且 0 ≤Nodd≤20 。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp;输出一个整数，代表选手所花费的最短时间。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>6 10 1 6</p>
<p>1 2 1</p>
<p>1 3 1</p>
<p>2 3 1</p>
<p>2 4 2</p>
<p>2 5 1</p>
<p>3 4 1</p>
<p>3 5 1</p>
<p>4 5 1</p>
<p>4 6 1</p>
<p>5 6 1 </p>
<p> </p>
<p>样例2：</p>
<p>3 3 1 2</p>
<p>1 2 4</p>
<p>1 3 6</p>
<p>2 3 5 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>14</p>
<p>样例2：</p>
<p>19</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>请参见输入描述</p>
<p> </p>
<p>TW一百学年度全国高级中学咨询学科能力竞赛决赛6</p>
</div>
</div>