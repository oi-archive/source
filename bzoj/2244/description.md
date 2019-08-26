
# Description

<div class="content"><p class="NOI0" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">某国为了防御敌国的导弹袭击，发展出一种导弹拦截系统。但是这种导弹拦截系统有一个缺陷：虽然它的第一发炮弹能够到达任意的高度、并且能够拦截任意速度的导弹，但是以后每一发炮弹都不能高于前一发的高度，其拦截的导弹的飞行速度也不能大于前一发。某天，雷达捕捉到敌国的导弹来袭。由于该系统还在试用阶段，所以只有一套系统，因此有可能不能拦截所有的导弹。</span><font face="Times New Roman"> </font></font></p>
<p class="NOI0" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">在不能拦截所有的导弹的情况下，我们当然要选择使国家损失最小、也就是拦截导弹的数量最多的方案。但是拦截导弹数量的最多的方案有可能有多个，如果有多个最优方案，那么我们会随机选取一个作为最终的拦截导弹行动蓝图。</font></span></p>
<p class="NOI0" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">我方间谍已经获取了所有敌军导弹的高度和速度，你的任务是计算出在执行上述决策时，每枚导弹被拦截掉的概率。</font></span></p>
<p></p></div>

# Input

<div class="content"><p class="NOI0" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第一行包含一个正整数</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示敌军导弹数量；</span></font></p>
<p class="NOI0" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">下面</font></span><span lang="EN-US"><span style="position: relative; top: 3pt; mso-text-raise: -3.0pt"><v:shape id="_x0000_i1025" type="#_x0000_t75" style="width: 6.75pt; height: 15.75pt"><font size="3"><font face="Times New Roman"> <v:imagedata src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image001.png" o:title="" chromakey="white"></v:imagedata></font></font></v:shape></span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">行按顺序给出了敌军所有导弹信息：</font></span></p>
<p class="NOI0" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第</span><span lang="EN-US"><font face="Times New Roman">i+1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行包含</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个正整数</span><span lang="EN-US"><font face="Times New Roman">h<sub>i</sub></font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">v<sub>i</sub></font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，分别表示第</span></font><span lang="EN-US"><span style="position: relative; top: 3pt; mso-text-raise: -3.0pt"><v:shape id="_x0000_i1026" type="#_x0000_t75" style="width: 4.5pt; height: 15.75pt"><font size="3"><font face="Times New Roman"> <v:imagedata src="file:///C:\DOCUME~1\ADMINI~1\LOCALS~1\Temp\msohtml1\01\clip_image003.png" o:title="" chromakey="white"></v:imagedata></font></font></v:shape></span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">枚导弹的高度和速度。</font></span></p>
<p class="NOI0" style="margin: 0cm 0cm 0pt"></p></div>

# Output

<div class="content"><p class="NOI0" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">输出包含两行。</font></span></p>
<p class="NOI0" style="margin: 0cm 0cm 0pt"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;"><font size="3">第一行为一个正整数，表示最多能拦截掉的导弹数量；</font></span></p>
<p class="NOI0" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">第二行包含</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个</span><span lang="EN-US"><font face="Times New Roman">0</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">到</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">之间的实数，第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个数字表示第</span><span lang="EN-US"><font face="Times New Roman">i</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">枚导弹被拦截掉的概率（你可以保留任意多位有效数字）。</span></font></p>
<p class="NOI1" style="margin: 0cm 0cm 0pt"></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
<br/>
3 30<br/>
<br/>
4 40<br/>
<br/>
6 60<br/>
<br/>
3 30<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
0.33333 0.33333 0.33333 1.00000<br/>
<br/>
【数据规模和约定】<br/>
<br/>
<br/>
对于100%的数据，1≤n≤5*104， 1≤hi ，vi≤109；<br/>
<br/>
均匀分布着约30%的数据，所有vi均相等。<br/>
<br/>
均匀分布着约50%的数据，满足1≤hi ，vi≤1000。<br/>
</span></div>

# Hint

<div class="content"><p></p><p>鸣谢<a href="http://61.187.179.132/JudgeOnline/userinfo.php?user=kac"><font color="#0000ff">kac</font></a>提供sj程序！</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=第一轮day2">第一轮day2</a></p></div>

