# 题目描述


<p>
<br/>
</p>
<p class="MsoNormal" style="text-align:center;">
<span style="font-family:宋体;font-weight:bold;font-size:16.0000pt;">镜面通道</span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;color:#333333;font-size:12pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;color:#333333;font-weight:bold;font-size:12pt;">题目背景:</span><span style="font-family:宋体;color:#333333;font-weight:bold;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21.0000pt;">
<span style="font-family:宋体;color:#333333;font-size:12pt;">掩体纪元 5 年，星环公司宣布曲率驱动飞船计划，你奉命清理大型激光切割器的镜面通道。</span><span style="font-family:宋体;color:#333333;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21.0000pt;">
<span style="font-family:宋体;color:#333333;font-size:12pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-weight:bold;font-size:12.0000pt;">题目描述:</span><span style="font-family:宋体;font-weight:bold;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">在一个二维平面上，有一个镜面通道，由镜面AC，BD组成，AC，BD长度相等，且都平行于x轴，B位于(0, 0)。</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">通道中有n个外表面为镜面的光学元件，光学元件α为圆形，光学元件β为矩形(这些元件可以与其他元件和通道有交集，具体看下图)。</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">光线可以在AB上任一点以任意角度射入通道，光线不会发生削弱。当出现元件与元件，元件和通道刚好接触的情况视为光线无法透过(比如两圆相切)。现在给出通道中所有元件的信息(α元件包括圆心坐标和半径xi，yi，ri，β元件包括左下角和右上角坐标x1，y1，x2，y2)</span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<img src="http://www.lydsy.com/JudgeOnline/upload/201406/11(1).jpg" alt="" style="text-indent:21pt;font-family:宋体;"/> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">如上图，S到T便是一条合法线路。</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;"><img src="http://www.lydsy.com/JudgeOnline/upload/201406/22(1).jpg" alt=""/><br/>
</span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">当然，显然存在光线无法透过的情况，现在交给你一个艰巨的任务，请求出至少拿走多少个光学元件后，存在一条光线线路可以从CD射出。</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">下面举例说明：</span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<img src="http://www.lydsy.com/JudgeOnline/upload/201406/33.jpg" alt="" style="text-indent:21pt;"/> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">现在假设，取走中间那个矩形，那么就可以构造出一条穿过通道的光路，如图中的S到T。</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-weight:bold;font-size:12pt;">输入格式:</span><span style="font-family:宋体;font-weight:bold;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">第一行包含两个整数, x , y ,表示C点坐标。</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">第二行包含一个整数, n ，表示有n个光学元件。</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">接下来 n 行:</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">第一个数字 ti 表示这个元件的类型。</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">如果 ti = 1，表示元件α，后面会有三个整数xi，yi，ri分别表示圆心坐标和半径。</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-size:12pt;">如果 ti = 2，表示元件β，后面会有四个整数x1，y1，x2，y2分别表示左下角和右上角坐标（矩形都平行，垂直于坐标轴）</span><span style="font-family:宋体;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21pt;">
<span style="font-family:宋体;font-weight:bold;font-size:12pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-weight:bold;font-size:12pt;">输出格式:</span><span style="font-family:宋体;font-weight:bold;font-size:12pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21.0000pt;">
<span style="font-family:宋体;font-size:12.0000pt;">输出包含两行:</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21.0000pt;">
<span style="font-family:宋体;font-size:12.0000pt;">第一行一个整数，至少需要拿走的光学元件个数m。</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal" style="text-indent:21.0000pt;">
<span style="font-family:宋体;font-size:12.0000pt;">第二行，接下来 m 个数, 输出要拿走的光学元件的编号。如果有多组方案输出字典序最小的即可。</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-weight:bold;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-weight:bold;font-size:12.0000pt;">样例数据:</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<table class="MsoTableGrid" style="border-collapse:collapse;width:426.1000pt;">
<tbody>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="284">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">mirror.in</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="284">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">mirror.out</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="284">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1000 100</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">6</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1 500 0 50</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2 10 10 20 100</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2 100 10 200 100</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2 300 10 400 100</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2 500 10 600 100</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2 700 0 800 100</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="284">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1 6 </span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-weight:bold;font-size:12.0000pt;">数据范围及约定:</span><span style="font-family:宋体;font-size:10.5000pt;"></span> 
</p>
<table class="MsoTableGrid" style="border-collapse:collapse;width:426.1000pt;">
<tbody>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
<br/>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">N</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">ti</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">250</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">250</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">3</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">250</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">4</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">201</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">5</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">300</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">6</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">232</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">7</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">90</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">8</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">68</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">9</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">300</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">10</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">300</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">11</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">15</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">12</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">12</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">13</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">10</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">14</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">17</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">15</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">17</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">16</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">10</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">17</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">300</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">18</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">300</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">19</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">300</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
<tr>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">20</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">300</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
<td style="border:0.5000pt solid windowtext;" valign="top" width="189">
<p class="MsoNormal">
<span style="font-family:宋体;font-size:12.0000pt;">1,2</span><span style="font-family:宋体;font-size:12.0000pt;"></span> 
</p>
</td>
</tr>
</tbody>
</table>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:10.5000pt;"></span> 
</p>
<p class="MsoNormal">
<span style="font-family:宋体;font-size:10.5000pt;">保证</span><span style="font-family:宋体;font-size:10.5000pt;">给定点的坐标</span><span style="font-family:宋体;font-size:10.5000pt;">在矩形AB</span><span style="font-family:宋体;font-size:10.5000pt;">DC</span><span style="font-family:宋体;font-size:10.5000pt;">内(包括边界)</span><span style="font-family:宋体;font-size:10.5000pt;">。</span><span style="font-family:宋体;font-size:10.5000pt;"></span> 
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
