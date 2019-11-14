<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Bessie透过牛棚的大门向外望去。发现今天是一个美丽的春季早晨。她想，“我真的好想好想沐浴著春风，走在草地之中，感受嫩草温柔地抚摸四蹄地的感觉。”她知道一旦她离开了牛棚，她将沿著一条小径走一段路，然后就会出现一个三岔路口，她必须在两条小径中选择一条继续走下去。然后她又会遇到更多的三岔路口，进行更多的选择，知道她到达一个青翠的牧场為止。</p>
<p>她决定坐一个选择使得她在去吃早草的路途中可以走过最多的小径。给你这些小径的描述，要求Bessie最多可以走过多少条小径。假定Bessie一出牛棚就有2条路径，Bessie需要从中选择一条。</p>
<p>农场中有P-1 (1 &lt;= P &lt;= 1,000) 个分岔节点（范围是1..P），引向P片草地，它们之间由小径连接。对任意一个节点来说，只有一条从牛棚（被标记為节点1）开始的路径可以到达。</p>
<p>考虑下面的图。线段表示小径，"%"表示草地。右边的图中的"#"表示一条到达草地的高亮的路径。</p>
<p> </p>
<p>从分岔节点9到达的草地是两个可以让Bessie走过最多小径的草地之一。在去吃早草的路上Bessie将走过7条不同的小径。这些草地是离牛棚也就是节点1最“远”的。</p>
<p>由3个整数来表示每一个节点：Cn, D1和D2，Cn是节点的编号(1 &lt;= Cn &lt;= P-1); D1和D2是由该节点引出的两条小径的终点(0 &lt;= D1 &lt;= P-1; 0 &lt;= D2 &lt;= P-1)。如果D1為0，表示这条小径引向的是一片牧草地；D2也一样。</p>

<img src="/source/codevs/codevs-2170/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yMTcwL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NzI5OTc4NS4zMTAuODc1NTM1NDcyMDE5LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>* 第1行: 一个单独的整数: P</p>
<p>* 第2到第P行: 第i+1行有3个由空格隔开的整数，表示一个分岔节点Cn, D1和D2。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>* 第一行: 一个单独的整数，表示Bessie去最远的草地的路上最多可以走过的小径的数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10<br>7 8 0<br>5 0 6<br>9 0 0<br>6 0 7<br>3 4 0<br>2 5 0<br>8 0 9<br>4 0 0<br>1 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1-2-5-6-7-8-9-P是最长的一条路径之一。</p>
</div>
</div>