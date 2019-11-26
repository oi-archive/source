<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>“余”人国的国王想重新编制他的国家。他想把他的国家划分成若干个省，每个省都由他们王室联邦的一个成员来管理。</p>
<p>他的国家有n个城市，编号为1..n。一些城市之间有道路相连，任意两个不同的城市之间有且仅有一条直接或间接的道路。为了防止管理太过分散，每个省至少要有B个城市，为了能有效的管理，每个省最多只有3B个城市。</p>
<p>每个省必须有一个省会，这个省会可以位于省内，也可以在该省外。但是该省的任意一个城市到达省会所经过的道路上的城市（除了最后一个城市，即该省省会）都必须属于该省。</p>
<p>一个城市可以作为多个省的省会。</p>
<p>聪明的你快帮帮这个国王吧！</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个数N，B（1&lt;=N&lt;=1000, 1 &lt;= B &lt;= N）。接下来N－1行，每行描述一条边，包含两个数，即这条边连接的两个城市的编号。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果无法满足国王的要求，输出0。否则第一行输出数K，表示你给出的划分方案中省的个数，编号为1..K。第二行输出N个数，第I个数表示编号为I的城市属于的省的编号，第三行输出K个数，表示这K个省的省会的城市编号，如果有多种方案，你可以输出任意一种。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>8 2 <br> 1 2 <br> 2 3 <br> 1 8 <br> 8 7 <br> 8 6 <br> 4 6 <br> 6 5 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3 <br> 2 1 1 3 3 3 3 2 <br> 2 1 8 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>