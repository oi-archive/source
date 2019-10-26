
# Description

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">2222<font face="宋体">年，人类在银河系外的某颗星球上发现了生命，并且携带了一个细胞回到了地球。经过反复研究，人类已经完全掌握了这类细胞的发展规律：</font></span><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">这种细胞最初的形态是“长条形”，一端是头，一端是尾，中间是躯干。细胞内部含有一列密码（你可以认为它是这种细胞的<font face="Times New Roman">DNA</font><font face="宋体">）。密码是一个长度为</font></span><span style="font-size: 12pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">n</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">的数字串，且仅含有<font face="Times New Roman">1~9</font><font face="宋体">这</font><font face="Times New Roman">9</font><font face="宋体">种数字，沿着细胞的躯干从头到尾排列着。</font></span><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">首先，细胞会经历一次分裂。细胞将沿躯干方向分裂成若干个球体，躯干将退化成丝状物，连接着相邻的球体。在分裂过程中，质量是均匀分布的。换句话说，若分裂成</span><span style="font-size: 12pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">k</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">个球体，每个球体的质量为原来的<font face="Times New Roman">1/</font></span><span style="font-size: 12pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">k</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">。然而，密码的分布是不确定的。若分割成</span><span style="font-size: 12pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">k</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">个球体，密码会被切割成</span><span style="font-size: 12pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">k</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">段（每段长度至少为<font face="Times New Roman">1</font><font face="宋体">），并</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; text-decoration: underline; mso-spacerun: &#39;yes&#39;">按从头到尾的顺序</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">分布在各个球体中。如图，为其中一种合法的一次分裂：</span><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-align: center"><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-align: center"><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><img height="270" width="456" alt="" src="/source/bzoj/2323/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwNi8xLmpwZw==.jpg"/></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">接下来，细胞会经历二次分裂。对于每个球体，其中会含有一小段密码（注意他是有序的），我们把它看作一个十进制的数</span><span style="font-size: 12pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">T</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">。这个球体会被分割成</span><span style="font-size: 12pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">T</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">个小球体，并排成一排，之间用躯干退化成的丝状物相连接，并且质量仍然是均匀分布的，每个小球体的质量都是原球体的<font face="Times New Roman">1/</font></span><span style="font-size: 12pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">T</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">。至此，密码已经发挥了它的作用，便消失了。如图，为二次分裂：</span><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-align: center"><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p><img height="218" width="583" alt="" src="/source/bzoj/2323/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwNi8yLmpwZw==.jpg"/></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">最后，细胞会进行变异。相邻小球体之间的丝状物可能会退化掉，这两个小球体便会以相切的方式直接连接。显然，二次分裂后，除两端外的每个小球体都有两段丝状物与其连接（头尾两端的小球体只有一段丝状物与其相连）。对于每个小球体，必须至少退化一段与其相连的丝状物，否则这个结构不稳定，会继续变异。如图，为一种稳定的变异：</span><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-align: center"><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p><img height="200" width="568" alt="" src="/source/bzoj/2323/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwNi8zLmpwZw==.jpg"/></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">现在，我们想知道，对于一个给定密码的细胞，总共有多少种稳定的结构。两种结构被认为相同，当且仅当他们拥有相同个数的小球体，从头到尾每个小球体的质量相同，并且从头到尾每对相邻小球体之间的连接方式相同（都是通过丝状物相连或都是通过相切直接相连）。你只需要回答这个结果 <font face="Times New Roman">mod 1000000007</font><font face="宋体">即可。</font></span><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第一行为一个正整数</span><span style="font-size: 12pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">n</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">，表示细胞密码的长度。</span><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 24pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第二行共</span><span style="font-size: 12pt; font-style: italic; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">n</span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">个数字，为给定的细胞密码，中间没有空格。</span><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p16" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p16" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><font face="宋体">只包含一个整数，为细胞的种数 </font><font face="Times New Roman">mod 1000000007</font><font face="宋体">的结果。</font></span><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p20" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入一】<br/>
<br/>
1<br/>
<br/>
1<br/>
<br/>
【样例输入二】<br/>
<br/>
1<br/>
<br/>
5<br/>
<br/>
【样例输入三】<br/>
<br/>
2<br/>
<br/>
11<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出一】<br/>
<br/>
0<br/>
<br/>
【样例输出二】<br/>
<br/>
3<br/>
<br/>
【样例输出三】<br/>
<br/>
56<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据规模】</p><br/>
<p>对于5%的数据满足，n ≤ 6；</p><br/>
<p>对于25%的数据满足，n ≤ 25；</p><br/>
<p>对于60%的数据满足，n ≤ 100；</p><br/>
<p>对于70%的数据满足，n ≤ 300；</p><br/>
<p>对于100%的数据满足，n ≤ 1 000。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

