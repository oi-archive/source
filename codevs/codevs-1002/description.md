<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一矩形区域的城市中建筑了若干建筑物，如果某两个单元格有一个点相联系，则它们属于同一座建筑物。现在想在这些建筑物之间搭建一些桥梁，其中桥梁只能沿着矩形的方格的边沿搭建，如下图城市1有5栋建筑物，可以搭建4座桥将建筑物联系起来。城市2有两座建筑物，但不能搭建桥梁将它们连接。城市3只有一座建筑物，城市4有3座建筑物，可以搭建一座桥梁联系两栋建筑物，但不能与第三座建筑物联系在一起。</p>

<img src="/source/codevs/codevs-1002/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMDAyL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMDAyLmdpZg==.gif" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>在输入的数据中的第一行包含描述城市的两个整数<em>r</em> 和<em>c,</em> 分别代表从北到南、从东到西的城市大小(1 &lt;= <em>r </em>&lt;= 50 and 1 &lt;= <em> c</em><em> </em>&lt;= 50). 接下来的<em>r</em> 行, 每一行由<em>c </em>个(“#”)和(“.”)组成的字符. 每一个字符表示一个单元格。“#”表示建筑物，“.”表示空地。</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>在输出的数据中有两行，第一行表示建筑物的数目。第二行输出桥的数目和所有桥的总长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">样例1</span></p>
<p>3 5</p>
<p>#...#</p>
<p>..#..</p>
<p>#...#</p>
<p> </p>
<p>样例2</p>
<p>3 5</p>
<p>##...</p>
<p>.....</p>
<p>....#</p>
<p> </p>
<p>样例3</p>
<p>3 5</p>
<p>#.###</p>
<p>#.#.#</p>
<p>###.#</p>
<p> </p>
<p>样例4:</p>
<p>3 5</p>
<p>#.#..</p>
<p>.....</p>
<p>....#</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">样例1</span></p>
<p>5</p>
<p>4 4</p>
<p> </p>
<p>样例2</p>
<p>2</p>
<p>0 0</p>
<p> </p>
<p>样例3</p>
<p>1</p>
<p>0 0</p>
<p> </p>
<p>样例4</p>
<p>3</p>
<p>1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>