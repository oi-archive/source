
# Description

<div class="content"><p><span style="font-size: medium">Rain has pummeled the cows&#39; field, a rectangular grid of R rows and C columns (1 &lt;= R &lt;= 50, 1 &lt;= C &lt;= 50). While good for the grass, the rain makes some patches of bare earth quite muddy. The cows, being meticulous grazers, don&#39;t want to get their hooves dirty while they eat. To prevent those muddy hooves, Farmer John will place a number of wooden boards over the muddy parts of the cows&#39; field. Each of the boards is 1 unit wide, and can be any length long. Each board must be aligned parallel to one of the sides of the field. Farmer John wishes to minimize the number of boards needed to cover the muddy spots, some of which might require more than one board to cover. The boards may not cover any grass and deprive the cows of grazing area but they can overlap each other. Compute the minimum number of boards FJ requires to cover all the mud in the field. </span></p>
<div><span style="font-size: medium">    大雨侵袭了奶牛们的牧场．牧场是一个R * C的矩形，其中1≤R，C≤50.大雨将没有长草的土地弄得泥泞不堪，可是小心的奶牛们不想在吃草的时候弄脏她们的蹄子．  为了防止她们的蹄子被弄脏，约翰决定在泥泞的牧场里放置一些木板．每一块木板的宽度为1个单位，长度任意．每一个板必须放置在平行于牧场的泥地里．    约翰想使用最少的木板覆盖所有的泥地．一个木板可以重叠在另一个木板上，但是不能放在草地上．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers: R and C </span></p>
<p><span style="font-size: medium">* Lines 2..R+1: Each line contains a string of C characters, with &#39;*&#39; representing a muddy patch, and &#39;.&#39; representing a grassy patch. No spaces are present. </span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman"> </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行：两个整数</span><span lang="EN-US"><font face="Times New Roman">R</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">C.</font></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman"> </font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">到</span><span lang="EN-US"><font face="Times New Roman">R+1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行：每行</span><span lang="EN-US"><font face="Times New Roman">C</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个字符，其中“</span><span lang="EN-US"><font face="Times New Roman">*</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">’代表泥地，“．”代表草地．</span></span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer representing the number of boards FJ needs. </span></p>
<p><span style="font-size: medium"><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-fareast-font-family: 宋体; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">   </span><span style="font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;">最少需要多少木板．</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
*.*.<br/>
.***<br/>
***.<br/>
..*.<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
</span></div>

# Hint

<div class="content"><p></p><p><img height="231" alt="" width="286" src="/source/bzoj/1735/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS80NCgyKS5qcGc=.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

