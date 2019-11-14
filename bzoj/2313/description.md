
# Description

<div class="content"><div class="Section0" style="layout-grid:  15.6pt none">
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-align: center"><span style="font-size: 14pt; font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">小Z最近在研究数学，尤其是分组问题最令小Z感兴趣。</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">分组问题是指将n个不同的人分到若干组中，使得每个组中的人数一样，求方案数。譬如n=4时，不同的分组方案如下：</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 39pt; text-indent: -18pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">1．</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">{1}{2}{3}{4}</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 39pt; text-indent: -18pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">2．</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">{1,2}{3,4}</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 39pt; text-indent: -18pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">3．</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">{1,3}{2,4}</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 39pt; text-indent: -18pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">4．</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">{1,4}{2,3}</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; margin-left: 39pt; text-indent: -18pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">5．</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">{1,2,3,4}</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">小Z自然不满足于此，他还想用m种颜色给这些方案染色，再计算染色的方案数。如n=4 m=2时，一共有5种分组方案，那么答案则是2*2*2*2*2=32种。</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-align: left"><span style="font-weight: bold; font-size: 12pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">Your Task</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">给定n m，计算染色的方案数。</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">由于答案可能很大，请输出它对</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;Cambria Math&#39;; mso-spacerun: &#39;yes&#39;">10^9-401</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">取模后的结果。</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: justify"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;Cambria Math&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
</div>
<!--EndFragment--></div>

# Input

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">第一行T表示数据组数</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每组数据，仅一行n m</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Output

<div class="content"><p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-indent: 21pt; text-align: left"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(0,0,0); font-family: &#39;宋体&#39;; mso-spacerun: &#39;yes&#39;">对于每组数据，在一行中输出答案</span><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p>
<p class="p0" style="margin-top: 0pt; margin-bottom: 0pt; text-align: justify"><span style="font-weight: normal; font-size: 10.5pt; color: rgb(255,255,255); font-family: &#39;Times New Roman&#39;; mso-spacerun: &#39;yes&#39;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
<br/>
4 2<br/>
<br/>
2 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">32<br/>
9<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
100%：T≤10，1≤n,m≤2*10^9<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

