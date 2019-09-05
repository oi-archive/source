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
BX正在进行一个字符串游戏，他手上有一个字符串L，以及其他一些字符串的集合S，然后他可以进行以下操作：对于一个在集合S中的字符串p,如果p在L中出现，BX就可以选择是否将其删除，如果删除，则将删除后L分裂成的左右两部分合并。<br/>
举个例子，L=&#39;abcdefg&#39; , S={&#39;de&#39;}，如果BX选择将&#39;de&#39;从L中删去，则删后的L=&#39;abcfg&#39;。<br/>
现在BX可以进行任意多次操作（删的次数，顺序都随意），他想知道最后L串的最短长度是多少。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含一个字符串，表示L。<br/>
第二行包含一个数字n，表示集合S中元素个数。<br/>
以下n行，每行一个字符串，表示S中的一个元素。<br/>
输入字符串都只包含小写字母。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个整数，表示L的最短长度。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
aaabccd<br/>
3<br/>
ac<br/>
abc<br/>
aaa
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
2
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
aaabccd<br/>
aacd<br/>
ad
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于40%数据，满足|L|&lt;9<br/>
对于100%数据,满足|L|&lt;151,|S|&lt;31,S中的每个元素|p|&lt;21
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【问题描述】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">        BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">正在进行一个字符串游戏，他手上有一个字符串</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，以及其他一些字符串的集合</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">S</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，然后他可以进行以下操作：对于一个在集合</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">S</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">中的字符串</span><span style="font-family:&#39;Times New Roman&#39;;"><i><span lang="EN-US">p</span></i><span lang="EN-US">,</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">如果</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">p</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">在</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">中出现，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">就可以选择是否将其删除，如果删除，则将删除后</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">分裂成的左右两部分合并。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    举个例子，</span><span style="font-family:&#39;Times New Roman&#39;;"><i><span lang="EN-US">L</span></i><span lang="EN-US">=&#39;abcdefg&#39; , <i>S</i>={&#39;de&#39;}</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，如果</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">选择将</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">&#39;de&#39;</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">从</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">中删去，则删后的</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L</span></span></i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">=&#39;abcfg&#39;</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    现在</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">BX</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">可以进行任意多次操作（删的次数，顺序都随意），他想知道最后</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">串的最短长度是多少。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【输入格式】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    输入的第一行包含一个字符串，表示</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    第二行包含一个数字</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，表示集合</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">S</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">中元素个数。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    以下</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行，每行一个字符串，表示</span><i><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">S</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">中的一个元素。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>输入字符串都只包含小写字母。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【输出格式】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>输出一个整数，表示</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">L</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的最短长度。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例输入】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>aaabccd<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-size:small;"><span style="font-family:&#39;Courier New&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>3<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>ac<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>abc<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>aaa<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例输出】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>2<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【样例说明】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-family:&#34;" lang="EN-US"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>aa<span style="color:red;">abc</span>cd<o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-family:&#34;" lang="EN-US"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>a<span style="color:red;">ac</span>d<o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-family:&#34;" lang="EN-US"><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>ad<o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span lang="EN-US"><o:p><span style="font-size:small;font-family:&#39;Times New Roman&#39;;"> </span></o:p></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;">【数据规模】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>对于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">40%</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">数据，满足</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">|<i>L</i>|&lt;9<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI0">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">    </span>对于</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">100%</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">数据</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">,</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">满足</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">|<i>L</i>|&lt;151,|<i>S</i>|&lt;31,S</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">中的每个元素</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">|<i>p</i>|&lt;21<o:p></o:p></span></span></span> 
</p>
</div>
</div>
