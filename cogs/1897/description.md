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
利用空闲时间，BX希望外出工作，工作开始之前，公司就会给BX一个评估值X<sub>0</sub>，之后每天BX的评估值都是根据上一天的评估值和当天公司的运行状况得出，即X<sub>i</sub>=X<sub>i-1</sub>+D<sub>i</sub>,但是每天的评估值有一个上限，也就是说完整的评估公式因该是X<sub>i</sub>=min{X<sub>i-1</sub>+D<sub>i</sub>,L<sub>i</sub>}。<br/>
现在BX已经知道了该公司对自己的初始评估值X<sub>0</sub>、公司每天的运行状况Di、每天的评估上限Li，他的空闲时间是从第A天到第B天，他希望找到一段时间i，j (A≤i≤j≤B)，使得从第i天开始工作，到第j天结束后的评估值最大。当然如果任意一段时间的工作得到评估值都&lt;初始评估值X<sub>0</sub>，BX可以选择不工作，从而得到最大的评估值。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含两个整数N、M，分别表示总共工作天数和询问数。<br/>
第二行N个数，表示D<sub>i</sub>。<br/>
第三行N个数，表示L<sub>i</sub>。<br/>
以下M行，每行3个数A、B、X<sub>0</sub>，表示一次询问。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
M行，每行输出一个整数，表示评估的最大值
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
6 3<br/>
-6 5 3 2 -3 4<br/>
8 10 8 1 9 9<br/>
1 3 9<br/>
2 6 3<br/>
3 4 0
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
10<br/>
8<br/>
3
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于30%数据，满足N,M&lt;101<br/>
对于60%数据，满足N,M&lt;10001<br/>
对于100%数据,满足N,M&lt;50001,|D<sub>i</sub>|&lt;10001,0≤L<sub>i</sub>&lt;1000000001
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【问题描述】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    利用空闲时间，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">希望外出工作，工作开始之前，公司就会给</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">一个评估值</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">X<sub>0</sub></span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，之后每天</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的评估值都是根据上一天的评估值和当天公司的运行状况得出，即</span><span style="font-family:&#39;Times New Roman&#39;;"><i><span lang="EN-US">X<sub>i</sub></span></i><span lang="EN-US">=<i>X<sub>i-1</sub></i>+<i>D<sub>i</sub></i>,</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">但是每天的评估值有一个上限，也就是说完整的评估公式因该是</span><span style="font-family:&#39;Times New Roman&#39;;"><i><span lang="EN-US">X</span></i><sub><span lang="EN-US">i</span></sub><span lang="EN-US">=min{<i>X<sub>i-1</sub></i>+<i>D<sub>i</sub></i>,<i>L<sub>i</sub></i>}</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>现在</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">已经知道了该公司对自己的初始评估值</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">X<sub>0</sub></span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">、公司每天的运行状况</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Di</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">、每天的评估上限</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">Li</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，他的空闲时间是从第</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">A</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">天到第</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">B</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">天，他希望找到一段时间</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">i</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><span style="font-family:&#39;Times New Roman&#39;;"><i><span lang="EN-US">j</span></i><span lang="EN-US"> (<i>A</i>≤<i>i</i>≤<i>j</i>≤<i>B</i>)</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，使得从第</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">i</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">天开始工作，到第</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">j</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">天结束后的评估值最大。当然如果任意一段时间的工作得到评估值都</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">&lt;</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">初始评估值</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">X<sub>0</sub></span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">可以选择不工作，从而得到最大的评估值。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【输入格式】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>输入的第一行包含两个整数</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span></i><i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">、</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，分别表示总共工作天数和询问数。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>第二行</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个数，表示</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">D<sub>i</sub></span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>第三行</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个数，表示</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L<sub>i</sub></span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>以下</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行，每行</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">3</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个数</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">A</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">、</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">B</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">、</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">X<sub>0</sub></span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，表示一次询问。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【输出格式】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>M</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行，每行输出一个整数，表示评估的最大值</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例输入】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>6 3<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>-6 5 3 2 -3 4<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>8 10 8 1 9 9<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>1 3 9<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>2 6 3<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>3 4 0<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例输出】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>10<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>8<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>3<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【数据规模】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>对于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">30%</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">数据，满足</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span></i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">,<i>M</i>&lt;101<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>对于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">60%</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">数据，满足</span><span style="font-family:&#39;Times New Roman&#39;;"><i><span lang="EN-US">N</span></i><span lang="EN-US">,<i>M</i>&lt;10001<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>对于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">100%</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">数据</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">,</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">满足</span><span style="font-family:&#39;Times New Roman&#39;;"><i><span lang="EN-US">N</span></i><span lang="EN-US">,<i>M</i>&lt;50001,|<i>D<sub>i</sub></i>|&lt;10001,0≤<i>L<sub>i</sub></i>&lt;1000000001<o:p></o:p></span></span></span> 
</p>
</div>
</div>
