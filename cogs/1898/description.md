# 题目描述


<div class="content">
<!--begin main-->
<!-- InstanceBeginEditable name="content" -->
<h3>
【试题来源】
</h3>
<div id="psrc" style="margin-top:20px;display:block;">
<div class="pdcont">
2011中国国家集训队命题答辩
</div>
</div>
<div id="pinputs" style="display:none;">
<div class="pdsec">
输入数据
</div>
<div class="pdcont">
<span class="notice"> 这是一道提交答案的试题，下面给出了该题的输入数据：</span> 
</div>
<div id="inputlist" class="pddata">
</div>
</div>
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
BX建了一个新家，家建在一个格点平面上（即平面被划分成单位格子），形成一个简单多边形。BX在看了家的设计图纸后，希望统计他的实际居住面积是多少。BX的实际居住面积是以单位格子进行统计的，也就是说，如果一个格子完整在家内（可以与边界相接），才会被算到居住面积内。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含一个整数n，分别表示多边形的点数。<br/>
以下n行，每行两个数x，y表示一个点的坐标。<br/>
点以顺时针（或逆时针）顺序读入。<br/>
数据保证多边形是简单多边形。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个整数，表示实际居住面积。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
6<br/>
2 2<br/>
4 8<br/>
8 6<br/>
10 8<br/>
11 2<br/>
5 4
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
18
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
<img src="/upload/image/20141222/20141222141931_39348.png" alt=""/> 
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于30%数据，n,|X|,|Y|&lt;101<br/>
对于50%数据，n,|X|,|Y|&lt;1001<br/>
对于100%数据,n&lt;1001,|X|,|Y|&lt;100000000
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【问题描述】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">建了一个新家，家建在一个格点平面上（即平面被划分成单位格子），形成一个简单多边形。</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">在看了家的设计图纸后，希望统计他的实际居住面积是多少。</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的实际居住面积是以单位格子进行统计的，也就是说，如果一个格子完整在家内（可以与边界相接），才会被算到居住面积内。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【输入格式】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>输入的第一行包含一个整数</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，分别表示多边形的点数。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>以下</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行，每行两个数</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">x</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">表示一个点的坐标。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>点以顺时针（或逆时针）顺序读入。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>数据保证多边形是简单多边形。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【输出格式】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>输出一个整数，表示实际居住面积。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例输入】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>6<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>2 2<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>4 8<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>8 6<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>10 8<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>11 2<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>5 4<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><o:p><span style="font-size:small;font-family:&#39;Courier New&#39;;"> </span></o:p></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例输出】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>18<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例说明】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span lang="EN-US"><v:shapetype id="_x0000_t75" stroked="f" filled="f" path="m@4@5l@4@11@9@11@9@5xe" o:preferrelative="t" o:spt="75" coordsize="21600,21600"><v:stroke joinstyle="miter"></v:stroke><v:formulas><v:f eqn="if lineDrawn pixelLineWidth 0"></v:f><v:f eqn="sum @0 1 0"></v:f><v:f eqn="sum 0 0 @1"></v:f><v:f eqn="prod @2 1 2"></v:f><v:f eqn="prod @3 21600 pixelWidth"></v:f><v:f eqn="prod @3 21600 pixelHeight"></v:f><v:f eqn="sum @0 0 1"></v:f><v:f eqn="prod @6 1 2"></v:f><v:f eqn="prod @7 21600 pixelWidth"></v:f><v:f eqn="sum @8 21600 0"></v:f><v:f eqn="prod @7 21600 pixelHeight"></v:f><v:f eqn="sum @10 21600 0"></v:f></v:formulas><v:path o:connecttype="rect" gradientshapeok="t" o:extrusionok="f"></v:path><o:lock aspectratio="t" v:ext="edit"></o:lock></v:shapetype><span style="font-family:&#34;font-size:10.5pt;mso-bidi-font-size:10.0pt;mso-fareast-font-family:宋体;mso-font-kerning:1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;" lang="EN-US"><v:shapetype id="_x0000_t75" stroked="f" filled="f" path="m@4@5l@4@11@9@11@9@5xe" o:preferrelative="t" o:spt="75" coordsize="21600,21600"> <span style="font-family:&#34;font-size:10.5pt;mso-bidi-font-size:10.0pt;mso-fareast-font-family:宋体;mso-font-kerning:1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;" lang="EN-US"><v:shapetype id="_x0000_t75" stroked="f" filled="f" path="m@4@5l@4@11@9@11@9@5xe" o:preferrelative="t" o:spt="75" coordsize="21600,21600"> <img alt="" src="/RequireFile.do?fid=5hfT3jqN" height="278" width="383"/><v:stroke joinstyle="miter"></v:stroke><v:formulas><v:f eqn="if lineDrawn pixelLineWidth 0"></v:f><v:f eqn="sum @0 1 0"></v:f><v:f eqn="sum 0 0 @1"></v:f><v:f eqn="prod @2 1 2"></v:f><v:f eqn="prod @3 21600 pixelWidth"></v:f><v:f eqn="prod @3 21600 pixelHeight"></v:f><v:f eqn="sum @0 0 1"></v:f><v:f eqn="prod @6 1 2"></v:f><v:f eqn="prod @7 21600 pixelWidth"></v:f><v:f eqn="sum @8 21600 0"></v:f><v:f eqn="prod @7 21600 pixelHeight"></v:f><v:f eqn="sum @10 21600 0"></v:f></v:formulas><v:path o:connecttype="rect" gradientshapeok="t" o:extrusionok="f"></v:path><o:lock aspectratio="t" v:ext="edit"></o:lock></v:shapetype></span></v:shapetype></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【数据规模】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>对于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">30%</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">数据，</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">,|<i>X</i>|,|<i>Y</i>|&lt;101<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>对于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">50%</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">数据，</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">,|<i>X</i>|,|<i>Y</i>|&lt;1001<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">       </span></span>对于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">100%</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">数据</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">,<i>n</i>&lt;1001,|<i>X</i>|,|<i>Y</i>|&lt;100000000<o:p></o:p></span></span></span> 
</p>
</div>
</div>
