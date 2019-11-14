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
一个序列的第1,3,5...项被称作奇数项，第2,4,6...项被称作偶数项。<br/>
一个序列A[1..n]被称作ZigZag序列当且仅当以下两个条件中的一个（或两个）成立：<br/>
1）除了首项，所有的奇数项都比它的前项小且所有的偶数项都比它的前项大。<br/>
2）除了首项，所有的奇数项都比它的前项大且所有的偶数项都比它的前项小。<br/>
一个序列A[1..n]被称作K凹凸序列当且仅当它的最长ZigZag子序列（不一定是连续子序列）的长度不超过K。<br/>
现在有一个序列A[1..n]，每次可以花费1的代价使得A中的某一项增加或减少1。我们的目的是花费最少的代价让它成为K凹凸序列。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
输入的第一行包含两个正整数，分别表示数列A[1..N]的长度N和K。<br/>
接下来的N行每行一个自然整数，依次表示数列的项。<br/>
前1个测试点满足：K=1，N≤20000<br/>
第2~8个测试点满足：K=2，N≤20000<br/>
第9~15个测试点满足：K=3，N≤20000<br/>
第16~20个测试点满足：K≤10，N≤1000<br/>
所有测试点满足：A[i]≤50000
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个整数，表示最小代价。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
9 3<br/>
1<br/>
2<br/>
3<br/>
6<br/>
9<br/>
8<br/>
7<br/>
4<br/>
5
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
1
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
把最后一项减小1，得到序列<br/>
1 2 3 6 9 8 7 4 4<br/>
它的最长ZigZag子序列之一是<br/>
1 9 4<br/>
长度为3，符合要求
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p style="margin:13pt 0cm;" class="NOI0">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;">【问题描述】</span><span lang="EN-US"><!--?xml:namespace prefix = o ns = "urn:schemas-microsoft-com:office:office" /--><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">一个序列的第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1,3,5...</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">项被称作奇数项，第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2,4,6...</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">项被称作偶数项。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">一个序列</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">A[1..n]</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">被称作</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">ZigZag</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">序列当且仅当以下两个条件中的一个（或两个）成立：</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">）除了首项，所有的奇数项都比它的前项小且所有的偶数项都比它的前项大。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">）除了首项，所有的奇数项都比它的前项大且所有的偶数项都比它的前项小。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">一个序列</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">A[1..n]</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">被称作</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">凹凸序列当且仅当它的<u>最长</u></span><u><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">ZigZag</span></span></u><u><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">子序列</span></u><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">（不一定是连续子序列）的长度<u>不超过</u></span><u><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K</span></span></u><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">现在有一个序列</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">A[1..n]</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，每次可以花费</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的代价使得</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">A</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">中的某一项增加或减少</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。我们的目的是花费最少的代价让它成为</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">凹凸序列。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI0">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;">【输入格式】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">输入的第一行包含两个正整数，分别表示数列</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">A[1..N]</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的长度</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">和</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">接下来的</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">行每行一个自然整数，依次表示数列的项。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">前</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个测试点满足：</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K=1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">≤</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">20000<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">2~8</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个测试点满足：</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K=2</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">≤</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">20000<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">9~15</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个测试点满足：</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K=3</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">≤</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">20000<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">16~20</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个测试点满足：</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">K</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">≤</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">10</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">N</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">≤</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1000<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">所有测试点满足：</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">A[i]</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">≤</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">50000<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI0">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;">【输出格式】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">输出一个整数，表示最小代价。</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI0">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;">【样例输入】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">9 3<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">1<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">2<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">3<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">6<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">9<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">8<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">7<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">4<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">5<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI0">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;">【样例输出】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI1">
<span lang="EN-US"><span style="font-family:&#39;Courier New&#39;;"><span style="font-size:small;">1<o:p></o:p></span></span></span> 
</p>
<p style="margin:13pt 0cm;" class="NOI0">
<strong><span style="font-size:small;"><span style="font-family:黑体;mso-ascii-font-family:Arial;">【样例说明】</span><span lang="EN-US"><o:p></o:p></span></span></strong> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">把最后一项减小</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，得到序列</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">1 2 3 6 9 8 7 4 4<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">它的最长</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">ZigZag</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">子序列之一是</span><span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"><span style="font-size:small;">1 9 4<o:p></o:p></span></span></span> 
</p>
<p style="margin:0cm 0cm 0pt;" class="NOI">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">长度为</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">3</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，符合要求</span></span><span lang="EN-US"><o:p></o:p></span> 
</p>
</div>
</div>
