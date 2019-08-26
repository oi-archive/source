
# Description

<div class="content"><h3 style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-weight: normal; font-size: 12pt; font-family: &#39;黑体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></h3>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; line-height: 150%"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">平面上给出<font face="Times New Roman">N</font><font face="宋体">个矩形，定义平面内的一个矩形是</font><font face="Times New Roman">cool</font><font face="宋体">的，当且仅当这个矩形的四边完全在给出</font><font face="Times New Roman">N</font><font face="宋体">个矩形的边界上（边界相互重合）。现在你想取</font><font face="Times New Roman">N</font><font face="宋体">个</font><font face="Times New Roman">cool</font><font face="宋体">矩形来一一代表这</font><font face="Times New Roman">N</font><font face="宋体">个矩形。</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; line-height: 150%"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">假如你要用一个<font face="Times New Roman">cool</font><font face="宋体">矩形来代表矩形</font><font face="Times New Roman">I</font><font face="宋体">，那么必须满足这个</font><font face="Times New Roman">cool</font><font face="宋体">矩形完全在</font><font face="Times New Roman">I</font><font face="宋体">之内；要求一个</font><font face="Times New Roman">cool</font><font face="宋体">矩形只能代表一个矩形，并且你选出的代表这</font><font face="Times New Roman">N</font><font face="宋体">个矩形的</font><font face="Times New Roman">N</font><font face="宋体">个</font><font face="Times New Roman">cool</font><font face="宋体">矩形之间，两两不覆盖（边界可以重叠）。</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; line-height: 150%"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">问你选出的<font face="Times New Roman">N</font><font face="宋体">个</font><font face="Times New Roman">cool</font><font face="宋体">矩形的最小面积和，或者返回</font><font face="Times New Roman">-1</font><font face="宋体">，表示无解</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">输入文件第一行括一个数字<font face="Times New Roman">N</font><font face="宋体">，</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">接下来<font face="Times New Roman">4</font><font face="宋体">行</font><font face="Times New Roman">N</font><font face="宋体">列，每列依次为</font><font face="Times New Roman">4</font><font face="宋体">个数字（</font><font face="Times New Roman">x1</font><font face="宋体">，</font><font face="Times New Roman">y1</font><font face="宋体">），（</font><font face="Times New Roman">x2</font><font face="宋体">，</font><font face="Times New Roman">y2</font><font face="宋体">）表示一个矩形的对顶角坐标。</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">输出最小面积，或者<font face="Times New Roman">-1.</font></span><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<h3 style="margin-top: 0pt; margin-bottom: 0pt"><span style="font-size: 12pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></h3></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】<br/>
2<br/>
<br/>
1 0<br/>
<br/>
1 2<br/>
<br/>
3 4<br/>
<br/>
4 3<br/>
<br/>
<br/>
【样例输入2】<br/>
2<br/>
<br/>
0 1<br/>
<br/>
0 1<br/>
<br/>
2 3<br/>
<br/>
2 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】<br/>
3<br/>
<br/>
【样例输出2】<br/>
-1<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
对于100%的数据，N ≤30 , |X|，|Y|≤10000<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2010福建集训">2010福建集训</a></p></div>

