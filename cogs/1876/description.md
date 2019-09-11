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
有N个可爱的小猴子，有一天，妈妈摘了M个桃子，可是怎么分都分不平均。于是妈妈偷偷地把桃子藏了起来，准备第二天再想办法。可是孩子们到了晚上，纷纷去偷吃。第一只猴子去的时候发现把桃子分成N份相等的量，会剩下1（注：是数字1不是字母l，下同）个桃子，于是拿走了自己的一份，并把多余的1个桃子也拿走了。第二只猴子去的时候发现平分成N份时会剩下2个桃子，于是拿走了自己的一份，并把多余的2个桃子也拿走了……第K只猴子去的时候发现平分成N份时会剩下K个桃子，于是拿走了自己的一份，并把多余的K个桃子也拿走了，第K+1只猴子去的时候发现平分成N份后只剩下1个桃子，于是拿走了自己的一份，并拿走了多余的1个桃子，第K+2只猴子去的时候发现平分成N份后剩下2个桃子，于是拿走了自己的一份，并拿走了多余的2个桃子……如此K个一循环。第N个猴子去的时候，把剩下的桃子（至少一个）全都吃了。试问M至少是多少？<br/>
任务：输入正整数N，K（K&lt; N），求出最小的正整数M，桃子不能分割。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入仅包含一行，包括两个用空格隔开的正整数N，K.
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个正整数，表示最小的M，答案有可能超过2<sup>64</sup>.
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
4 3
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
73
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
30%的数据满足，0&lt;K&lt;N&lt;12;<br/>
另外15%的数据满足，K+1=N;<br/>
100%的数据满足，0&lt;K&lt;N&lt;100.<br/>
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">【问题描述】</span></span> 
</p>
<p style="text-indent:24.1pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">有</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个可爱的小猴子，有一天，妈妈摘了</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子，可是怎么分都分不平均。于是妈妈偷偷地把桃子藏了起来，准备第二天再想办法。可是孩子们到了晚上，纷纷去偷吃。第一只猴子去的时候发现把桃子分成</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">份相等的量，会剩下</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-style:italic;">（注：是数字</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-style:italic;">不是字母</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">l</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-style:italic;">，下同）</span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子，于是拿走了自己的一份，并把多余的</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子也拿走了。第二只猴子去的时候发现平分成</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">份时会剩下</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子，于是拿走了自己的一份，并把多余的</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子也拿走了</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">……</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">第</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">只猴子去的时候发现平分成</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">份时会剩下</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子，于是拿走了自己的一份，并把多余的</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子也拿走了，第</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K+1</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">只猴子去的时候发现平分成</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">份后只剩下</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子，于是拿走了自己的一份，并拿走了多余的</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子，第</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K+2</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">只猴子去的时候发现平分成</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">份后剩下</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子，于是拿走了自己的一份，并拿走了多余的</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个桃子</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">……</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">如此</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个一循环。第</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">个猴子去的时候，把剩下的桃子（至少一个）全都吃了。试问</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">至少是多少？</span><span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"> <o:p></o:p></span></span> 
</p>
<p style="text-indent:24.1pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">任务：输入正整数</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;mso-bidi-font-style:italic;">，</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">（</span><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US">K</span><span style="font-size:12pt;" lang="EN-US">&lt; <span style="mso-bidi-font-style:italic;">N</span></span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">），求出最小的正整数</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">，桃子不能分割。</span><span style="font-size:12pt;" lang="EN-US"><o:p></o:p></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;"><span style="font-size:small;">【输入格式】<o:p></o:p></span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">输入仅包含一行，包括两个用空格隔开的正整数</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;mso-bidi-font-style:italic;">，</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K.<o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;"><span style="font-size:small;">【输出格式】<o:p></o:p></span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;">输出一个正整数，表示最小的</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">M</span></span><span style="font-family:宋体;font-size:12pt;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;mso-bidi-font-style:italic;">，答案有可能超过</span><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US">2<sup>64</sup></span><span style="font-size:12pt;" lang="EN-US">.<o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:&#39;Courier New&#39;;mso-hansi-font-family:&#39;Courier New&#39;;mso-bidi-font-family:&#39;Courier New&#39;;mso-ansi-language:ZH-CN;">【样例输入】</span><span style="font-family:&#34;mso-ansi-language:ZH-CN;"><o:p></o:p></span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;mso-char-indent-count:2.0;" class="MsoNormal">
<span style="font-family:&#34;font-size:12pt;" lang="EN-US">4 3<o:p></o:p></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:&#39;Courier New&#39;;mso-hansi-font-family:&#39;Courier New&#39;;mso-bidi-font-family:&#39;Courier New&#39;;mso-ansi-language:ZH-CN;">【样例输出】</span><span style="font-family:&#34;mso-ansi-language:ZH-CN;"><o:p></o:p></span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;mso-char-indent-count:2.0;" class="MsoNormal">
<span style="font-family:&#34;font-size:12pt;" lang="EN-US">73<o:p></o:p></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI">
<span style="font-family:黑体;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-family:宋体;mso-ansi-language:ZH-CN;"><span style="font-size:small;">【数据范围】<o:p></o:p></span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;mso-char-indent-count:2.0;" class="MsoNormal">
<span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">30%</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:ZH-CN;">的数据满足，</span><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-size:12pt;mso-ansi-language:ZH-CN;">0&lt;</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US">K&lt;N&lt;12;<o:p></o:p></span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;mso-char-indent-count:2.0;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-style:italic;">另外</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">15%</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-bidi-font-style:italic;">的数据满足，</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K+1=N;<o:p></o:p></span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;mso-char-indent-count:2.0;" class="MsoNormal">
<span style="font-size:12pt;" lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">100%</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-ansi-language:ZH-CN;">的数据满足，</span><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-size:12pt;mso-ansi-language:ZH-CN;">0&lt;</span><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US">K&lt;N&lt;100.</span></span> 
</p>
<p style="text-indent:24pt;margin:0cm 0cm 0pt;mso-layout-grid-align:none;mso-char-indent-count:2.0;" class="MsoNormal">
<span style="font-family:&#39;Times New Roman&#39;;"><span style="font-size:12pt;mso-bidi-font-style:italic;" lang="EN-US"><o:p>时限1s</o:p></span></span> 
</p>
</div>
</div>
