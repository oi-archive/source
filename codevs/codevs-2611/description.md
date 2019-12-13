<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>某旅游区里面有Ｎ个景点。两个景点之间可能直接有道路相连，用a[i][j]<span style="">表示它的长度</span>，否则它们之间没有直接的道路相连。这里所说的道路是没有规定方向的，也就是说，如果从i到j有直接的道路，那么从j到i也有，并且长度与之相等。</p>
<p>旅游区规定：每个游客的旅游线路只能是一个回路（好霸道的规定）。也就是说，游客可以任取一个景点出发，依次经过若干个景点，最终回到起点。一天，Smart决定到这个景区来旅游，由于他实在已经很累了，于是他决定尽量少走一些路。</p>
<p>他想请你帮他求出最优的路线。怎么样，不是很难吧？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入有多组数据。对于每组数据：</p>
<p>第一行有两个正整数<span style="font-family: Consolas;">N</span><span style="">，</span><span style="font-family: Consolas;">M</span><span style="">，分别表示景点个数和有多少对景点之间直接有边相连（</span><span style="font-family: Consolas;">N</span>≤100,M≤10000<span style="">）</span>；</p>
<p>接下来M<span style="">行，每行三个正整数，分别表示一条道路的两端的编号，以及这条道路的长度</span>（长度≤1000）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">对于每组数据，输出一行，如果该回路存在，则输出一个正整数，表示该回路的总长度；否则输出<span style="font-family: Consolas;">&ldquo;No&nbsp;solution.&rdquo;</span><span style="font-family: 宋体;">（不要输出引号）</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 7</p>
<p>1 4 1</p>
<p>1 3 300</p>
<p>3 1 10</p>
<p>1 2 16</p>
<p>2 3 100</p>
<p>2 5 15</p>
<p>5 3 20</p>
<p>4 3</p>
<p>1 2 10</p>
<p>1 3 20</p>
<p>1 4 30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>61</p>
<p>No solution.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N≤100,M≤10000</p>
<p>长度≤1000</p>
<p> </p>
</div>
</div>