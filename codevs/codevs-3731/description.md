<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在有向图G中，每条边的长度均为1，现给定起点和终点，请你在图中找一条从起点到终点的路径，该路径满足以下条件：</span></p><p style=""><span style="">1．路径上的所有点的出边所指向的点都直接或间接与终点连通。</span></p><p style=""><span style="">2．在满足条件1的情况下使路径最短。</span></p><p style=""><span style="">注意：图G中可能存在重边和自环，题目保证终点没有出边。</span></p><p style=""><span style="">请你输出符合条件的路径的长度。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行有两个用一个空格隔开的整数n和m，表示图有n个点和m条边。</span></p><p style=""><span style="">接下来的m行每行2个整数x、y，之间用一个空格隔开，表示有一条边从点x指向点y。</span></p><p style=""><span style="">最后一行有两个用一个空格隔开的整数s、t，表示起点为s，终点为t。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style=";font-family:宋体;font-size:14px">输出文件名为road.out。</span></p><p style="text-indent: 28px;"><span style=";font-family:宋体;font-size:14px">输出只有一行，包含一个整数，表示满足题目</span><span style=";font-family:宋体;font-size:14px">描</span><span style=";font-family:宋体;font-size:14px">述的最短路径的长度。如果这样的路径不存在，输出-1。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<table width="553"><tbody><tr><td style="" valign="top" width="277"><p style=""><span style="">road.in</span></p></td><td style="" valign="top" width="277"><p style=""><span style="">road.out</span></p></td></tr><tr style=""><td style="" valign="top" width="277"><p><span style="">3 2</span></p><p><span style="">1 2</span></p><p><span style="">2 1</span></p><p><span style="">1 3</span></p></td><td style="" valign="top" width="277"><p><span style="">－1</span></p></td></tr></tbody></table><p><img height="332" src="/source/codevs/codevs-3731/img/aHR0cDovL3d3dy5qb3lvaS5jbi9tZWRpYS9ibG9iXzIwMTUwNTAyMTcwNjI0XzMzOS5wbmc=.png" style="" title="" width="657"></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<table width="553"><tbody><tr><td style="" valign="top" width="277"><p style=""><span style="">road.in</span></p></td><td style="" valign="top" width="277"><p style=""><span style="">road.out</span></p></td></tr><tr style=""><td style="" valign="top" width="277"><p><span style="">6 6</span></p><p><span style="">1 2</span></p><p><span style="">1 3</span></p><p><span style="">2 6</span></p><p><span style="">2 5</span></p><p><span style="">4 5</span></p><p><span style="">3 4</span></p><p><span style="">1 5</span></p></td><td style="" valign="top" width="277"><p><span style="">3</span></p></td></tr></tbody></table><p><img src="/source/codevs/codevs-3731/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zNzMxL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvYmxvYl8yMDE1MDUwMjE3MDcyOV80MzkucG5n.png" title=""></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于30%的数据，0</span><span style="">&lt; n </span><span style="">≤</span><span style="">10，0&lt;</span><span style=""> m </span><span style="">≤</span><span style="">20；</span></p><p style=""><span style="">对于60%的数据，0&lt;</span><span style=""> n </span><span style="">≤</span><span style="">100，0&lt;</span><span style=""> m </span><span style="">≤</span><span style="">2000；</span></p><p style=""><span style="">对于100%的数据，0&lt;</span><span style=""> n </span><span style="">≤</span><span style="">10,000，0&lt;</span><span style=""> m </span><span style="">≤</span><span style="">200,000，0&lt;</span><span style=""> x</span><span style="">,</span><span style="">y,s,t≤n，x≠t。</span></p><p><br></p>
</div>
</div>