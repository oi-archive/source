# 题目描述


<p style="text-align:center;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">卫星照片(satel)</span> 
</p>
<p style="text-align:left;">
	<br/>
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">农夫 John 正在研究他的农场的卫星照片.照片为一个R (1 &lt;=</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">R &lt;= 75) 行  C (1 &lt;= C &lt;= 75) 列的字符矩阵表示.如下图:</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">..................</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">..#####.......##..</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">..#####......##...</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">..................</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">#.......###.....#.</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">#.....#####.......      </span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">图上的一块相连通的 &#34;#&#34; 表示一群奶牛或一个房间, 两个子&#34;#&#34; 连通的意思是说左右或上下相连.而下面的两块则是分开的:</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">....</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">.#..</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">..#.</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">....</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">John现在根据卫星照片上的的这些&#34;#&#34;块的形状来判断哪些是牛群,哪些是房间.如果一个&#34;#&#34;块形状的边是水平或垂直的矩形,则是房间.其它的则认为都是牛群.在第一个图中,有三个房间 ( 2x1, 2x5, and 1x1)和2群牛.</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">请根据输入文件中的数据,统计出房间数和牛群数.</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">数据中牛群不会包围另一个牛群或房间.</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入格式: satel.in</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">* 第一行,两个整数: R 和 C.</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">* 和 2..R+1行: 第 i+1 行表示照片的第 i 行情况,由 C 字符组成.</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出格式:</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">* 第一行: 房间数.</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">* 第二行: 牛群数.</span> 
</p>
<p style="text-align:left;">
	<br/>
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输入样例 (file satel.in):</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">5 8</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">#####..#</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">#####.##</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">......#.</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">.###...#</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">.###..##</span> 
</p>
<p style="text-align:left;">
	<br/>
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出样例 (file satel.out):</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span> 
</p>
<p style="text-align:left;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span> 
</p>
