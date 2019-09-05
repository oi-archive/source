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
<div id="pcont1" style="margin-top:20px;display:block;">
<h3>
【问题描述】
</h3>
<div class="pdcont">
gx和lc去参加noip初赛，其中有一种题型叫单项选择题，顾名思义，只有一个选项是正确答案。试卷上共有n道单选题，第i道单选题有a<sub>i</sub>个选项，这a<sub>i</sub>个选项编号是1,2,3,…,a<sub>i</sub>，每个选项成为正确答案的概率都是相等的。lc采取的策略是每道题目随机写上1-a<sub>i</sub>的某个数作为答案选项，他用不了多少时间就能期望做对<img alt="" src="/upload/image/20141217/20141217083227_81009.png"/>道题目。gx则是认认真真地做完了这n道题目，可是等他做完的时候时间也所剩无几了，于是他匆忙地把答案抄到答题纸上，没想到抄错位了：第i道题目的答案抄到了答题纸上的第i+1道题目的位置上，特别地，第n道题目的答案抄到了第1道题目的位置上。现在gx已经走出考场没法改了，不过他还是想知道自己期望能做对几道题目，这样他就知道会不会被lc鄙视了。<br/>
我们假设gx没有做错任何题目，只是答案抄错位置了。
</div>
<h3>
【输入格式】
</h3>
<div class="pdcont">
n很大，为了避免读入耗时太多，输入文件只有5个整数参数n, A, B, C, a<sub>1</sub>，由上交的程序产生数列a。下面给出pascal/C/C++的读入语句和产生序列的语句（默认从标准输入读入）：<br/>
<table align="center" style="border-collapse:collapse;border:none;" cellspacing="0" cellpadding="2">
<tbody>
<tr align="center" style="border:solid 1.0pt;">
<td style="border:solid 1.0pt;">
// for pascal<br/>
readln(n,A,B,C,q[1]);<br/>
for i:=2 to n do<br/>
q[i] := (int64(q[i-1]) * A + B) mod 100000001;<br/>
for i:=1 to n do<br/>
q[i] := q[i] mod C + 1;<br/>
<br/>
</td>
</tr>
</tbody>
</table>
<br/>
<table align="center" style="border-collapse:collapse;border:none;" cellspacing="0" cellpadding="2">
<tbody>
<tr align="center" style="border:solid 1.0pt;">
<td style="border:solid 1.0pt;">
// for C/C++<br/>
scanf(&#34;%d%d%d%d%d&#34;,&amp;n,&amp;A,&amp;B,&amp;C,a+1);<br/>
for (int i=2;i&lt;=n;i++)<br/>
a[i] = ((long long)a[i-1] * A + B) % 100000001;<br/>
for (int i=1;i&lt;=n;i++)<br/>
a[i] = a[i] % C + 1;<br/>
<br/>
</td>
</tr>
</tbody>
</table>
<br/>
选手可以通过以上的程序语句得到n和数列a（a的元素类型是32位整数），n和a的含义见题目描述。
</div>
<h3>
【输出格式】
</h3>
<div class="pdcont">
输出一个实数，表示gx期望做对的题目个数，保留三位小数。
</div>
<h3>
【样例输入】
</h3>
<div class="pddata">
3 2 0 4 1
</div>
<h3>
【样例输出】
</h3>
<div class="pddata">
1.167
</div>
<h3>
【样例说明】
</h3>
<div class="pdcont">
a[] = {2,3,1}<br/>
<table align="center" style="border-collapse:collapse;border:none;" cellspacing="0" cellpadding="2">
<tbody>
<tr align="center" style="border:solid 1.0pt;">
<td style="border:solid 1.0pt;">
正确答案<br/>
</td>
<td style="border:solid 1.0pt;">
gx的答案<br/>
</td>
<td style="border:solid 1.0pt;">
做对题目<br/>
</td>
<td style="border:solid 1.0pt;">
出现概率<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td style="border:solid 1.0pt;">
{1,1,1}<br/>
</td>
<td style="border:solid 1.0pt;">
{1,1,1}<br/>
</td>
<td style="border:solid 1.0pt;">
3<br/>
</td>
<td style="border:solid 1.0pt;">
1/6<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td style="border:solid 1.0pt;">
{1,2,1}<br/>
</td>
<td style="border:solid 1.0pt;">
{1,1,2}<br/>
</td>
<td style="border:solid 1.0pt;">
1<br/>
</td>
<td style="border:solid 1.0pt;">
1/6<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td style="border:solid 1.0pt;">
{1,3,1}<br/>
</td>
<td style="border:solid 1.0pt;">
{1,1,3}<br/>
</td>
<td style="border:solid 1.0pt;">
1<br/>
</td>
<td style="border:solid 1.0pt;">
1/6<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td style="border:solid 1.0pt;">
{2,1,1}<br/>
</td>
<td style="border:solid 1.0pt;">
{1,2,1}<br/>
</td>
<td style="border:solid 1.0pt;">
1<br/>
</td>
<td style="border:solid 1.0pt;">
1/6<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td style="border:solid 1.0pt;">
{2,2,1}<br/>
</td>
<td style="border:solid 1.0pt;">
{1,2,2}<br/>
</td>
<td style="border:solid 1.0pt;">
1<br/>
</td>
<td style="border:solid 1.0pt;">
1/6<br/>
</td>
</tr>
<tr align="center" style="border:solid 1.0pt;">
<td style="border:solid 1.0pt;">
{2,3,1}<br/>
</td>
<td style="border:solid 1.0pt;">
{1,2,3}<br/>
</td>
<td style="border:solid 1.0pt;">
0<br/>
</td>
<td style="border:solid 1.0pt;">
1/6<br/>
</td>
</tr>
</tbody>
</table>
<br/>
共有6种情况，每种情况出现的概率是1/6，gx期望做对(3+1+1+1+1+0)/6 = 7/6题。（相比之下，lc随机就能期望做对11/6题）
</div>
<h3>
【数据规模和约定】
</h3>
<div class="pdcont">
对于30%的数据 n≤10, C≤10<br/>
对于80%的数据 n≤10000, C≤10<br/>
对于90%的数据 n≤500000, C≤100000000<br/>
对于100%的数据 2≤n≤10000000, 0≤A,B,C,a<sub>1</sub>≤100000000
</div>
</div>
<div id="pcont2" style="margin-top:20px;display:none;">
<p class="NOI0" style="text-align:center;margin:13pt 0cm;">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><span style="font-size:large;"><strong>单选错位</strong></span></span> 
</p>
<p class="NOI" style="margin:13pt 0cm;">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【问题描述】</span></strong></span> 
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span style="font-size:small;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"> gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">和</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">lc</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">去参加</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">noip</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">初赛，其中有一种题型叫单项选择题，顾名思义，只有一个选项是正确答案。试卷上共有</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">道单选题，第</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">i</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">道单选题有</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">a<sub>i</sub></span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">个选项，这</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">a<sub>i</sub></span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">个选项编号是</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1,2,3,…,<i style="mso-bidi-font-style:normal;">a<sub>i</sub></i></span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">，每个选项成为正确答案的概率都是相等的。</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">lc</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">采取的策略是每道题目随机写上</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1-<i style="mso-bidi-font-style:normal;">a<sub>i</sub></i></span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">的某个数作为答案选项，他用不了多少时间就能期望做对<img width="40" height="59" alt="" src="/RequireFile.do?fid=hNQHr5N2"/></span></span><span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">道题目。</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">则是认认真真地做完了这</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">道题目，可是等他做完的时候时间也所剩无几了，于是他匆忙地把答案抄到答题纸上，没想到抄错位了：第</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">i</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">道题目的答案抄到了答题纸上的第</span><span style="font-family:&#39;Times New Roman&#39;;"><i style="mso-bidi-font-style:normal;"><span lang="EN-US">i</span></i><span lang="EN-US">+1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">道题目的位置上，特别地，第</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">道题目的答案抄到了第</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">1</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">道题目的位置上。现在</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">已经走出考场没法改了，不过他还是想知道自己期望能做对几道题目，这样他就知道会不会被</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">lc</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">鄙视了。</span></span> 
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;"> 我们假设</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;">没有做错任何题目，只是答案抄错位置了。</span></span> 
</p>
<p class="NOI" style="margin:13pt 0cm;">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【输入格式】</span></strong></span> 
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span style="font-size:small;"><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;"> n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">很大，为了避免读入耗时太多，输入文件只有</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">5</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">个整数参数</span><span style="font-family:&#39;Times New Roman&#39;;"><i style="mso-bidi-font-style:normal;"><span lang="EN-US">n</span></i><span lang="EN-US">, <i style="mso-bidi-font-style:normal;">A</i>, <i style="mso-bidi-font-style:normal;">B</i>, <i style="mso-bidi-font-style:normal;">C</i>, <i style="mso-bidi-font-style:normal;">a</i><sub>1</sub></span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">，由上交的程序产生数列</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">a</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">。下面给出</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">pascal/C/C++</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的读入语句和产生序列的语句（默认从标准输入读入）：</span></span> 
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span lang="EN-US"><v:shapetype id="_x0000_t202" path="m,l,21600r21600,l21600,xe" o:spt="202" coordsize="21600,21600"><v:stroke joinstyle="miter"></v:stroke><v:path o:connecttype="rect" gradientshapeok="t"></v:path></v:shapetype><v:shape id="_x0000_s1026" style="width:362.85pt;height:104.9pt;mso-position-horizontal-relative:char;mso-position-vertical-relative:line;" type="#_x0000_t202"><v:textbox>
</v:textbox></v:shape></span> 
</p>
<table width="100%" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td style="border-bottom:#f0f0f0;border-left:#f0f0f0;background-color:transparent;border-top:#f0f0f0;border-right:#f0f0f0;">
<div>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;color:gray;"><span style="font-size:small;">// for pascal<o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;"><span style="font-size:small;">readln(n,A,B,C,q[1]);<o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;"><span style="font-size:small;">for i:=2 to n do<o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;"><span style="font-size:small;"><span style="mso-tab-count:1;">    </span>q[i] := (int64(q[i-1]) * A + B) mod 100000001;<o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;"><span style="font-size:small;">for i:=1 to n do<o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;"><span style="font-size:small;"><span style="mso-tab-count:1;">    </span>q[i] := q[i] mod C + 1;<o:p></o:p></span></span> 
</p>
</div>
</td>
</tr>
</tbody>
</table>
<w:wrap type="none"></w:wrap><w:anchorlock></w:anchorlock>
<p>
<br/>
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span lang="EN-US"><v:shape id="_x0000_s1027" style="width:362.85pt;height:104.9pt;mso-position-horizontal-relative:char;mso-position-vertical-relative:line;" type="#_x0000_t202"><v:textbox>
</v:textbox></v:shape></span> 
</p>
<table width="100%" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td style="border-bottom:#f0f0f0;border-left:#f0f0f0;background-color:transparent;border-top:#f0f0f0;border-right:#f0f0f0;">
<div>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;color:gray;"><span style="font-size:small;">// for C/C++<o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;"><span style="font-size:small;">scanf(&#34;%d%d%d%d%d&#34;,&amp;n,&amp;A,&amp;B,&amp;C,a+1);<o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;"><span style="font-size:small;">for (int i=2;i&lt;=n;i++)<o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;"><span style="font-size:small;"><span style="mso-tab-count:1;">    </span>a[i] = ((long long)a[i-1] * A + B) % 100000001;<o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;"><span style="font-size:small;">for (int i=1;i&lt;=n;i++)<o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;">
<span lang="EN-US" style="font-family:&#34;"><span style="font-size:small;"><span style="mso-tab-count:1;">    </span>a[i] = a[i] % C + 1;<o:p></o:p></span></span> 
</p>
</div>
</td>
</tr>
</tbody>
</table>
<w:wrap type="none"></w:wrap><w:anchorlock></w:anchorlock>
<p>
<br/>
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"> 选手可以通过以上的程序语句得到</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">和数列</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">a</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">（</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">a</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的元素类型是</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">32</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">位整数），</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">n</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">和</span><i style="mso-bidi-font-style:normal;"><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">a</span></span></i><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">的含义见题目描述。</span></span> 
</p>
<p class="NOI" style="margin:13pt 0cm;">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【输出格式】</span></strong></span> 
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;"> 输出一个实数，表示</span><span lang="EN-US"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">期望做对的题目个数，保留三位小数。</span></span> 
</p>
<p class="NOI" style="margin:13pt 0cm;">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【样例输入】</span></strong></span> 
</p>
<p class="NOI2" style="margin:0cm 0cm 0pt;">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">3 2 0 4 1</span></span> 
</p>
<p class="NOI" style="margin:13pt 0cm;">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【样例输出】</span></strong></span> 
</p>
<p class="NOI2" style="margin:0cm 0cm 0pt;">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Courier New&#39;;">1.167</span></span> 
</p>
<p class="NOI" style="margin:13pt 0cm;">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【样例说明】</span></strong></span> 
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span lang="EN-US"><span style="font-size:small;font-family:&#39;Times New Roman&#39;;"> a[] = {2,3,1}</span></span> 
</p>
<p>
<br/>
</p>
<table class="MsoNormalTable ke-zeroborder" style="margin:auto auto auto 4.65pt;border-collapse:collapse;mso-table-layout-alt:fixed;mso-padding-alt:0cm 5.4pt 0cm 5.4pt;" border="0" cellspacing="0" cellpadding="0">
<tbody>
<tr style="height:14.25pt;mso-yfti-irow:0;mso-yfti-firstrow:yes;">
<td width="103" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:77pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">正确答案</span><span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><o:p></o:p></span> 
</p>
</td>
<td width="98" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:73.65pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">的答案</span><span lang="EN-US" style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;"><o:p></o:p></span> 
</p>
</td>
<td width="79" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:59.25pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">做对题目</span><span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><o:p></o:p></span> 
</p>
</td>
<td width="80" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:60pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span style="font-family:宋体;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;mso-font-kerning:0pt;">出现概率</span><span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><o:p></o:p></span> 
</p>
</td>
</tr>
<tr style="height:14.25pt;mso-yfti-irow:1;">
<td width="103" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:77pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{1,1,1}<o:p></o:p></span></span> 
</p>
</td>
<td width="98" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:73.65pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{1,1,1}<o:p></o:p></span></span> 
</p>
</td>
<td width="79" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:59.25pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">3<o:p></o:p></span></span> 
</p>
</td>
<td width="80" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:60pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">1/6<o:p></o:p></span></span> 
</p>
</td>
</tr>
<tr style="height:3.7pt;mso-yfti-irow:2;">
<td width="103" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:77pt;padding-right:5.4pt;height:3.7pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{1,2,1}<o:p></o:p></span></span> 
</p>
</td>
<td width="98" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:73.65pt;padding-right:5.4pt;height:3.7pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{1,1,2}<o:p></o:p></span></span> 
</p>
</td>
<td width="79" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:59.25pt;padding-right:5.4pt;height:3.7pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">1<o:p></o:p></span></span> 
</p>
</td>
<td width="80" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:60pt;padding-right:5.4pt;height:3.7pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">1/6<o:p></o:p></span></span> 
</p>
</td>
</tr>
<tr style="height:14.25pt;mso-yfti-irow:3;">
<td width="103" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:77pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{1,3,1}<o:p></o:p></span></span> 
</p>
</td>
<td width="98" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:73.65pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{1,1,3}<o:p></o:p></span></span> 
</p>
</td>
<td width="79" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:59.25pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">1<o:p></o:p></span></span> 
</p>
</td>
<td width="80" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:60pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">1/6<o:p></o:p></span></span> 
</p>
</td>
</tr>
<tr style="height:14.25pt;mso-yfti-irow:4;">
<td width="103" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:77pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{2,1,1}<o:p></o:p></span></span> 
</p>
</td>
<td width="98" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:73.65pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{1,2,1}<o:p></o:p></span></span> 
</p>
</td>
<td width="79" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:59.25pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">1<o:p></o:p></span></span> 
</p>
</td>
<td width="80" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:60pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">1/6<o:p></o:p></span></span> 
</p>
</td>
</tr>
<tr style="height:14.25pt;mso-yfti-irow:5;">
<td width="103" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:77pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{2,2,1}<o:p></o:p></span></span> 
</p>
</td>
<td width="98" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:73.65pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{1,2,2}<o:p></o:p></span></span> 
</p>
</td>
<td width="79" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:59.25pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">1<o:p></o:p></span></span> 
</p>
</td>
<td width="80" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:60pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">1/6<o:p></o:p></span></span> 
</p>
</td>
</tr>
<tr style="height:14.25pt;mso-yfti-irow:6;mso-yfti-lastrow:yes;">
<td width="103" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:77pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{2,3,1}<o:p></o:p></span></span> 
</p>
</td>
<td width="98" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:73.65pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">{1,2,3}<o:p></o:p></span></span> 
</p>
</td>
<td width="79" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:59.25pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">0<o:p></o:p></span></span> 
</p>
</td>
<td width="80" style="border-bottom:#f0f0f0;border-left:#f0f0f0;padding-bottom:0cm;background-color:transparent;padding-left:5.4pt;width:60pt;padding-right:5.4pt;height:14.25pt;border-top:#f0f0f0;border-right:#f0f0f0;padding-top:0cm;">
<p align="left" class="MsoNormal" style="text-align:left;margin:0cm 0cm 0pt;mso-pagination:widow-orphan;">
<span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;mso-font-kerning:0pt;"><span style="font-family:&#39;Times New Roman&#39;;">1/6<o:p></o:p></span></span> 
</p>
</td>
</tr>
</tbody>
</table>
<p>
<br/>
</p>
<p class="MsoNormal" style="text-indent:21pt;margin:0cm 0cm 0pt;">
<span style="font-family:&#34;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">共有</span><span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;"><span style="font-family:&#39;Times New Roman&#39;;">6</span></span><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;">种情况，每种情况出现的概率是</span><span lang="EN-US" style="font-size:12pt;"><span style="font-family:&#39;Times New Roman&#39;;">1/6</span></span><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;">，</span><span lang="EN-US" style="font-size:12pt;"><span style="font-family:&#39;Times New Roman&#39;;">gx</span></span><span style="font-family:&#34;font-size:12pt;mso-ascii-font-family:&#39;Times New Roman&#39;;mso-hansi-font-family:&#39;Times New Roman&#39;;">期望做对</span><span lang="EN-US" style="font-size:12pt;mso-fareast-font-family:&#39;Lingoes Unicode&#39;;"><span style="font-family:&#39;Times New Roman&#39;;">(3+1+1+1+1+0)/6 = 7/6</span></span><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;">题。（相比之下，</span><span lang="EN-US" style="font-size:12pt;"><span style="font-family:&#39;Times New Roman&#39;;">lc</span></span><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;">随机就能期望做对</span><span lang="EN-US" style="font-size:12pt;"><span style="font-family:&#39;Times New Roman&#39;;">11/6</span></span><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;">题）<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p class="NOI" style="margin:13pt 0cm;">
<span style="font-family:黑体;mso-ascii-font-family:Arial;mso-hansi-font-family:Arial;"><strong><span style="font-size:small;">【数据范围】</span></strong></span> 
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">对于</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">30%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">的数据</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;"> n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">10, C</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">10<o:p></o:p></span></span> 
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">对于</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">80%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">的数据</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;"> n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">10000, C</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">10<o:p></o:p></span></span> 
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">对于</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">90%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">的数据</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;"> n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">500000, C</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">100000000<o:p></o:p></span></span> 
</p>
<p class="NOI1" style="margin:0cm 0cm 0pt;">
<span style="font-size:small;"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">对于</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">100%</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">的数据</span><span style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;"> <span lang="EN-US">2</span></span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">n</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">10000000, 0</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">A,B,C,<i style="mso-bidi-font-style:normal;">a</i><sub>1</sub></span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri;">≤</span><span lang="EN-US" style="font-family:&#34;mso-bidi-font-family:&#39;Times New Roman&#39;;">100000000<o:p></o:p></span></span> 
</p>
<p>
 
</p>
</div>
</div>
