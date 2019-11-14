<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">在一个地图上有N个地窖（N&lt;=20），每个地窖中埋有一定数量的地雷。同时，给出地窖之间的连接路径。当地窖及其连接的数据给出之后，某人可以从第一个地窖开始挖地雷，然后可以沿着指出的连接往下挖（仅能选择一条路径），当无连接时挖地雷工作结束。设计一个挖地雷的方案，使某人能挖到最多的地雷。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">输入文件mine.in有若干行。</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">第1行只有一个数字，表示地窖的个数N。</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">第2行有N个数，分别表示每个地窖中的地雷个数。</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">第3行至第N+1行表示地窖之间的连接情况：</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">第3行有n-1个数（0或1），表示第一个地窖至第2个、第3个、…、第n个地窖有否路径连接。如第3行为1 1 0 0 0 … 0，则表示第1个地窖至第2个地窖有路径，至第3个地窖有路径，至第4个地窖、第5个、…、第n个地窖没有路径。</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">第4行有n-2个数，表示第二个地窖至第3个、第4个、…、第n个地窖有否路径连接。</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">… …</p><p style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">第n+1行有1个数，表示第n-1个地窖至第n个地窖有否路径连接。（为0表示没有路径，为1表示有路径）。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="box-sizing: border-box; margin-top: 1.6rem; margin-bottom: 1.6rem; color: rgb(51, 51, 51); font-family: &#39;Segoe UI&#39;, &#39;Lucida Grande&#39;, Helvetica, Arial, &#39;Microsoft YaHei&#39;, FreeSans, Arimo, &#39;Droid Sans&#39;, &#39;wenquanyi micro hei&#39;, &#39;Hiragino Sans GB&#39;, &#39;Hiragino Sans GB W3&#39;, FontAwesome, sans-serif; font-size: 15px; line-height: 24px; white-space: normal;">输出文件wdl.out有两行数据。</p><p style="box-sizing: border-box; margin-top: 1.6rem; margin-bottom: 1.6rem; color: rgb(51, 51, 51); font-family: &#39;Segoe UI&#39;, &#39;Lucida Grande&#39;, Helvetica, Arial, &#39;Microsoft YaHei&#39;, FreeSans, Arimo, &#39;Droid Sans&#39;, &#39;wenquanyi micro hei&#39;, &#39;Hiragino Sans GB&#39;, &#39;Hiragino Sans GB W3&#39;, FontAwesome, sans-serif; font-size: 15px; line-height: 24px; white-space: normal;">第一行表示挖得最多地雷时的挖地雷的顺序，各地窖序号间以一个空格分隔，不得有多余的空格。</p><p style="box-sizing: border-box; margin-top: 1.6rem; margin-bottom: 1.6rem; color: rgb(51, 51, 51); font-family: &#39;Segoe UI&#39;, &#39;Lucida Grande&#39;, Helvetica, Arial, &#39;Microsoft YaHei&#39;, FreeSans, Arimo, &#39;Droid Sans&#39;, &#39;wenquanyi micro hei&#39;, &#39;Hiragino Sans GB&#39;, &#39;Hiragino Sans GB W3&#39;, FontAwesome, sans-serif; font-size: 15px; line-height: 24px; white-space: normal;">第二行只有一个数，表示能挖到的最多地雷数。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: Monaco, Menlo, Consolas, 'Courier New', FontAwesome, monospace;">5
10 8 4 7 6
1 1 1 0
0 0 0
1 1
1</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre style="font-family: Monaco, Menlo, Consolas, 'Courier New', FontAwesome, monospace;">1 3 4 5
27</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Segoe UI', 'Lucida Grande', Helvetica, Arial, 'Microsoft YaHei', FreeSans, Arimo, 'Droid Sans', 'wenquanyi micro hei', 'Hiragino Sans GB', 'Hiragino Sans GB W3', FontAwesome, sans-serif;">（N&lt;=20）</span></p>
</div>
</div>