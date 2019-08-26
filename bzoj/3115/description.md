
# Description

<div class="content"><p><span style="font-size: medium">一个化学家，他对化学的无比狂热使得他认为自己说的每一句话都应该由元素名称组成的，例如：“I Am CLaRa”（I是碘，Am是镅，C是碳，La镧，Ra是镭），“InTeRnAtIONAl”。但是有些词他是不能说的，例如“collegiate”, “programming” and “contest”。</span></p>
<p><span style="font-size: medium"><img height="299" alt="" width="533" src="source/bzoj/3115/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNC8xMS5qcGc=.jpg"/><br/>
现在给你一些单词，希望你确定这些单词是他是否能说，如果能输出YES，不能输出NO。</span></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-family: &#39;Courier New&#39;">第一行</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;">T</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-family: &#39;Courier New&#39;">表示数据组数。</span></span><font size="3"><span lang="EN-US" style="font-family: &#34;Courier New&#34;"><o:p></o:p></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-family: &#39;Courier New&#39;">下面</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;">T</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-family: &#39;Courier New&#39;">行每行一个字符串，表示大伟询问的词语。长度不超过</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;">5W</span></span><font size="3"><span lang="EN-US" style="font-family: &#34;Courier New&#34;"><o:p></o:p></span></font></p>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><span style="font-size: medium"><span lang="EN-US" style="font-family: &#39;Courier New&#39;">T</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-family: &#39;Courier New&#39;">行，每行为</span><span lang="EN-US" style="font-family: &#39;Courier New&#39;">YES</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-family: &#39;Courier New&#39;">或者</span><span lang="EN-US" style="font-family: &#39;Courier New&#39;">NO</span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-family: &#39;Courier New&#39;">。</span></span><font size="3"><span lang="EN-US" style="font-family: &#39;Courier New&#39;"><o:p></o:p></span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-family: &#39;Courier New&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
international<br/>
collegiate<br/>
programming<br/>
Contest<br/>
<br/>
 <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
NO<br/>
NO<br/>
NO<br/>
<br/>
 <br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">附录</span></p><br/>
<p><span style="font-size: medium">&#34;H&#34;,&#34;He&#34;,&#34;Li&#34;,&#34;Be&#34;,&#34;B&#34;,&#34;C&#34;,&#34;N&#34;,&#34;O&#34;,&#34;F&#34;,&#34;Ne&#34;,&#34;Na&#34;,&#34;Mg&#34;,&#34;Al&#34;,&#34;Si&#34;,&#34;P&#34;,&#34;S&#34;,&#34;Cl&#34;,&#34;Ar&#34;,&#34;K&#34;,&#34;Ca&#34;,&#34;Sc&#34;,&#34;Ti&#34;,&#34;V&#34;,&#34;Cr&#34;,&#34;Mn&#34;,&#34;Fe&#34;,&#34;Co&#34;,&#34;Ni&#34;,&#34;Cu&#34;,&#34;Zn&#34;,&#34;Ga&#34;,&#34;Ge&#34;,&#34;As&#34;,&#34;Se&#34;,&#34;Br&#34;,&#34;Kr&#34;,&#34;Rb&#34;,&#34;Sr&#34;,&#34;Y&#34;,&#34;Zr&#34;,&#34;Nb&#34;,&#34;Mo&#34;,&#34;Tc&#34;,&#34;Ru&#34;,&#34;Rh&#34;,&#34;Pd&#34;,&#34;Ag&#34;,&#34;Cd&#34;,&#34;In&#34;,&#34;Sn&#34;,&#34;Sb&#34;,&#34;Te&#34;,&#34;I&#34;,&#34;Xe&#34;,&#34;Cs&#34;,&#34;Ba&#34;,&#34;Hf&#34;,&#34;Ta&#34;,&#34;W&#34;,&#34;Re&#34;,&#34;Os&#34;,&#34;Ir&#34;,&#34;Pt&#34;,&#34;Au&#34;,&#34;Hg&#34;,&#34;Tl&#34;,&#34;Pb&#34;,&#34;Bi&#34;,&#34;Po&#34;,&#34;At&#34;,&#34;Rn&#34;,&#34;Fr&#34;,&#34;Ra&#34;,&#34;Rf&#34;,&#34;Db&#34;,&#34;Sg&#34;,&#34;Bh&#34;,&#34;Hs&#34;,&#34;Mt&#34;,&#34;Ds&#34;,&#34;Rg&#34;,&#34;Cn&#34;,&#34;Fl&#34;,&#34;Lv&#34;,&#34;La&#34;,&#34;Ce&#34;,&#34;Pr&#34;,&#34;Nd&#34;,&#34;Pm&#34;,&#34;Sm&#34;,&#34;Eu&#34;,&#34;Gd&#34;,&#34;Tb&#34;,&#34;Dy&#34;,&#34;Ho&#34;,&#34;Er&#34;,&#34;Tm&#34;,&#34;Yb&#34;,&#34;Lu&#34;,&#34;Ac&#34;,&#34;Th&#34;,&#34;Pa&#34;,&#34;U&#34;,&#34;Np&#34;,&#34;Pu&#34;,&#34;Am&#34;,&#34;Cm&#34;,&#34;Bk&#34;,&#34;Cf&#34;,&#34;Es&#34;,&#34;Fm&#34;,&#34;Md&#34;,&#34;No&#34;,&#34;Lr&#34;</span></p><br/>
<p><span style="font-size: medium"> </span></p><br/>
<p><span style="font-size: medium">保证T&lt;=100，每行不超过5万个字母。</span></p><br/>
<p><span style="font-size: medium">有多组测试数据。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

