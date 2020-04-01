
# Description

<div class="content"><div>给定Ｎ个点以及每个点的权值，要你处理接下来的Ｍ个操作。</div>
<div>操作有４种。操作从０到３编号。点从１到Ｎ编号。</div>
<div>０：后接两个整数（ｘ，ｙ），代表询问从ｘ到ｙ的路径上的点的权值的ｘｏｒ和。</div>
<div>保证ｘ到ｙ是联通的。</div>
<div>１：后接两个整数（ｘ，ｙ），代表连接ｘ到ｙ，若ｘ到Ｙ已经联通则无需连接。</div>
<div>２：后接两个整数（ｘ，ｙ），代表删除边（ｘ，ｙ），不保证边（ｘ，ｙ）存在。</div>
<div>３：后接两个整数（ｘ，ｙ），代表将点Ｘ上的权值变成Ｙ。</div>
<p></p>
<p><span id="1376900648617E" style="display: none"> </span></p></div>

# Input

<div class="content"><div>第１行两个整数,分别为Ｎ和Ｍ,代表点数和操作数。</div>
<div>第２行到第Ｎ＋１行,每行一个整数,整数在［１,１０＾９］内,代表每个点的权值。</div>
<div>第Ｎ＋２行到第Ｎ＋Ｍ＋１行,每行三个整数,分别代表操作类型和操作所需的量。</div>
<div>１＜＝Ｎ，Ｍ＜＝３０００００</div>
<p></p>
<p></p>
<p class="NOI" style="margin: 0cm 0cm 0pt; text-indent: 0cm; mso-char-indent-count: 0"><span style="font-size: 10.5pt; font-family: 华文新魏; mso-hansi-font-family: 宋体"><o:p></o:p></span></p>
<p></p>
<p class="NOI" style="margin: 0cm 0cm 0pt; text-indent: 0cm; mso-char-indent-count: 0"><span style="font-size: 10.5pt; mso-hansi-font-family: 宋体"><o:p></o:p></span></p>
<p class="NOI" style="margin: 0cm 0cm 0pt; text-indent: 0cm; mso-char-indent-count: 0"></p></div>

# Output

<div class="content"><p class="NOI" style="margin: 0cm 0cm 0pt; text-indent: 0cm; mso-char-indent-count: 0"><span style="font-family: Arial"><span style="font-size: medium"><span style="mso-hansi-font-family: 宋体">对于每一个０号操作，你须输出Ｘ到Ｙ的路径上点权的Ｘｏｒ和。</span></span></span><span style="font-size: 10.5pt; font-family: 华文新魏; mso-hansi-font-family: 宋体"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 <br/>
1<br/>
2<br/>
3<br/>
1 1 2<br/>
0 1 2 <br/>
0 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

