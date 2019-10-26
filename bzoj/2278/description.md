
# Description

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">The Byteotian Waste Management Company (BWMC) has drastically raised the price of garbage collection lately. This caused some of the citizens to stop paying for collecting their garbage and start disposing of it in the streets. Consequently, many streets of Byteburg are literally buried under litter. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">The street system of Byteburg consists of n intersections, some of which are directly connected with bidirectional streets. No two streets connect the same pair of intersections. Some of the streets are littered while others are not. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">The mayor of Byteburg, Byteasar, has decided on an unprecedented action to persuade the citizens to pay for waste collection. Namely, he decided to clean only some of the streets - precisely those that the majority of people living on paid for garbage collection. The streets that the majority of people living on did not pay for waste collection, on the other hand, will thus remain littered - or if it is called for - will become littered by the garbage collected from other streets! Byteasar has already prepared a city map with the streets to be cleaned and to remain or become littered marked on. Unfortunately, the BWMC employees cannot comprehend his master plan. They are, however, quite capable of carrying out simple instructions. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">A single such instruction consists in driving the garbage truck along a route that starts on an arbitrary intersection, goes along any streets of choice, and ending on the very same intersection that it started on. However, every intersection can be visited at most once on a single route, except for the one it starts and ends with-the garbage truck obviously appears twice on that one. The truck cleans a littered street it rides along, but on the other hand it dumps the waste on the clean streets along its route, making them littered. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">Byteasar wonders if it is possible to execute his plan by issuing a number of aforementioned route instructions. Help him out by writing a program that determines a set of such routes or concludes that it is impossible. <o:p></o:p></span></p>
<p>某国的街道很脏，可以开一些清理车去清理它们。<br/>
每次清理车走的路是一个环，清理完之后环上所有的街道改变状态（脏-&gt;不脏，不脏-&gt;脏）<br/>
给出初始状态和终止状态，求一个合法的清理车清理方案。</p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">There are two integers, separated by a single space, in the first line of the standard input: n and m (1&lt;=N&lt;=100000,1&lt;=M&lt;=1000000), denoting the number of intersections and the number of streets in Byteburg, respectively. The intersections are numbered from 1 to n. The following m lines specify successive streets, one per line. Each of those lines holds four integers separated by single spaces: a,b, s and t(1&lt;=a&lt;b&lt;=N, s,t</span><span style="font-size: 10pt; color: #444444; line-height: 140%; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: Tahoma; mso-ascii-font-family: Tahoma; mso-hansi-font-family: Tahoma">属于集合</span><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">[0,1]). Such a quadruple specifies that the intersections a and b are connected with a street, <v:shape id="_x0000_i1026" alt="" type="#_x0000_t75" style="width: 4.5pt; height: 5.25pt"><v:imagedata o:href="http://main.edu.pl/images/OI18/smi-en-tex.17.png" src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image002.gif"></v:imagedata></v:shape>tells if the street is currently littered (0 means clean, while 1 means littered), and <v:shape id="_x0000_i1027" alt="" type="#_x0000_t75" style="width: 3.75pt; height: 8.25pt"><v:imagedata o:href="http://main.edu.pl/images/OI18/smi-en-tex.20.png" src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image003.gif"></v:imagedata></v:shape>tells if the street should be littered according to Byteasar&#39;s plan. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">You may assume that if there exists a set of routes to carry out Byteasar&#39;s plan, then there is one in which the total number of streets that the garbage truck follows does not exceed 5*M. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">In tests worth 60% of the points it additionally holds that m&lt;=10000. <o:p></o:p></span></p>
<p><span lang="EN-US" style="font-size: 12pt; color: #444444; line-height: 140%; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: 宋体"><o:p></o:p></span></p>
<p></p>
<p></p>
<p>Input<br/>
第一行n，m (路口个数，街道个数)<br/>
下面m行，每行四个数x,y,z,w<br/>
x，y表示该街道连接的路口的编号，z表示初始时该街道的状态，w表示终止时该街道的状态(1=脏 0=不脏)<br/>
1&lt;=n&lt;=100000 1&lt;=m&lt;=1000000</p></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">If there is no set of routes for the garbage truck to execute Byteasar&#39;s plan, then the word &#34;</span><span lang="EN-US" style="font-size: 12pt; color: #444444; line-height: 140%; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: 宋体">NIE</span><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">&#34; (<i>no</i> in Polish) should be printed out to the first and only line of the standard output. Otherwise, an arbitrary set of routes that does execute Byteasar&#39;s plan and has the truck move along no more than 5*m streets in total should be printed out. Then the first line should hold the number k of routes in the set. The following k lines should describe the routes, one per line. The <v:shape id="_x0000_i1028" alt="" type="#_x0000_t75" style="width: 32.25pt; height: 13.5pt"><v:imagedata o:href="http://main.edu.pl/images/OI18/smi-en-tex.26.png" src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image004.gif"></v:imagedata></v:shape>-th line should start with a positive integer <v:shape id="_x0000_i1029" alt="" type="#_x0000_t75" style="width: 8.25pt; height: 10.5pt"><v:imagedata o:href="http://main.edu.pl/images/OI18/smi-en-tex.27.png" src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image005.gif"></v:imagedata></v:shape>equal to the number of streets in the <v:shape id="_x0000_i1030" alt="" type="#_x0000_t75" style="width: 3pt; height: 8.25pt"><v:imagedata o:href="http://main.edu.pl/images/OI18/smi-en-tex.28.png" src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image006.gif"></v:imagedata></v:shape>-th route. After a single space, <v:shape id="_x0000_i1031" alt="" type="#_x0000_t75" style="width: 30pt; height: 10.5pt"><v:imagedata o:href="http://main.edu.pl/images/OI18/smi-en-tex.29.png" src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image007.gif"></v:imagedata></v:shape>numbers of successive intersections along the route should follow, separated by single spaces. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto; mso-outline-level: 2"><b><span lang="EN-US" style="font-size: 18pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">Example<o:p></o:p></span></b></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">The clean streets are drawn with a thin line in the figure, whereas the littered streets are drawn with a thick line. The streets that are to be clean are drawn with a dashed line, while those that are to be littered are drawn with a solid line. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; tab-stops: 45.8pt 91.6pt 137.4pt 183.2pt 229.0pt 274.8pt 320.6pt 366.4pt 412.2pt 458.0pt 503.8pt 549.6pt 595.4pt 641.2pt 687.0pt 732.8pt"><span lang="EN-US" style="font-size: 12pt; color: #444444; line-height: 140%; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: 宋体"><o:p></o:p></span></p>
<p></p>
<p></p>
<p></p>
<p></p>
<p>如果不存在合法方案，输出NIE。<br/>
如果存在，第一行p，表示清理车的个数（要求p&lt;=m*5）<br/>
</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 8<br/>
1 2 0 1<br/>
2 3 1 0<br/>
1 3 0 1<br/>
2 4 0 0<br/>
3 5 1 1<br/>
4 5 0 1<br/>
5 6 0 1<br/>
4 6 0 1<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3 1 3 2 1 <br/>
3 4 6 5 4 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><img alt="" src="/source/bzoj/2278/img/aHR0cDovL21haW4uZWR1LnBsL2ltYWdlcy9PSTE4L3NtaXphZDEuZ2lm.gif"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=vfleaking提供SPJ">vfleaking提供SPJ</a></p></div>

