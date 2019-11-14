# 题目描述


<p style="text-indent:21.0000pt;">
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">给出一个简单多边形</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">没有缺口</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，它的边要么是垂直的，要么是水平的。要求计算多边形的面积。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">多边形被放置在一个<span>X</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">Y<span>的卡笛尔平面上，它所有的边都平行于两条坐标轴之一。然后按逆时针方向给出各顶点的坐标值。所有的坐标值都是整数</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">因此多边形的面积也为整数</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入文件第一行给出多边形的顶点数<span>n</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">n<span>≤</span><span>100</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。接下来的<span>n</span><span>行每行给出多边形一个顶点的坐标值</span><span>X</span><span>和</span><span>Y</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">都为整数并且用空格隔开</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。顶点按逆时针方向逐个给出。并且多边形的每一个顶点的坐标值</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">200<span>≤</span><span>x</span><span>，</span><span>y</span><span>≤</span><span>200</span><span>。多边形最后是靠从最后一个顶点到第一个顶点画一条边来封闭的。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出文件仅有一行，包含一个整数，表示多边形的面积。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">area.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">10</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">area.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">9</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<br/>
</p>
