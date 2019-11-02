<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">    </span><span style="">农夫 John 正在研究他的农场的卫星照片.照片为一个R行C 列的字符矩阵表示。如下图:</span></p><p style=""><span style="">..................</span></p><p style=""><span style="">..#####.......##..</span></p><p style=""><span style="">..#####......##...</span></p><p style=""><span style="">..................</span></p><p style=""><span style="">#.......###.....#.</span></p><p style=""><span style="">#.....#####.......      </span></p><p style=""><span style="">    </span><span style="">图上的一块相连通的 "#" 表示一群奶牛或一个房间, 两个子"#" 连通的意思是说左右或上下相连。而下面的两块则是分开的:</span></p><p style=""><span style="">....</span></p><p style=""><span style="">.#..</span></p><p style=""><span style="">..#.</span></p><p style=""><span style="">....</span></p><p style=""><span style="">    </span><span style="">John</span><span style="">现在根据卫星照片上的的这些"#"块的形状来判断哪些是牛群，哪些是房间。如果矩形内只有‘#’，则是房间。其它的则认为都是牛群。在第一个图中,有三个房间 ( 2x1, 2x5, and 1x1)和2群牛。</span></p><p style=""><span style="">    </span><span style="">根据输入文件的数据，统计出房间数和牛群数，数据中牛群不会包围另一个牛群或房间。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行,两个整数: R 和 C.</span></p><p style=""><span style="">和 2..R+1行: 第 i+1 行表示照片的第 i 行情况，由 C 字符组成。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="line-height: 19px"><span style="font-family:宋体">第一行: 房间数。</span></p><p style="line-height: 19px"><span style="font-family:宋体">第二行: 牛群数。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">5 8</span></p><p style=""><span style="">#####..#</span></p><p style=""><span style="">#####.##</span></p><p style=""><span style="">......#.</span></p><p style=""><span style="">.###...#</span></p><p style=""><span style="">.###..##</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">2</span></p><p style=""><span style="">2</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">(1&lt;= R &lt;= 75)</span></p><p><span style=""><span style="">(1&lt;=C&lt;=75)</span></span></p>
</div>
</div>