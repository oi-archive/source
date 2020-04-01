
# Description

<div class="content"><div style="text-indent: 21pt; line-height: 150%"><span style="font-size: medium">ASCII图像是用ASCII字符拼出的图像。尽管有许多种ASCII图像，我们只考虑最原始的一种：用不同的ASCII字符表示格子被覆盖的百分比。</span></div>
<div style="text-indent: 21pt; line-height: 150%"><span style="font-size: medium">设OXY是一个笛卡尔坐标系，OX指向右方，OY指向上方。画布是一个(0,0)-(w,h)的矩形。一个像素是指(x,y)-(x+1,y+1)的正方形，其中0≤x&lt;w,0≤y&lt;h。画布上画着一个简单多边形。每一个像素可能被多边形部分地覆盖。每个像素覆盖情况与ASCII字符的对应关系如下表：</span></div>
<div style="text-indent: 21pt; line-height: 150%"></div>
<div style="text-indent: 21pt; line-height: 150%"><span style="font-size: medium">
<p class="Default" style="margin: 0cm 0cm 0pt; text-indent: 21pt; line-height: 150%; mso-char-indent-count: 1.75"><font size="3"><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: Verdana"><font face="宋体">你需要编写一个程序，对于给定的多边形，画出相应的</font></span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: 宋体">ASCII</span><font face="宋体"><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: Verdana">图案。</span><span lang="EN-US" style="font-family: &#34;Courier New&#34;; mso-bidi-font-family: 宋体"><o:p></o:p></span></font></font></p>
</span></div>
<p></p></div>

# Input

<div class="content"><p class="Default" style="margin: 0cm 0cm 0pt; text-indent: 21pt; line-height: 150%; mso-char-indent-count: 1.75"><font size="3"><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: Verdana"><font face="宋体">第一行包含三个整数</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">n,w,h(3</span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;"><font face="宋体">≤</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">n</span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;"><font face="宋体">≤</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">100,1</span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;"><font face="宋体">≤</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">w,h</span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;"><font face="宋体">≤</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">100)</span><font face="宋体"><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: Verdana">，分别表示多边形顶点个数，画布的宽度和高度。</span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体"><o:p></o:p></span></font></font></p>
<p class="Default" style="margin: 0cm 0cm 0pt; text-indent: 21pt; line-height: 150%; mso-char-indent-count: 1.75"><font size="3"><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: Verdana"><font face="宋体">接下来</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">n</span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: Verdana"><font face="宋体">行，每行一个坐标</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">x<sub>i</sub>,y<sub>i</sub>(0</span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;"><font face="宋体">≤</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">x<sub>i</sub></span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;"><font face="宋体">≤</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">w,0</span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;"><font face="宋体">≤</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">y<sub>i</sub></span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;"><font face="宋体">≤</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">h)</span><font face="宋体"><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: Verdana">，按顺时针给出多边形的各顶点坐标。</span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体"><o:p></o:p></span></font></font></p>
<p class="Default" style="margin: 0cm 0cm 0pt; text-indent: 21pt; line-height: 150%; mso-char-indent-count: 1.75"><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体"><font size="3"><o:p></o:p></font></span></p></div>

# Output

<div class="content"><p class="Default" style="margin: 0cm 0cm 0pt; text-indent: 21pt; line-height: 150%; mso-char-indent-count: 1.75"><font size="3"><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: Verdana"><font face="宋体">输出</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">h</span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: Verdana"><font face="宋体">行，每行</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">w</span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: Verdana"><font face="宋体">个</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">ASCII</span><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;"><font face="宋体">字符，表示给定多边形的</font></span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体">ASCII</span><font face="宋体"><span style="mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;">图像。</span><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体"><o:p></o:p></span></font></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; line-height: 150%"><span lang="EN-US" style="font-family: &#39;Courier New&#39;; mso-bidi-font-family: 宋体"><font size="3"><o:p></o:p></font></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 8 7<br/>
7 6<br/>
1 0<br/>
1 7<br/>
5 5<br/>
2 4<br/>
2 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">.$+.....<br/>
.##$+...<br/>
.#$oo+..<br/>
.##o....<br/>
.#o.....<br/>
.o......<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=梯形剖分">梯形剖分</a></p></div>

