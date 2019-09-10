# 题目描述


<p style="text-align:left;">
<span style="font-weight:bold;font-size:18.0000pt;font-family:&#39;宋体&#39;;">三．<span>mok</span></span><span style="font-weight:bold;font-size:18.0000pt;font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;">题目描述</span><span style="font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;text-align:left;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">N个杯子，第i个容量为Vi，一开始所有杯子装满水，每次可以</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:60.0000pt;text-indent:-18.0000pt;text-align:left;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">1) </span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">将一个杯子中的水倒掉。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:60.0000pt;text-indent:-18.0000pt;text-align:left;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">2) </span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">将杯子A中的水全部倒入杯子B（如果不会溢出的话）。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:60.0000pt;text-indent:-18.0000pt;text-align:left;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">3) </span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">用杯子A中部分的水填满杯子B（如果够的话）。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:21.0000pt;text-align:left;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">问能否通过若干次倒水得到目标状态。</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;">输入文件</span><span style="color:#000000;font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;text-align:left;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">第一行N</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"> </span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">表示杯子个数</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;text-align:left;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">第二行N个数 表示每个杯子的容量</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;text-align:left;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">第三行N个数 表示目标状态中每个杯子的水量</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;">输出文件</span><span style="color:#000000;font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;"> </span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">若可以，输出最少步数，否则输出NIE</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:left;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-align:left;">
<span style="font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;">样例输入</span><span style="font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">3</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">3 5 5</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">0 0 4</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;">样例输出</span><span style="font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">6</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
<span style="font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;">数据约定</span><span style="font-weight:bold;font-size:16.0000pt;font-family:&#39;幼圆&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;text-align:left;">
<span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;">100%：N&lt;=4，1&lt;=Vi&lt;=50</span><span style="color:#000000;font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
