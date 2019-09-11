# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<div style="margin:0cm -1.1pt 0pt 36.55pt;line-height:11.25pt;text-align:left;" align="left">
<span style="font-size:medium;"><span style="font-family:Arial;"><span style="color:black;">二维平面中，给定</span><i><span style="color:black;">   N</span></i><span style="color:black;">个等腰直角三角形（每个三角形的两条直角边分别</span></span></span> 
</div>
<div style="margin:0cm -1.1pt 0pt 36.55pt;line-height:11.25pt;text-align:left;" align="left">
</div>
<div style="margin:0cm -1.1pt 0pt 36.55pt;line-height:11.25pt;text-align:left;" align="left">
</div>
<div style="margin:0cm -1.1pt 0pt 36.55pt;line-height:11.25pt;text-align:left;" align="left">
<span style="font-size:medium;"><span style="font-family:Arial;"><span style="color:black;">平行于坐标轴，斜边从左上到右下）。我们用三个非负整数(<i> x</i>, <i>y</i>, <i>d</i>)来描</span></span></span> 
</div>
<div style="margin:0cm -1.1pt 0pt 36.55pt;line-height:11.25pt;text-align:left;" align="left">
</div>
<div style="margin:0cm -1.1pt 0pt 36.55pt;line-height:11.25pt;text-align:left;" align="left">
<span style="font-size:medium;"><span style="font-family:Arial;"><span style="color:black;">述这样一个三角形，三角形三个顶点的坐标</span></span></span> 
</div>
<div style="margin:0cm -1.1pt 0pt 36.55pt;line-height:11.25pt;text-align:left;" align="left">
</div>
<div style="margin:0cm -1.1pt 0pt 0cm;line-height:1pt;" align="left">
<span style="font-size:medium;"><span style="font-family:Arial;"><span style="color:black;"> </span></span></span> 
</div>
<div style="margin:0cm -1.1pt 0pt 15.55pt;line-height:11.25pt;text-align:left;" align="left">
<span style="font-size:medium;"><span style="font-family:Arial;"><span style="color:black;">分别为(<i>x</i>, <i>y</i>), (<i>x</i> + <i>d</i>, <i>y</i>)</span><span style="color:black;">和</span><span style="color:black;">(<i>x</i>, <i>y</i> + <i>    d</i>)</span><span style="color:black;">。要求计算这</span><i><span style="color:black;">   N</span></i><span style="color:black;">个三角形所覆盖的总面</span></span></span> 
</div>
<div style="margin:0cm -1.1pt 0pt 15.55pt;line-height:11.25pt;text-align:left;" align="left">
</div>
<p>
<span style="font-size:medium;"><span style="font-family:Arial;"><span style="color:black;">积。例如，下图有</span><span style="color:black;"> 3 个三角形，覆盖的总面积为 11.0。</span></span></span> 
</p>
<p>
<img src="http://www.lydsy.com/JudgeOnline/upload/201204/aa(4).jpg" alt=""/> 
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<div class="content">
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<span style="font-size:medium;"><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">输入文件第一行为一个正整数</span><i style="mso-bidi-font-style:normal;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span></i><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">，表示三角形的个数。接下来</span><span style="font-family:&#39;Times New Roman&#39;;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;mso-bidi-font-family:宋体;" lang="EN-US"><span style="mso-list:Ignore;">的 </span></span><i style="mso-bidi-font-style:normal;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US">N</span></i></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<br/>
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<span style="font-size:medium;"><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">行每行有用空格隔开的三个非负整数，</span><span style="font-family:&#39;Times New Roman&#39;;"><i style="mso-bidi-font-style:normal;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="mso-tab-count:1;">  </span>x</span></i><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US">, <i style="mso-bidi-font-style:normal;">y</i><span style="mso-tab-count:1;">   </span>, <i style="mso-bidi-font-style:normal;">d</i></span></span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">，描述一个三角</span></span> 
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<br/>
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<span style="font-size:medium;"><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">形的顶点坐标，分别为</span></span> 
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<br/>
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<span style="font-size:medium;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(<i style="mso-bidi-font-style:normal;"><span style="mso-tab-count:1;">    </span>x</i>, <i style="mso-bidi-font-style:normal;">y</i>), (<i style="mso-bidi-font-style:normal;">x</i> </span></span><span style="font-family:&#39;Times New Roman&#39;;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;mso-fareast-font-family:&#39;Times New Roman&#39;;" lang="EN-US"><span style="mso-list:Ignore;">+ </span></span><i style="mso-bidi-font-style:normal;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US">d</span></i><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US">, <i style="mso-bidi-font-style:normal;">y</i>), (<i style="mso-bidi-font-style:normal;"><span style="mso-tab-count:1;">  </span>x</i>, <i style="mso-bidi-font-style:normal;">y</i>+<i style="mso-bidi-font-style:normal;">d</i>)</span></span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">，</span></span> 
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<br/>
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<span style="font-size:medium;"><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">其中</span><span style="font-family:&#39;Times New Roman&#39;;"><i style="mso-bidi-font-style:normal;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="mso-tab-count:1;"> </span>x</span></i><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US">, <i style="mso-bidi-font-style:normal;">y</i>, <i style="mso-bidi-font-style:normal;">d</i><span style="mso-tab-count:1;"> </span></span></span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">满足</span><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">0≤<i style="mso-bidi-font-style:normal;"><span style="mso-tab-count:1;">   </span>x</i>, <i style="mso-bidi-font-style:normal;">y</i>, <i style="mso-bidi-font-style:normal;">d</i>≤1000000</span></span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">。</span></span> 
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<br/>
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<span style="font-size:medium;"><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">对于</span><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">50%</span></span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">的数据，</span><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1≤<i style="mso-bidi-font-style:normal;"><span style="mso-tab-count:1;">         </span>N</i>≤500</span></span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">；</span></span> 
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<br/>
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;mso-layout-grid-align:none;" align="left">
<span style="font-size:medium;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">100%</span></span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">的数</span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">据，</span><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1≤<i style="mso-bidi-font-style:normal;">N</i>≤10000</span></span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">。</span><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"> </span></span></span><span style="font-size:10pt;color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"><o:p></o:p></span></span> 
</p>
<p>
<span style="font-size:medium;"> </span> 
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="content">
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;tab-stops:238.4pt 243.45pt;mso-layout-grid-align:none;" align="left">
<span style="font-size:medium;"><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">仅包含一行，为一个实数</span><span style="font-family:&#39;Times New Roman&#39;;"><i style="mso-bidi-font-style:normal;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="mso-tab-count:1;">    </span>S</span></i><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="mso-tab-count:1;">    </span></span></span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">，表示所有三角形所覆盖的总面积，输出恰</span></span> 
</p>
<p class="MsoNormal" style="margin:0cm -1.1pt 0pt 35.95pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;tab-stops:238.4pt 243.45pt;mso-layout-grid-align:none;" align="left">
<br/>
</p>
<p class="MsoNormal" style="margin:0.75pt -1.1pt 0pt 15.55pt;line-height:11.25pt;text-align:left;mso-line-height-rule:exactly;tab-stops:163.3pt;mso-layout-grid-align:none;" align="left">
<span style="font-size:medium;"><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">好保留一位小数。输入数据保证</span><span style="font-family:&#39;Times New Roman&#39;;"><i style="mso-bidi-font-style:normal;"><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="mso-tab-count:1;">     </span>S</span></i><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US">≤2^31 </span></span><span style="color:black;font-family:宋体;mso-bidi-font-size:12.0pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">。</span><span style="color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"> </span></span></span><span style="font-size:10pt;color:black;mso-bidi-font-size:12.0pt;mso-font-kerning:0pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"><o:p></o:p></span></span> 
</p>
<p>
<br/>
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>3                                           .
  1  1 4
  2  0 2
  3  2 2
  </pre>
<h3>
【样例输出】
</h3>
<pre>  11.0
  </pre>
<h3>
【提示】
</h3>
<div class="content">
<p>
<br/>
</p>
</div>
<h3>
【来源】
</h3>
<div class="content">
<p>
<a href="problemset.php?search=day2">day2</a> 
</p>
</div>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=2731">耒阳大世界（衡阳八中） OJ 2731</a>
