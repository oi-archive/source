
# Description

<div class="content"><div>Maishroom在全国各地开设了OI辅导班，比如四川班等等。Maishroom的辅导班有两种讲师，也就是助教（主要是机房里其他小伙伴）和教师（主要是Maishroom自己）。当一个助教去打vp的时候，显然他就不能授课了，不过没有关系，因为只是助教。当一个教师A（例如Maishroom）去打（看）vp（片）的时候，他需要找另一个讲师B来代替自己的授课。如果B也是教师，他也需要另一个讲师C来代替自己，依次类推。</div>
<div>现在我们需要知道：</div>
<div>1）有多少个讲师不能去打vp。</div>
<div>2）有多少对讲师（A,B），单独地，每个人都可以去打vp，然而不能一起打（开）vp（黑）。</div>
<p></p></div>

# Input

<div class="content"><div>第一行，两个整数N, K。分别表示：辅导班里的讲师数与教师数。</div>
<div>约定：编号1~K的为教师，编号K+1~N的为助教。</div>
<div>以下K行，表示各个教师可以被哪些讲师替代。</div>
<div>第i+1行，第一个整数Di，代表可代替教师i的讲师数，之后Di个整数为其编号。</div>
<p></p></div>

# Output

<div class="content"><div>一行，两个整数。分别代表两问的答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 5<br/>
2 6 7<br/>
1 7<br/>
2 2 7<br/>
1 5<br/>
1 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 3</span></div>

# Hint

<div class="content"><p></p><div>教师4, 5不能去打vp。因为剩下一个人不能做两个人的事。</div><br/>
<div>当教师2, 3开黑的时候，讲师7不可能同时顶替他们两个人。</div><br/>
<div>事实上，(2, 3), (2, 7), (3, 7)都满足，可以单独vp，不能一起开黑。</div><br/>
<div><span style="font-size:10.5pt;line-height:115%;&lt;br /&gt;
font-family:微软雅黑;mso-ascii-font-family:Consolas;mso-hansi-font-family:Consolas;&lt;br /&gt;
mso-bidi-font-family:Consolas;mso-ansi-language:EN-US;mso-fareast-language:&lt;br /&gt;
ZH-CN;mso-bidi-language:AR-SA">对于</span><span lang="EN-US" style="font-size:10.5pt;&lt;br /&gt;
line-height:115%;font-family:Consolas;mso-fareast-font-family:微软雅黑;mso-bidi-font-family:&lt;br /&gt;
Consolas;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:&lt;br /&gt;
AR-SA">100%</span><span style="font-size:10.5pt;line-height:115%;font-family:&lt;br /&gt;
微软雅黑;mso-ascii-font-family:Consolas;mso-hansi-font-family:Consolas;mso-bidi-font-family:&lt;br /&gt;
Consolas;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:&lt;br /&gt;
AR-SA">的数据：</span><span lang="EN-US" style="font-size:10.5pt;line-height:115%;&lt;br /&gt;
font-family:Consolas;mso-fareast-font-family:微软雅黑;mso-bidi-font-family:Consolas;&lt;br /&gt;
mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">1</span><span style="font-size:10.5pt;line-height:115%;font-family:微软雅黑;mso-ascii-font-family:&lt;br /&gt;
Consolas;mso-hansi-font-family:Consolas;mso-bidi-font-family:Consolas;&lt;br /&gt;
mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">≤</span><span lang="EN-US" style="font-size:10.5pt;line-height:115%;font-family:Consolas;&lt;br /&gt;
mso-fareast-font-family:微软雅黑;mso-bidi-font-family:Consolas;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">K</span><span style="font-size:10.5pt;line-height:115%;font-family:微软雅黑;mso-ascii-font-family:&lt;br /&gt;
Consolas;mso-hansi-font-family:Consolas;mso-bidi-font-family:Consolas;&lt;br /&gt;
mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">≤</span><span lang="EN-US" style="font-size:10.5pt;line-height:115%;font-family:Consolas;&lt;br /&gt;
mso-fareast-font-family:微软雅黑;mso-bidi-font-family:Consolas;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">N</span><span style="font-size:10.5pt;line-height:115%;font-family:微软雅黑;mso-ascii-font-family:&lt;br /&gt;
Consolas;mso-hansi-font-family:Consolas;mso-bidi-font-family:Consolas;&lt;br /&gt;
mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">≤</span><span lang="EN-US" style="font-size:10.5pt;line-height:115%;font-family:Consolas;&lt;br /&gt;
mso-fareast-font-family:微软雅黑;mso-bidi-font-family:Consolas;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">5,000</span><span style="font-size:10.5pt;line-height:115%;font-family:微软雅黑;mso-ascii-font-family:&lt;br /&gt;
Consolas;mso-hansi-font-family:Consolas;mso-bidi-font-family:Consolas;&lt;br /&gt;
mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">，</span><span lang="EN-US" style="font-size:10.5pt;line-height:115%;font-family:Consolas;&lt;br /&gt;
mso-fareast-font-family:微软雅黑;mso-bidi-font-family:Consolas;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">1</span><span style="font-size:10.5pt;line-height:115%;font-family:微软雅黑;mso-ascii-font-family:&lt;br /&gt;
Consolas;mso-hansi-font-family:Consolas;mso-bidi-font-family:Consolas;&lt;br /&gt;
mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">≤</span><span lang="EN-US" style="font-size:10.5pt;line-height:115%;font-family:Consolas;&lt;br /&gt;
mso-fareast-font-family:微软雅黑;mso-bidi-font-family:Consolas;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">M</span><span style="font-size:10.5pt;line-height:115%;font-family:微软雅黑;mso-ascii-font-family:&lt;br /&gt;
Consolas;mso-hansi-font-family:Consolas;mso-bidi-font-family:Consolas;&lt;br /&gt;
mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">≤</span><span lang="EN-US" style="font-size:10.5pt;line-height:115%;font-family:Consolas;&lt;br /&gt;
mso-fareast-font-family:微软雅黑;mso-bidi-font-family:Consolas;mso-ansi-language:&lt;br /&gt;
EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA">20,000</span></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

