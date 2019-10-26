
# Description

<div class="content"><p><span style="font-size: medium">小T准备在家里摆放几幅画，为此他买来了N幅画和N个画框。为了体现他的品味，小T希望能合理地搭配画与画框，使得其显得既不过于平庸也不太违和。对于第 幅画与第 个画框的配对，小T都给出了这个配对的平凡度Aij 与违和度Bij 。整个搭配方案的总体不和谐度为每对画与画框平凡度之和与每对画与画框违和度的乘积。具体来说，设搭配方案中第i幅画与第Pi个画框配对，则总体不和谐度为</span></p>
<p><span style="font-size: medium"><img height="96" width="364" alt="" src="/source/bzoj/3571/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNS8xMS5qcGc=.jpg"/></span></p>
<p><span style="font-size: medium">小T希望知道通过搭配能得到的最小的总体不和谐度是多少。<br/>
</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">输入文件第 行是一个正整数T ，表示数据组数，接下来是T组数据。<br/>
对于每组数据，第 行是一个正整数N，表示有N对画和画框。<br/>
第2到第N+1行，每行有N个非负整数，第i+1 行第j个数表示Aij 。<br/>
第N+2到第2*N+1行，每行有N个非负整数，第i+N+1 行第j个数表示Bij 。</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><span style="font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">包含T</span></span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Times New Roman&#34;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体"><v:shape id="_x0000_i1026" type="#_x0000_t75" style="width: 4.5pt; height: 12pt"><v:imagedata src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image001.png" o:title="" chromakey="white"></v:imagedata></v:shape></span><span style="font-size: medium"><span style="font-family: 宋体; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">行，每行一个整数，表示最小的总体不和谐度</span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
3<br/>
4 3 2<br/>
2 3 4<br/>
3 2 1<br/>
2 3 2<br/>
2 2 4<br/>
1 1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">30</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">第1幅画搭配第3个画框，第2幅画搭配第1个画框，第3 幅画搭配第2个画框，则总体不和谐度为30</span></p><br/>
<p><span style="font-size: medium"><br/><br/>
N&lt;=70,T&lt;=3,Aij&lt;=200,Bij&lt;=200</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

