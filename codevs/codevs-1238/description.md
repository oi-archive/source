<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">给定一张航空图，图中顶点代表城市，边代表 2 城市间的直通航线。现要求找出一条满</span><span style="">足下述限制条件的且途经城市最多的旅行路线。 </span><br><span style="">(1)从最西端城市出发，单向从西向东途经若干城市到达最东端城市，然后再单向从东</span><br><span style="">向西飞回起点(可途经若干城市)。 </span><br><span style="">(2)除起点城市外，任何城市只能访问 1 次。  </span><br><span style="">对于给定的航空图，试设计一个算法找出一条满足要求的最佳航空旅行路线。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第 1 行有 2 个正整数 N 和 V，N 表示城市数，N&lt;100，</span><span style="">V 表示直飞航线数。</span></p>
<p><span style="">接下来的 N 行中每一行是一个城市名，可乘飞机访问这些城市。城市名</span><span style="">出现的顺序是从西向东。也就是说，设 i,j 是城市表列中城市出现的顺序，当 i&gt;j 时，表示</span><span style="">城市 i 在城市 j 的东边，而且不会有 2 个城市在同一条经线上。城市名是一个长度不超过</span><span style="">15 的字符串，串中的字符可以是字母或阿拉伯数字。例如，AGR34 或 BEL4。</span></p>
<p><br><span style="">再接下来的 V 行中，每行有 2 个城市名，中间用空格隔开，如 city1 city2 表示city1</span><span style="">到 city2 有一条直通航线，从 city2 到 city1 也有一条直通航线。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: large;">第 1 行是旅行路</span><span style="font-size: large;">线中所访问的城市总数 M。接下来的 M＋1 行是旅行路线的城市名，每行写 1 个城市名。首</span><span style="font-size: large;">先是出发城市名，然后按访问顺序列出其它城市名。注意，最后 1 行（终点城市）的城市名</span><span style="font-size: large;">必然是出发城市名。如果问题无解，则输出&ldquo;No Solution!&rdquo;。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">8 9 </span></p>
<p><span style="">Vancouver </span></p>
<p><span style="">Yellowknife </span></p>
<p><span style="">Edmonton </span></p>
<p><span style="">Calgary </span></p>
<p><span style="">Winnipeg </span></p>
<p><span style="">Toronto </span></p>
<p><span style="">Montreal </span></p>
<p><span style="">Halifax </span></p>
<p><span style="">Vancouver </span><span style="">Edmonton </span></p>
<p><span style="">Vancouver </span><span style="">Calgary </span></p>
<p><span style="">Calgary </span><span style="">Winnipeg </span></p>
<p><span style="">Winnipeg </span><span style="">Toronto </span></p>
<p><span style="">Toronto </span><span style="">Halifax </span></p>
<p><span style="">Montreal </span><span style="">Halifax </span></p>
<p><span style="">Edmonton </span><span style="">Montreal </span></p>
<p><span style="">E</span><span style="">dmonton </span><span style="">Yellowknife </span></p>
<p><span style="">Edmonton </span><span style="">Calgary</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">7 </span></p>
<p><span style="">Vancouver </span></p>
<p><span style="">Edmonton </span></p>
<p><span style="">Montreal </span></p>
<p><span style="">Halifax </span></p>
<p><span style="">Toronto </span></p>
<p><span style="">Winnipeg </span></p>
<p><span style="">Calgary </span></p>
<p><span style="">Vancouver</span></p>

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