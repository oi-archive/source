# 题目描述


<h3>
【题目描述】
</h3>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">小</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">F</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">的学校在城市的一个偏僻角落，所有学生都只好在学校吃饭。学校有一个食堂，虽然简陋，但食堂大厨总能做出让同学们满意的菜肴。当然，不同的人口味也不一定相同，但每个人的口味都可以用一个非负整数表示。</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><!--?xml:namespace prefix = o ns = "urn:schemas-microsoft-com:office:office" /--><o:p></o:p></span> 
</p>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">由于人手不够，食堂每次只能为一个人做菜。做每道菜所需的时间是和前一道菜有关的，若前一道菜的对应的口味是</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">a</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">，这一道为</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">b</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">，则做这道菜所需的时间为（</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">a</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"> or </span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">b</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">）</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">-</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">（</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">a</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"> and </span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">b</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">），而做第一道菜是不需要计算时间的。其中，</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">or</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">和</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">and</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">表示整数逐位或运算及逐位与运算，</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">C</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">语言中对应的运算符为</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">”</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">｜</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">”</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">和</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">”</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">＆</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">”</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">。</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">学生数目相对于这个学校还是比较多的，吃饭做菜往往就会花去不少时间。因此，学校食堂偶尔会不按照大家的排队顺序做菜，以缩短总的进餐时间。</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">虽然同学们能够理解学校食堂的这种做法，不过每个同学还是有一定容忍度的。也就是说，队伍中的第</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">i</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">个同学，最多允许紧跟他身后的</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">B</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;vertical-align:sub;mso-spacerun:&#34;">i</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">个人先拿到饭菜。一旦在此之后的任意同学比当前同学先拿到饭，当前同学将会十分愤怒。因此，食堂做菜还得照顾到同学们的情绪。</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">现在，小</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">F</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">想知道在满足所有人的容忍度这一前提下，自己的学校食堂做完所有菜最少需要多少时间。</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<!--EndFragment-->
<h3>
【输入格式】
</h3>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">dining.in</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">的第一行包含一个正整数</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">C</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">，表示测试点的数据组数。</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">每组数据的第一行包含一个正整数</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">N</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">，表示同学数。</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">每组数据的第二行起共</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">N</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">行，每行包含两个用空格分隔的非负整数</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">T</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;vertical-align:sub;mso-spacerun:&#34;">i</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">和</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">B</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;vertical-align:sub;mso-spacerun:&#34;">i</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">，表示按队伍顺序从前往后的每个同学所需的菜的口味和这个同学的忍受度。</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">每组数据之间没有多余空行。</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<!--EndFragment-->
<h3>
【输出格式】
</h3>
<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">输出文件</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">dining.out</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">包含</span><span style="color:#000000;font-family:&#34;font-size:14pt;font-style:italic;mso-spacerun:&#34;">C</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">行，每行一个整数，表示对应数据中食堂完成所有菜所需的最少时间。</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<!--EndFragment-->
<h3>
【样例输入】
</h3>
<pre><p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">2</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>

<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">5</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>

<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">5 2</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>

<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">4 1</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>

<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">12 0</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>

<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">3 3</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>

<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">2 2</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>

<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">2</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>

<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">5 0</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>

<p style="text-indent:21pt;margin-top:0pt;margin-bottom:0pt;" class="p0">
<span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;">4 0</span><span style="color:#000000;font-family:&#34;font-size:14pt;mso-spacerun:&#34;"><o:p></o:p></span> 
</p>
<!--EndFragment--></pre>
<h3>
【样例输出】
</h3>
<pre>16</pre>
<pre> 1</pre>
<h3>
【提示】
</h3>
<p>
DP
【数据规模和约定】
对于30%的数据，满足1 ≤ N ≤ 20。 
</p>
<p>
对于100%的数据，满足1 ≤ N ≤ 1,000，0 ≤ Ti ≤ 1,000，0 ≤ Bi ≤ 7，1 ≤ C ≤ 5。 
</p>
<p>
存在30%的数据，满足0 ≤ Bi ≤ 1。
存在65%的数据，满足0 ≤ Bi ≤ 5。
存在45%的数据，满足0 ≤ Ti ≤ 130。
</p>
<h3>
【来源】
</h3>
<p>
BZOJ————SDOI
</p>
