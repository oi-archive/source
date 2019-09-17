# 题目描述


<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">给定平面上<span>n</span><span>个互不相交</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">指公共面积为零</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的正方形，它们的顶点坐标均为整数。设坐标原点为<span>O</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0, 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。对于任一正方形<span>R</span><span>，如果可以找到</span><span>R</span><span>的边上</span><span>2</span><span>个不同的点</span><span>A</span><span>和</span><span>B</span><span>，使三角形</span><span>OAB</span><span>的内部与其他正方形无公共点，则称正方形</span><span>R</span><span>是从</span><span>O</span><span>点可见的正方形。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">对于给定的<span>n</span><span>个互不相交的正方形，计算从坐标原点</span><span>O</span><span>可见的正方形个数。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入文件的第一行是正方形个数<span>n</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>≤</span><span>n</span><span>≤</span><span>1000</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来<span>n</span><span>行中，每行有</span><span>3</span><span>个表示正方形的整数</span><span>X</span><span>，</span><span>Y</span><span>，</span><span>L</span><span>。其中，</span><span>X</span><span>和</span><span>Y</span><span>表示正方形的左下角顶点坐标，</span><span>L</span><span>表示边长，</span><span>1</span><span>≤</span><span>X, Y, L</span><span>≤</span><span>10000</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出文件仅有一行包含一个整数，表示从坐标原点<span>O</span><span>可见的正方形个数。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">squares.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 6 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 4 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 4 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">squares.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<br/>
</p>
