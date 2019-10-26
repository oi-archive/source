
# Description

<div class="content"><div style="text-indent: 21pt">某个城市有N个区域，这些区域用1到N这N个正整数编号，并且它们之间通过N-1条道路相连，保证任意两个区域有路径相通。对于每个区域i,有一个正整数权值w(i)。记d(u,v)为区域u和区域v之间的距离，表示它们之间唯一的一条路径的边数。若u和v为同一个区域，则d(u,v)=0。</div>
<div style="text-indent: 21pt">现在要选择两个区域建立消防站，你的任务是找出这两个不同的区域x和y使得以下的表达式S(x，y)的值最小。</div>
<p><img alt="" src="/source/bzoj/2447/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwOC9hYWEuanBn.jpg"/></p></div>

# Input

<div class="content"><div class="Section0" style="layout-grid:  15.6pt none">
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">共<font face="Times New Roman">N+1</font><font face="宋体">行。 </font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">第一行有一个正整数<font face="Times New Roman">N</font><font face="宋体">，表示区域的个数。 </font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">接下来有<font face="Times New Roman">N-1</font><font face="宋体">行，每行两个整数</font><font face="Times New Roman">u</font><font face="宋体">、</font><font face="Times New Roman">v</font><font face="宋体">，表述区域</font><font face="Times New Roman">u</font><font face="宋体">和区域</font><font face="Times New Roman">v</font><font face="宋体">之间有一条道路。 </font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">最后一行有<font face="Times New Roman">N</font><font face="宋体">个正整数，第</font><font face="Times New Roman">i</font><font face="宋体">个正整数表示区域</font><font face="Times New Roman">i</font><font face="宋体">的权值</font><font face="Times New Roman">W(i)</font><font face="宋体">。 </font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
</div>
<!--EndFragment--></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;">包含一个正整数，为最小的<font face="Times New Roman">S(x, y)</font><font face="宋体">的值。 </font></span><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 10.5pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
<br/>
<br/>
1 2<br/>
<br/>
<br/>
1 3<br/>
<br/>
<br/>
3 4<br/>
<br/>
<br/>
3 5<br/>
<br/>
<br/>
5 7 6 5 4 <br/>
<br/>
<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【样例解释】</p><br/>
<p><br/><br/>
选取区域2和区域3。</p><br/>
<p><br/><br/>
【数据规模和约定】</p><br/>
<p><br/><br/>
用H表示距离区域1最远结点的距离，即d(1, u)的最大值。</p><br/>
<p><br/><br/>
对于30%的数据满足：2 ≤ N ≤ 300</p><br/>
<p><br/><br/>
余下70%的数据满足：2 ≤ N ≤ 50000、H ≤ 70、W(i) ≤ 100<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

