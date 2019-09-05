# 题目描述


<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">题目背景：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">幻想乡的创始人之一，八云紫，有着强大的控制结界的能力，可以瞬间消除一定范围内所有弹幕。我们可以将其消除范围视为一个矩形，而弹幕可以视为动点。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">八云紫想要嘲讽她的敌人，所以她希望只使用一次消除能力，尽可能多地消除弹幕。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">请你告诉她，在哪一时刻使用道具，可以消除尽可能多的弹幕。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">问题描述：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">在平面上给定一个矩形区域<span>(</span>也可能退化成线段或者点<span>)</span>。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">矩形的边与坐标轴平行，左下端点为<span> (xl,yl)</span>，右上端点为<span> (xr,yr)</span>。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">给定<span> n </span>个动点，初始坐标为<span> (xi, yi)</span>，运动方向为<span> (ui,vi)</span>，速度为<span> sqrt((ui)^2+(vi)^2)</span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">求在哪一时刻<span> t (t ∈ N)</span>，在矩形内部及边界的动点数目最多。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">如果有多个<span> t </span>满足条件，输出最小的<span> t </span>即可。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">输入格式：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">第一行<span> 5 </span>个正整数，<span>n, xl, yl, xr, yr</span>，表示动点个数和矩形区域。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">接下来<span> n </span>行，每行<span> 4 </span>个整数，<span>xi, yi, ui, vi </span>，描述第<span> i </span>个动点。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">输出格式：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">        </span><span style="font-family:文泉驿微米黑;">在矩形内部及边界的动点数目最多的时刻<span> t (t ∈ N)</span>。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">如果有多个<span> t </span>满足条件，输出最小的<span> t </span>即可。<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">样例数据<span>1</span>：<span></span></span></b> 
</p>
<table class="MsoNormalTable ke-zeroborder" style="border-collapse:collapse;" border="0" cellpadding="0" cellspacing="0" width="643">
<tbody>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">camera.in</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">camera.out</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">2 2 2 3 3</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">3 1 -1 1</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">2 3 1 -1</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">1</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">样例数据<span>2</span>：<span></span></span></b> 
</p>
<table class="MsoNormalTable ke-zeroborder" style="border-collapse:collapse;" border="0" cellpadding="0" cellspacing="0" width="643">
<tbody>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">camera.in</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:文泉驿微米黑;">camera.out</span> 
</p>
</td>
</tr>
<tr>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">13
  44 68 49 73</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">40
  46 2 6</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">28
  75 4 -1</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">32
  61 3 3</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">41
  64 2 1</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">40
  99 2 -7</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">54
  49 -2 6</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">32
  80 4 -2</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">73
  99 -7 -7</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">23
  93 6 -5</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">44
  96 0 -6</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">36
  70 3 0</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">70
  98 -6 -7</span> 
</p>
<p class="TableContents">
<span style="font-family:&#34;">75
  53 -7 4</span> 
</p>
</td>
<td style="border:solid black 1.0pt;" valign="top" width="321">
<p class="TableContents">
<span style="font-family:&#34;">4</span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;"> </span></b> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;"> </span></b> 
</p>
<p class="Standard">
<b><span style="font-family:文泉驿微米黑;">数据范围：<span></span></span></b> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于前<span> 40% </span>数据，<span></span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       1&lt;=
n &lt;= 100, 1 &lt;= xl, xr, yl, yr, xi, yi &lt;= 100, -10 &lt;= ui, vi &lt;=
10</span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">对于<span>100% </span>数据<span>,</span></span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       1&lt;=
n &lt;= 10^5, 1 &lt;= xl, xr, yl, yr, xi, yi &lt;= 10^9, 0 &lt;= |ui|,
|vi|&lt;= 10^5, xl &lt;= xr, yl &lt;= yr</span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;"> </span> 
</p>
<p class="Standard">
<span style="font-family:文泉驿微米黑;">       </span><span style="font-family:文泉驿微米黑;">保证<span> n</span>，<span>xl</span>，<span>xr</span>，<span>yl</span>，<span>yr</span>，<span>xi</span>，<span>yi</span>，<span>ui</span>，<span>vi </span>均为整数<span>.</span></span> 
</p>
