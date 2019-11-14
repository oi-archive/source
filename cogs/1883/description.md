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
为了提高自己的实力，gx想要制定一个合理的刷题计划。这里我们用实数来表示题目的难度，并且把刷题计划中由题目难度组成的序列称为刷题序列。gx刷题最喜欢循序渐进的方式，最理想的情况莫过于刷题序列是个等差数列了。但是这很难做到，于是我们定义一个刷题序列a的偏离值 <img src="/upload/image/20141217/20141217082132_92470.png" alt=""/>，其中L是给定的一个常数。<br/>
现在gx的老师已经布置给了他n道必做题，同时他还有空余时间从OJ上找m道题目来刷。他不希望改变这n道必做题的相对顺序，但是选做题的难度以及在数列中的位置都是任意的（OJ上的题目太多了，随你怎么挑）。<br/>
gx希望你帮他设计一个刷题序列，使得该序列的偏离值最小。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含三个数：n, m, L。n是整数，表示必做题有n道，m是整数，表示选做题有m道，L是实数。第二行包含n个实数，依次表示每道必做题的难度。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个实数，表示最小的偏离值。保留三位小数。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
4 3 1.0<br/>
1 4 5 3
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
8.000
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
将原序列(1,4,5,3)变成(1,2,3,4,5,4,3)，偏离值为8.00。
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于30%的数据 n≤500, m≤200<br/>
对于70%的数据 n≤20000, m≤100000<br/>
对于100%的数据 1≤n≤50000, 1≤m≤100000000, -100≤L≤100, |a<sub>i</sub>|≤100<br/>
均匀分布着50%的数据 L=0
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【问题描述】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"> 为了提高自己的实力，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">想要制定一个合理的刷题计划。这里我们用实数来表示题目的难度，并且把刷题计划中由题目难度组成的序列称为刷题序列。</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">刷题最喜欢循序渐进的方式，最理想的情况莫过于刷题序列是个等差数列了。但是这很难做到，于是我们定义一个刷题序列</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">a</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的偏离值</span></span><span lang="EN-US"><span style="position:relative;top:14pt;mso-text-raise:-14.0pt;"><v:shapetype id="_x0000_t75" coordsize="21600,21600" o:spt="75" o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe" filled="f" stroked="f"><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;"> <img width="175" height="50" alt="" src="/RequireFile.do?fid=82LtAb52"/><v:stroke joinstyle="miter"></v:stroke><v:formulas><v:f eqn="if lineDrawn pixelLineWidth 0"></v:f><v:f eqn="sum @0 1 0"></v:f><v:f eqn="sum 0 0 @1"></v:f><v:f eqn="prod @2 1 2"></v:f><v:f eqn="prod @3 21600 pixelWidth"></v:f><v:f eqn="prod @3 21600 pixelHeight"></v:f><v:f eqn="sum @0 0 1"></v:f><v:f eqn="prod @6 1 2"></v:f><v:f eqn="prod @7 21600 pixelWidth"></v:f><v:f eqn="sum @8 21600 0"></v:f><v:f eqn="prod @7 21600 pixelHeight"></v:f><v:f eqn="sum @10 21600 0"></v:f></v:formulas><v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"></v:path><o:lock v:ext="edit" aspectratio="t"></o:lock></span></span></v:shapetype></span></span><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，其中</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">是给定的一个常数。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"> 现在</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的老师已经布置给了他</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">道必做题，同时他还有空余时间从</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">OJ</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">上找</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">m</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">道题目来刷。他不希望改变这</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">道必做题的相对顺序，但是选做题的难度以及在数列中的位置都是任意的（</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">OJ</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">上的题目太多了，随你怎么挑）。</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"> gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">希望你帮他设计一个刷题序列，使得该序列的偏离值最小。</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【输入格式】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"> 输入的第一行包含三个数：</span><span style="font-family:&#39;Times New Roman&#39;;"><i style="mso-bidi-font-style:normal;"><span lang="EN-US">n</span></i><span lang="EN-US">, <i style="mso-bidi-font-style:normal;">m</i>, <i style="mso-bidi-font-style:normal;">L</i></span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">是整数，表示必做题有</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">道，</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">m</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">是整数，表示选做题有</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">m</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">道，</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">是实数。第二行包含</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个实数，依次表示每道必做题的难度。</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【输出格式】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;"> 输出一个实数，表示最小的偏离值。保留三位小数。</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【样例输入】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI2">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">4 3 1.0</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI2">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">1 4 5 3</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【样例输出】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI2">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">8.000</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【样例说明】</span></strong></span> 
</p>
<p style="text-indent:21pt;margin:0cm 0cm 0pt;mso-char-indent-count:0;" class="NOI1">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:&#39;Times New Roman&#39;;">将原序列</span><span style="font-family:&#34;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">(1,4,5,3)</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:&#39;Times New Roman&#39;;">变成</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US">(1,2,3,4,5,4,3)</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:&#39;Times New Roman&#39;;">，偏离值为</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US">8.00</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【数据范围】</span></strong></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;mso-bidi-font-family:&#39;Courier New&#39;;">对于</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">30%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;mso-bidi-font-family:&#39;Courier New&#39;;">的数据</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US"> n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">500, m</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">200<o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;mso-bidi-font-family:&#39;Courier New&#39;;">对于</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">70%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;mso-bidi-font-family:&#39;Courier New&#39;;">的数据</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US"> n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">20000, m</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">100000<o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;mso-bidi-font-family:&#39;Courier New&#39;;">对于</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">100%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;mso-bidi-font-family:&#39;Courier New&#39;;">的数据</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US"> 1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">50000, 1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">m</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">100000000, -100</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">L</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">100, |<i style="mso-bidi-font-style:normal;">a</i><sub>i</sub>|</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;" lang="EN-US">100</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;mso-bidi-font-family:&#39;Courier New&#39;;">均匀分布着</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US">50%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;mso-bidi-font-family:&#39;Courier New&#39;;">的数据</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Courier New&#39;;" lang="EN-US"> L=0<o:p></o:p></span></span> 
</p>
<p>
 
</p>
</div>
</div>
