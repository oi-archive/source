
# Description

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">因为是<font face="Times New Roman">OJ</font><font face="宋体">上的题，就简单点好了。给出一个长度为</font><font face="Times New Roman">n</font><font face="宋体">的序列，给出</font><font face="Times New Roman">M</font><font face="宋体">个询问：在</font><font face="Times New Roman">[l,r]</font><font face="宋体">之间找到一个在这个区间里只出现过一次的数，并且要求找的这个数尽可能大。如果找不到这样的数，则直接输出</font><font face="Times New Roman">0</font><font face="宋体">。我会采取一些措施强制在线。</font></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p> </o:p></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第一行为两个整数<font face="Times New Roman">N,M</font><font face="宋体">。</font><font face="Times New Roman">M</font><font face="宋体">是询问数，</font><font face="Times New Roman">N</font><font face="宋体">是序列的长度（</font><font face="Times New Roman">N&lt;=100000</font><font face="宋体">，</font><font face="Times New Roman">M&lt;=200000)</font></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第二行为<font face="Times New Roman">N</font><font face="宋体">个整数，描述这个序列</font><font face="Times New Roman">{ai}</font><font face="宋体">，其中所有</font><font face="Times New Roman">1&lt;=ai&lt;=N</font></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">再下面<font face="Times New Roman">M</font><font face="宋体">行，每行两个整数</font><font face="Times New Roman">x</font><font face="宋体">，</font><font face="Times New Roman">y</font><font face="宋体">，</font></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">询问区间<font face="Times New Roman">[l,r]</font><font face="宋体">由下列规则产生（</font><font face="Times New Roman">OIER</font><font face="宋体">都知道是怎样的吧</font><font face="Times New Roman">&gt;_&lt;)</font><font face="宋体">：</font></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">l=min(<font face="宋体">（</font><font face="Times New Roman">x+lastans)mod n+1,(y+lastans</font><font face="宋体">）</font><font face="Times New Roman">mod n+1);</font></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">r=max(<font face="宋体">（</font><font face="Times New Roman">x+lastans)mod n+1,(y+lastans</font><font face="宋体">）</font><font face="Times New Roman">mod n+1);</font></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">Lastans<font face="宋体">表示上一个询问的答案，一开始</font><font face="Times New Roman">lastans</font><font face="宋体">为</font><font face="Times New Roman">0</font></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">一共<font face="Times New Roman">M</font><font face="宋体">行，每行给出每个询问的答案。</font></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: medium"><span style="font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></span><span style="font-size: 10.5pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">10 10<br/>
6 4 9 10 9 10 9 4 10 4 <br/>
3 8<br/>
10 1<br/>
3 4<br/>
9 4<br/>
8 1<br/>
7 8<br/>
2 9<br/>
1 1<br/>
7 3<br/>
9 9<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
10<br/>
10<br/>
0<br/>
0<br/>
10<br/>
0<br/>
4<br/>
0<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
注意出题人为了方便，input的第二行最后多了个空格。</p><br/>
<p>2015.6.24新加数据一组，2016.7.9放至40S,600M,但未重测</p><br/>
<p> </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search= by zhzqkkk"> by zhzqkkk</a></p></div>

