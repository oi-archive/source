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
在世界末日的前一天，所有神牛全部来到了一个矩形大广场上。这让你——一个相对还很弱小的同学感到透不过气来，因为神牛会产生看不到的气场，让人身心俱疲。具体的，每个神牛的控制区域都是一条线段(x1,y1)----(x2,y2)，两端点有可能相同，那样就变成了一个点。设你所在的位置为点P，如果可以过P做两条互相垂直的直线，使得这两条直线都与某一个或某两个神牛的控制区域有公共点，那么这个P点就是被气场覆盖的部分，这是你不想呆在的地方，你只想一个人静一静，于是，你想知道这个广场的安静系数的值。其中，安静系数=未被气场覆盖的面积/广场总面积。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含三个整数N,X,Y，分别表示神牛的个数，以及广场的长和宽。广场的区域范围为(0,0)~(X,Y).<br/>
接下来N行，每行有四个用空格隔开的非负整数x1,y1,x2,y2,表示该神牛的控制线段为(x1,y1)----(x2,y2)，其中，x1,x2在0到X之间，y1,y2在0到Y之间.
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个0到1之间的数，表示这个广场的安静系数，只要输出的答案和参考答案相差不超过0.005就算正确。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
1 2 2<br/>
0 1 2 1
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
0.214602
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
实际上，样例对应的气场覆盖的区域为以(1,1)为圆心的一个圆，面积为pi，而安静系数自然就等于(4-pi)/4=0.2146018…
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
25%的数据满足，N≤10;<br/>
另外15%的数据满足，除了一个神牛，其他的神牛的控制区域只是一个点;<br/>
100%的数据满足，N≤50，X≤10000，Y≤100.<br/>
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">【问题描述】</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">在世界末日的前一天，所有神牛全部来到了一个矩形大广场上。这让你——一个相对还很弱小的同学感到透不过气来，因为神牛会产生看不到的气场，让人身心俱疲。具体的，每个神牛的控制区域都是一条线段</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(x1,y1)----(x2,y2)</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，两端点有可能相同，那样就变成了一个点。设你所在的位置为点</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">P</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，如果可以过</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">P</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">做两条互相垂直的直线，使得这两条直线都与某一个或某两个神牛的控制区域有公共点，那么这个</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">P</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">点就是被气场覆盖的部分，这是你不想呆在的地方，你只想一个人静一静，于是，你想知道这个广场的安静系数的值。其中，安静系数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">=</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">未被气场覆盖的面积</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">/</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">广场总面积。</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">【输入格式】</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">输入的第一行包含三个整数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N,X,Y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，分别表示神牛的个数，以及广场的长和宽。广场的区域范围为</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(0,0)~(X,Y).</span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">接下来</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行，每行有四个用空格隔开的非负整数</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">x1,y1,x2,y2,</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">表示该神牛的控制线段为</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(x1,y1)----(x2,y2)</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，其中，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">x1,x2</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">在</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">0</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">到</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">X</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">之间，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">y1,y2</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">在</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">0</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">到</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Y</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">之间</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">.</span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">【输出格式】</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">输出一个</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">0</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">到</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">之间的数，表示这个广场的安静系数，只要输出的答案和参考答案相差不超过</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">0.005</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">就算正确。</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">【样例输入】</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">1 2 2</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">0 1 2 1</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">【样例输出】</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">0.214602</span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">【样例说明】</span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">实际上，样例对应的气场覆盖的区域为以</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(1,1)</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">为圆心的一个圆，面积为</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">pi</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，而安静系数自然就等于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">(4-pi)/4=0.2146018…</span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;"><span style="font-size:small;">【数据范围】<o:p></o:p></span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;mso-char-indent-count:2.0;" class="MsoNormal">
<span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">25%</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Courier New&#39;;mso-ansi-language:ZH-CN;">的数据满足，</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N≤10;<o:p></o:p></span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;mso-char-indent-count:2.0;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-style:italic;">另外</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">15%</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-style:italic;">的数据满足，除了一个神牛，其他的神牛的控制区域只是一个点</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">;<o:p></o:p></span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;mso-char-indent-count:2.0;" class="MsoNormal">
<span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">100%</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Courier New&#39;;mso-ansi-language:ZH-CN;">的数据满足，</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N≤50</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-style:italic;">，</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">X≤10000</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-style:italic;">，</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Y≤100. </span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;mso-char-indent-count:2.0;" class="MsoNormal">
<span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"><o:p>时限3s</o:p></span></span> 
</p>
<p style="text-indent:0cm;margin:0cm 0cm 0pt;mso-char-indent-count:0;" class="NOI0">
<span lang="EN-US"><o:p><span style="font-size:small;font-family:&#39;Times New Roman&#39;;"> </span></o:p></span> 
</p>
</div>
</div>
