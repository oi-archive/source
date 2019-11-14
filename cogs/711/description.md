# 题目描述


<p style="text-indent:21pt;">
	<span style="font-family:宋体;font-size:10.5pt;">现在我们在一个平面上画了<span>n</span>个矩形。每一个矩形的两边都与坐标轴相平行，且矩形定点的坐标均为整数。现我们定义满足如下性质的图形为一个块：<span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:21pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span>l<span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;">每一个矩形都是一个块；<span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:21pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span>l<span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;">如果两个块有一段公共的部分，那么这两个块就会形成一个新的块，否则这两个块就是不同的。<span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:21pt;">
	<span style="font-family:Wingdings;"><span>l<span> </span></span></span><span style="font-family:黑体;">示例：</span> 
</p>
<p>
	<br/>
<span style="font-family:宋体;font-size:10.5pt;">图<span>1</span>中的矩形形成了两个不同的块。图<span>2</span>中的矩形形成了一个块。</span> 
</p>
<p>
	<span style="font-family:黑体;"><img alt="" src="/cogs/images/upload/image/20120401/20120401083339_40420.bmp"/> <img alt="" src="/cogs/images/upload/image/20120401/20120401083543_60583.bmp"/></span> 
</p>
<p>
	<span style="font-family:黑体;">任务：</span><span></span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">请写一个程序：<span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:21pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span>l<span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;">从文本文件<span>recpro.in</span>中读入各个矩形的顶点坐标；<span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:21pt;">
	<span style="font-family:Wingdings;font-size:10.5pt;"><span>l<span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;">找出这些矩形中不同的块的数目；<span></span></span> 
</p>
<p style="text-indent:-21pt;margin-left:21pt;">
	<span style="font-family:Wingdings;"><span>l<span> </span></span></span><span style="font-family:宋体;font-size:10.5pt;">把结果输出到文本文件<span>recpro.out</span>中。</span> 
</p>
<p>
	<span style="font-family:黑体;">输入格式（<span>recpro.in</span></span><span style="font-family:宋体;font-size:10.5pt;">）</span><span style="font-family:黑体;">：</span><span></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:宋体;font-size:10.5pt;">文本文件<span>recpro.in</span>的第一行包括一个整数<span>n</span>，<span>1 </span></span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-family:宋体;font-size:10.5pt;"> n </span><span style="font-family:Symbol;font-size:10.5pt;"><span>£</span></span><span style="font-family:宋体;font-size:10.5pt;"> 7000</span><span style="font-family:宋体;font-size:10.5pt;">，为矩形的数目。以下的<span>n</span>行为矩形顶点的坐标。每一个矩形都是用四个整数来描述的：左下角的<span>x</span>坐标、左下角的<span>y</span>坐标、右上角的<span>x</span>坐标和右上角的<span>y</span>坐标。所有的坐标都是不大于<span>10000</span>的非负整数。<span></span></span> 
</p>
<p>
	<span style="font-family:黑体;">输出格式（<span>recpro.out</span></span><span style="font-family:宋体;font-size:10.5pt;">）</span><span style="font-family:黑体;">：</span><span></span> 
</p>
<p style="text-indent:21pt;">
	<span style="font-family:宋体;font-size:10.5pt;">在文本文件<span>recpro.out</span>中输出唯一的一个整数——这些矩形所形成的不同的块的数目。<span></span></span> 
</p>
<p>
	<span style="font-family:黑体;">样例：</span><span></span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">输入（<span>recpro.in</span>）：<span></span></span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">9</span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">0 3 2 6</span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">4 5 5 7</span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">4 2 6 4</span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">2 0 3 2</span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">5 3 6 4</span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">3 2 5 3</span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">1 4 4 7</span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">0 0 1 4</span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">0 0 4 1</span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">输出（<span>recpro.out</span>）：<span></span></span> 
</p>
<p>
	<span style="font-family:宋体;font-size:10.5pt;">2</span> 
</p>
