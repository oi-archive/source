
# Description

<div class="content"><h1 style="margin-top:0cm;margin-right:0cm;margin-bottom:15.0pt;margin-left:
0cm;mso-line-height-alt:13.5pt;background:white"></h1>
<p style="line-height: 13.5pt; background-color: white; background-position: initial initial; background-repeat: initial initial; "><span style="font-size: medium; "><span lang="EN-US" style="font-family: Tahoma; color: rgb(68, 68, 68); ">Everyone knew it would only be a matter of time. So what? Faced for years on, a peril becomes the every-day reality. It loses its meaning...</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:Tahoma;
color:#444444"><o:p></o:p></span></p>
<p style="line-height: 13.5pt; background-color: white; background-position: initial initial; background-repeat: initial initial; "><span style="font-size: medium; "><span lang="EN-US" style="font-family: Tahoma; color: rgb(68, 68, 68); ">Today the letter of the Bitotian char Bittard to the Byteotian king Byteasar was released to the public. Bitotia requested annexation of the whole Byteotia on pain of using the Bit Polarizing Magnet (BPM). If used, the BPM would make each and every road in Byteotia unidirectional. The enemy knows only too well that this could be a fatal blow to the minimalist Byteotian infrastructure - there is a unique way between each pair of towns.</span></span><span lang="EN-US" style="font-size:10.0pt;font-family:Tahoma;
color:#444444"><o:p></o:p></span></p>
<p style="line-height: 13.5pt; background-color: white; background-position: initial initial; background-repeat: initial initial; "><span style="font-size: medium; "><span lang="EN-US" style="font-family: Tahoma; color: rgb(68, 68, 68); ">How badly can the BPM damage the Byteotian infrastructure? Determine the minimum and the maximum number of such pairs of towns that it will still be possible to travel from one of them to the other while observing the new roads orientation.</span></span></p>
<p style="line-height: 13.5pt; background-color: white; background-position: initial initial; background-repeat: initial initial; "><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">给定一棵树，可以对每条边定向成一个有向图，这张有向图的可达点对数为树上有路径从</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">u</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">到达</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">v</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">的点对</span><span lang="EN-US" style="font-family: Helvetica, &#39;Microsoft Yahei&#39;, verdana; font-size: 14px; line-height: 20.909090042114258px;">(u,v)</span><span style="font-size: 14px; line-height: 20.909090042114258px; font-family: 宋体;">个数。求最小可达点对数和最大可达点对数</span></p>
<p style="line-height: 13.5pt; background-color: white; background-position: initial initial; background-repeat: initial initial; "><span lang="EN-US" style="font-size:10.0pt;font-family:Tahoma;
color:#444444"><o:p></o:p></span></p>
<h2 style="background-color: white; background-position: initial initial; background-repeat: initial initial; "></h2>
<p></p></div>

# Input

<div class="content"><h2 style="background-color: white; "><span lang="EN-US" style="font-size: medium; background-color: white; line-height: 13.5pt; font-family: Tahoma; color: rgb(68, 68, 68); ">The first line of the standard input gives a single integer<span class="apple-converted-space"> </span>N </span><span style="font-size: medium; background-color: white; line-height: 13.5pt; color: rgb(68, 68, 68); ">（</span><span lang="EN-US" style="font-size: medium; background-color: white; line-height: 13.5pt; font-family: Tahoma; color: rgb(68, 68, 68); ">1&lt;=N&lt;=250000</span><span style="font-size: medium; background-color: white; line-height: 13.5pt; color: rgb(68, 68, 68); ">）</span><span lang="EN-US" style="font-size: medium; background-color: white; line-height: 13.5pt; font-family: Tahoma; color: rgb(68, 68, 68); ">, the number of towns in Byteotia. The<span class="apple-converted-space"> </span>N-1<span class="apple-converted-space"> </span>lines that follow describe these roads. Each such line holds two integers,<span class="apple-converted-space"> </span>U <span class="apple-converted-space"> </span>and<span class="apple-converted-space"> </span>V (1&lt;=U&lt;=V&lt;=N)<span class="apple-converted-space"> </span>, which indicate that there is a direct road (still bidirectional at the moment) linking the towns no.<span class="apple-converted-space"> </span><img width="8" height="7" src="file:///C:/DOCUME~1/ADMINI~1/LOCALS~1/Temp/msohtml1/01/clip_image001.gif" v:shapes="_x0000_i1025" alt=""/><span class="apple-converted-space"> </span>and<span class="apple-converted-space"> </span><img width="6" height="7" src="file:///C:/DOCUME~1/ADMINI~1/LOCALS~1/Temp/msohtml1/01/clip_image002.gif" v:shapes="_x0000_i1026" alt=""/>.</span></h2>
<h2 style="background-color: white; "></h2>
<pre style="background-color: white; line-height: 13.5pt; "></pre>
<p></p></div>

# Output

<div class="content"><div></div>
<div>
<p style="background-color: white; line-height: 13.5pt; "><span style="font-size: medium; "><span lang="EN-US" style="font-family: Tahoma; color: rgb(68, 68, 68); ">Two integers should be printed to the first and only line of the standard output. The first number should be the minimum and the second - the maximum number of pairs of towns which could remain connected (though in one direction only) after the roads are polarized.</span></span><span lang="EN-US" style="font-size: 10pt; font-family: Tahoma; color: rgb(68, 68, 68); "><o:p></o:p></span></p>
<h2 style="background-color: white; "></h2>
<pre style="background-color: white; line-height: 13.5pt; "></pre>
</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2<br/>
1 3<br/>
1 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
3 5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢HJWJBSR提供译文">鸣谢HJWJBSR提供译文</a></p></div>

