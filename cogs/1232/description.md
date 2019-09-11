# 题目描述


<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">司令部的助理经常需要在大纸上切割各种形状的孔。他们刚刚购买了一台新的切孔机，该机比他们以前使用的要方便自由的多。他们想编写一个程序来求出经过一系列复杂的切孔后会发生什么情况，他们特别想知道纸上形成的孔的数量。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">下图列出了经过切割后形成的一些图样。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<img src="/upload/image/20121026/20121026142607_87702.png" width="100%" alt=""/> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入文件第一行是一个整数<span>N</span><span>，表示切纸操作的次数，</span><span>1</span><span>≤</span><span>N</span><span>≤</span><span>100</span><span>。接下来的</span><span>N</span><span>行中每行给出一个精确的切割操作，每次切割都给出了用空格隔开的四个整数，</span><span>x</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>y</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>x</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>y</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1000<span>≤</span><span>x</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>y</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>x</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>y</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">≤<span>1000</span><span>。</span><span>x</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">和<span>y</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">是切割线开始处的坐标值，<span>x</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">和<span>y</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">是切割线结束时的坐标值。你可以假设所有的切割点都在纸上，不会出界。每次切割都平行于纸上的<span>x</span><span>和</span><span>y</span><span>坐标轴。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">对于每次切割操作，要求输出纸上留下的单独的孔数。注意任何孔的最小面积不低于<span>1</span><span>平方单位。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">cutter.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 1 1 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 1 1 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 0 0 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0 0 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">cutter.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<br/>
</p>
