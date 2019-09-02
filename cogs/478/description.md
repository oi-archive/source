# 题目描述


<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-indent:21pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">一天，警官抓获了<span style="font-family:&#39;Times New Roman&#39;;">N</span><span style="font-family:宋体;">个嫌犯，有</span><span style="font-family:&#39;Times New Roman&#39;;">M</span><span style="font-family:宋体;">个居民站了出来指证罪犯，每人说了一句话，形式有两种，</span><span style="font-family:&#39;Times New Roman&#39;;">“***</span><span style="font-family:宋体;">是罪犯</span><span style="font-family:&#39;Times New Roman&#39;;">”</span><span style="font-family:宋体;">，</span><span style="font-family:&#39;Times New Roman&#39;;">“***</span><span style="font-family:宋体;">不是罪犯</span><span style="font-family:&#39;Times New Roman&#39;;">”</span><span style="font-family:宋体;">。现在警长想借此考察居民的诚信程度，请作为警长副手的你帮忙，求出最多有多少个人在说谎，最少有多少个人在说谎。</span></span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">【输入格式】</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">    第一行，两个整数<span style="font-family:&#39;Times New Roman&#39;;">N</span><span style="font-family:宋体;">，</span><span style="font-family:&#39;Times New Roman&#39;;">M</span><span style="font-family:宋体;">，含义如题目描述所示。</span></span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-indent:24pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">第<span style="font-family:&#39;Times New Roman&#39;;">2—M+1</span><span style="font-family:宋体;">行，第</span><span style="font-family:&#39;Times New Roman&#39;;">i+1</span><span style="font-family:宋体;">行有一个整数</span><span style="font-family:&#39;Times New Roman&#39;;">X</span><span style="font-family:宋体;">，若</span><span style="font-family:&#39;Times New Roman&#39;;">X</span><span style="font-family:宋体;">大于零，表示</span></span><span style="font-size:12pt;font-family:&#39;宋体&#39;;mso-spacerun:&#39;yes&#39;;">有一个</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">居民说<span style="font-family:&#39;Times New Roman&#39;;">“X</span><span style="font-family:宋体;">号是罪犯</span><span style="font-family:&#39;Times New Roman&#39;;">”</span><span style="font-family:宋体;">；若</span><span style="font-family:&#39;Times New Roman&#39;;">X</span><span style="font-family:宋体;">小于零，表示</span></span><span style="font-size:12pt;font-family:&#39;宋体&#39;;mso-spacerun:&#39;yes&#39;;">有一个</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">居民说<span style="font-family:&#39;Times New Roman&#39;;">“-X</span><span style="font-family:宋体;">号不是罪犯</span><span style="font-family:&#39;Times New Roman&#39;;">”</span><span style="font-family:宋体;">。</span></span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">【输出格式】</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-indent:24pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">共有两行，第一行输出最多有多少个人在说谎，第二行输出最少有多少个人在说谎。</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">【样例输入】</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">2 7</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">1</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">2</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">1</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">-1</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">-2</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">1</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">-1</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">【样例输出】</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">4</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">3</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">如果<span style="font-family:&#39;Times New Roman&#39;;">1</span><span style="font-family:宋体;">号嫌犯不是罪犯，</span><span style="font-family:&#39;Times New Roman&#39;;">2</span><span style="font-family:宋体;">号也不是，则有四人说谎，如果</span><span style="font-family:&#39;Times New Roman&#39;;">1</span><span style="font-family:宋体;">号嫌犯是罪犯，而</span><span style="font-family:&#39;Times New Roman&#39;;">2</span><span style="font-family:宋体;">号也是，则有三人说谎。</span></span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">【数据规模】</span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-indent:24pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:&#39;Times New Roman&#39;;">30%</span><span style="font-family:宋体;">的数据，</span><span style="font-family:&#39;Times New Roman&#39;;">N&lt;=10,M&lt;=500;</span></span><span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;"><o:p></o:p></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-indent:24pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">对于<span style="font-family:&#39;Times New Roman&#39;;">100%</span><span style="font-family:宋体;">的数据，</span><span style="font-family:&#39;Times New Roman&#39;;">N&lt;=1000,M&lt;=50000;</span></span> 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-indent:24pt;text-align:left;">
 
</p>
<p class="p0" style="margin-top:0pt;margin-bottom:0pt;text-indent:24pt;text-align:left;">
<span style="font-size:12pt;font-family:&#39;Times New Roman&#39;;mso-spacerun:&#39;yes&#39;;">by kily</span> 
</p>
<!--EndFragment-->
