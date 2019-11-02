<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: arial, verdana, helvetica, sans-serif;">发生了火警，所有人员需要紧急疏散！假设每个房间是一个N M的矩形区域。每个格子如果是'.'，那么表示这是一块空地；如果是'X'，那么表示这是一面墙，如果是'D'，那么表示这是一扇门，人们可以从这儿撤出房间。已知门一定在房间的边界上，并且边界上不会有空地。最初，每块空地上都有一个人，在疏散的时候，每一秒钟每个人都可以向上下左右四个方向移动一格，当然他也可以站着不动。疏散开始后，每块空地上就没有人数限制了（也就是说每块空地可以同时站无数个人）。但是，由于门很窄，每一秒钟只能有一个人移动到门的位置，一旦移动到门的位置，就表示他已经安全撤离了。现在的问题是：如果希望所有的人安全撤离，最短需要多少时间？或者告知根本不可能。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: arial, verdana, helvetica, sans-serif;">输入文件第一行是由空格隔开的一对正整数N与M，3&lt;=N &lt;=20，3&lt;=M&lt;=20，以下N行M列描述一个N M的矩阵。其中的元素可为字符'.'、'X'和'D'，且字符间无空格。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一个整数K，表示让所有人安全撤离的最短时间，如果不可能撤离，那么输出&#39;impossible&#39;（不包括引号）.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">5 5  </span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">XXXXX</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">X...D</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">XX.XX</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">X..XX</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">XXDXX</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="font-family: arial, verdana, helvetica, sans-serif;">3&lt;=N &lt;=20，3&lt;=M&lt;=20</span></span><br></p>
</div>
</div>