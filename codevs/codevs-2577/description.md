<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>设有一棵二叉树,如下图</p>
<p>其中,圈中数字表示结点居民的人口.圈边上数字表示结点编号,.现在要求在某个结点上建立一个医院,使所有居民所走的路程之和为最小,同时约定,相邻结点之间 的距离为1.如上图中,若医院建在:</p>
<p>1处：则距离之和=4+12+2*20+2*40=136</p>
<p>3处：则距离之和=4*2+13+20+40=81</p>
<p>…….</p>

<img src="/source/codevs/codevs-2577/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yNTc3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2ODUyMzY4NC40NzAuNDc2MjQ2NzMxNjE1LlBORw==.PNG" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n，表示树的结点数。（n&lt;=100）</p>
<p>接下来的n行每行描述了一个结点的状况，包含三个整数，整数之间用空格（一个或多个）分隔，其中：第一个数为居民人口数；第二个数为左链接，为0表示表链接；第三个数为右链接。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数，表示最小距离和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>13 2 3</p>
<p>4 0 0</p>
<p>12 4 5</p>
<p>20 0 0</p>
<p>40 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>81</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>无</p>
</div>
</div>