
# Description

<div class="content"><p class="MsoNormal" style="text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:normal"><span lang="RU">某地区有m座煤矿，其中第i号矿每年产量为a<sub>i</sub>吨，现有火力发电厂一个，每年需用煤b吨，每年运行的固定费用（包括折旧费，不包括煤的运费）为h元，每吨原煤从第i号矿运到原有发电厂的运费为C<sub>i0</sub>（i=1，2，…，m）。 </span></b><b style="mso-bidi-font-weight:normal"><span lang="RU" style="mso-fareast-font-family:宋体;mso-fareast-language:ZH-CN"><o:p></o:p></span></b></p>
<p class="MsoNormal" style="text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:normal"><span lang="RU" style="mso-fareast-font-family:
宋体;mso-fareast-language:ZH-CN"><o:p> </o:p></span></b></p>
<p class="MsoNormal" style="text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:normal"><span lang="RU">现规划新建一个发电厂，m座煤矿每年开采的原煤将全部供给这两座发电厂。现有n个备选的厂址。若在第j号备选厂址建新厂，每年运行的固定费用为h<sub>j</sub>元。每吨原煤从第i号矿运到j号备选厂址的运费为C<sub>ij</sub>（i=1，2，…，m；j=1，2，…，n）。 </span></b><b style="mso-bidi-font-weight:normal"><span lang="RU" style="mso-fareast-font-family:宋体;mso-fareast-language:ZH-CN"><o:p></o:p></span></b></p>
<p class="MsoNormal" style="text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:normal"><span lang="RU" style="mso-fareast-font-family:
宋体;mso-fareast-language:ZH-CN"><o:p> </o:p></span></b></p>
<p class="MsoNormal" style="text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:normal"><span lang="RU">试问：应把新厂厂址选取在何处？m座煤矿开采的原煤应如何分配给两个发电厂，才能使每年的总费用（发电厂运行费用与原煤运费之和）为最小。 </span></b><b style="mso-bidi-font-weight:normal"><span lang="RU" style="mso-fareast-font-family:宋体;mso-fareast-language:ZH-CN"><o:p></o:p></span></b></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin-left:12.0pt;mso-para-margin-left:1.0gd;
text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:
normal"><span lang="RU">第1行：      m  b  h  n <o:p></o:p></span></b></p>
<p class="MsoNormal" style="margin-left:12.0pt;mso-para-margin-left:1.0gd;
text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:
normal"><span lang="RU">第2行：      a<sub>1</sub>  a<sub>2</sub> …  a<sub>m</sub> </span></b><b style="mso-bidi-font-weight:normal"><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;;mso-fareast-language:ZH-CN">（</span><span lang="RU">0&lt;=a<sub>i</sub>&lt;=500, a<sub>1</sub>+a<sub>2</sub>+...+a<sub>n</sub>&gt;=b</span></b><b style="mso-bidi-font-weight:normal"><span style="font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;;mso-fareast-language:
ZH-CN">）</span></b><b style="mso-bidi-font-weight:normal"><span lang="RU" style="mso-fareast-font-family:宋体;mso-fareast-language:ZH-CN"><o:p></o:p></span></b></p>
<p class="MsoNormal" style="margin-left:12.0pt;mso-para-margin-left:1.0gd;
text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:
normal"><span lang="RU">第3行：      h<sub>1</sub>  h<sub>2</sub> …  h<sub>n</sub> </span></b><b style="mso-bidi-font-weight:normal"><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;;mso-fareast-language:ZH-CN">（</span><span lang="RU">0&lt;=h<sub>i</sub>&lt;=100</span></b><b style="mso-bidi-font-weight:normal"><span style="font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;;mso-fareast-language:
ZH-CN">）</span></b><b style="mso-bidi-font-weight:normal"><span lang="RU" style="mso-fareast-font-family:宋体;mso-fareast-language:ZH-CN"><o:p></o:p></span></b></p>
<p class="MsoNormal" style="margin-left:12.0pt;mso-para-margin-left:1.0gd;
text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:
normal"><span lang="RU">第4行：      C<sub>10</sub> C<sub>20</sub> … C<sub>m0</sub> </span></b><b style="mso-bidi-font-weight:normal"><span style="font-family:宋体;mso-ascii-font-family:&#34;Times New Roman&#34;;mso-hansi-font-family:
&#34;Times New Roman&#34;;mso-fareast-language:ZH-CN">（</span><span lang="RU">0&lt;=Cij&lt;=50</span></b><b style="mso-bidi-font-weight:normal"><span style="font-family:宋体;mso-ascii-font-family:
&#34;Times New Roman&#34;;mso-hansi-font-family:&#34;Times New Roman&#34;;mso-fareast-language:
ZH-CN">）</span><span lang="RU"> <o:p></o:p></span></b></p>
<p class="MsoNormal" style="margin-left:12.0pt;mso-para-margin-left:1.0gd;
text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:
normal"><span lang="RU">第5行：      C<sub>11</sub> C<sub>21</sub> … C<sub>m1</sub> <o:p></o:p></span></b></p>
<p class="MsoNormal" style="margin-left:12.0pt;mso-para-margin-left:1.0gd;
text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:
normal"><span lang="RU">                              …   … <o:p></o:p></span></b></p>
<p class="MsoNormal" style="margin-left:12.0pt;mso-para-margin-left:1.0gd;
text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:
normal"><span lang="RU">第</span></b><b style="mso-bidi-font-weight:normal"><span lang="RU" style="mso-fareast-font-family:宋体;mso-fareast-language:ZH-CN">n</span><span lang="RU">+4行：C<sub>1n</sub> C<sub>2n</sub> … C<sub>mn</sub> <o:p></o:p></span></b></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin-left:12.0pt;mso-para-margin-left:1.0gd;
text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:
normal"><span lang="RU">第1行：新厂址编号，如果有多个编号满足要求，输出最小的。 <o:p></o:p></span></b></p>
<p class="MsoNormal" style="margin-left:12.0pt;mso-para-margin-left:1.0gd;
text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:
normal"><span lang="RU">第2行：总费用 <o:p></o:p></span></b></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 2 7 9 <br/>
3 1 10 3 <br/>
6 3 7 1 10 2 7 4 9 <br/>
1 2 4 3 <br/>
6 6 8 2 <br/>
4 10 8 4 <br/>
10 2 9 2 <br/>
7 6 6 2 <br/>
9 3 7 1 <br/>
2 1 6 9 <br/>
3 1 10 9 <br/>
4 2 1 8 <br/>
2 1 3 4 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8 <br/>
49 <br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin-left:24.0pt;mso-para-margin-left:2.0gd;&lt;br /&gt;
text-align:justify;text-justify:inter-ideograph"><b style="mso-bidi-font-weight:&lt;br /&gt;
normal"><span lang="RU">对于所有数据, n&lt;=50, m&lt;=50000, b&lt;=10000 <o:p></o:p></span></b></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

