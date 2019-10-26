
# Description

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">The Byteotian Institute of Meteorology (BIM) measures the air temperature daily. The measurement is done automatically, and its result immediately printed. Unfortunately, the ink in the printer has long dried out... The employees of BIM however realised the fact only recently, when the Byteotian Organisation for Meteorology (BOM) requested access to that data. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">An eager intern by the name of Byteasar saved the day, as he systematically noted down the temperatures reported by two domestic alcohol thermometers placed on the north and south outside wall of the BIM building. It was established decades ago by various BIM employees that the temperature reported by the thermometer on the south wall of the building is never lower than the actual temperature, while that reported by the thermometer on the north wall of the building is never higher than the actual temperature. Thus even though the exact temperatures for each day remain somewhat of a mystery, the range they were in is known at least. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">Fortunately for everyone involved (except Byteasar and you, perhaps), BOM does not require exact temperatures. They only want to know the longest period in which the temperature was not dropping (i.e. on each successive day it was no smaller than on the day before). In fact, the veteran head of BIM knows very well that BOM would like this period as long as possible. To whitewash the negligence he insists that Byteasar determines, based on his valuable notes, the longest period in which the temperature <b>could have been</b> not dropping. Now this is a task that Byteasar did not quite expect on his BIM internship, and he honestly has no idea how to tackle it. He asks you for help in writing a program that determines the longest such period. <o:p></o:p></span></p>
<p>某国进行了连续n天的温度测量，测量存在误差，测量结果是第i天温度在[l_i,r_i]范围内。<br/>
求最长的连续的一段，满足该段内可能温度不降。</p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">In the first line of the standard input there is one integer n(1&lt;=N&lt;=1000000) that denotes the number of days for which Byteasar took notes on the temperature. The measurements from day <v:shapetype id="_x0000_t75" coordsize="21600,21600" o:spt="75" o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe" filled="f" stroked="f"><v:stroke joinstyle="miter"></v:stroke><v:formulas><v:f eqn="if lineDrawn pixelLineWidth 0"></v:f><v:f eqn="sum @0 1 0"></v:f><v:f eqn="sum 0 0 @1"></v:f><v:f eqn="prod @2 1 2"></v:f><v:f eqn="prod @3 21600 pixelWidth"></v:f><v:f eqn="prod @3 21600 pixelHeight"></v:f><v:f eqn="sum @0 0 1"></v:f><v:f eqn="prod @6 1 2"></v:f><v:f eqn="prod @7 21600 pixelWidth"></v:f><v:f eqn="sum @8 21600 0"></v:f><v:f eqn="prod @7 21600 pixelHeight"></v:f><v:f eqn="sum @10 21600 0"></v:f></v:formulas><v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"></v:path><o:lock v:ext="edit" aspectratio="t"></o:lock></v:shapetype><v:shape id="_x0000_i1025" type="#_x0000_t75" alt="" style="width: 3pt; height: 8.25pt"><v:imagedata src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image001.gif" o:href="http://main.edu.pl/images/OI18/tem-en-tex.3.png"></v:imagedata></v:shape>are given in the line no.i+1 Each of those lines holds two integers, x and y (-10^9&lt;=x&lt;=y&lt;=10^9). These denote, respectively, the minimum and maximum possible temperature on that particular day, as reported by the two thermometers. <o:p></o:p></span></p>
<p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">In some of the tests, worth 50 points in total, the temperatures never drop below -50 degrees (Celsius, in case you wonder!) and never exceeds 50 degrees (-50&lt;=x&lt;=y&lt;=50) <span style="mso-spacerun: yes"> </span><o:p></o:p></span></p>
<p><span lang="EN-US" style="font-size: 12pt; color: #444444; line-height: 140%; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: 宋体"><o:p></o:p></span>
</p><p></p>
<p></p>
<p>第一行n<br/>
下面n行，每行l_i，r_i<br/>
1&lt;=n&lt;=1000000</p></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="margin: 0cm 0cm 0pt; line-height: 140%; text-align: left; mso-pagination: widow-orphan; mso-margin-top-alt: auto; mso-margin-bottom-alt: auto"><span lang="EN-US" style="font-size: 10pt; color: #444444; line-height: 140%; font-family: Tahoma; mso-font-kerning: 0pt">In the first and only line of the standard output your program should print a single integer, namely the maximum number of days for which the temperature in Byteotia could have been not dropping. <o:p></o:p></span></p>
<p><span lang="EN-US" style="font-size: 12pt; color: #444444; line-height: 140%; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: 宋体"><o:p></o:p></span>
</p><p></p>
<p></p>
<p>一行，表示该段的长度</p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
<br/>
6 10<br/>
<br/>
1 5<br/>
<br/>
4 8<br/>
<br/>
2 5<br/>
<br/>
6 8<br/>
<br/>
3 5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
</span></div>

# Hint

<div class="content"><p></p><p><a href="http://main.edu.pl/images/OI18/tem.gif"><img alt="" src="/source/bzoj/2276/img/aHR0cDovL21haW4uZWR1LnBsL2ltYWdlcy9PSTE4L3RlbS5naWY=.gif"/></a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

