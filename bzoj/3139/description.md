
# Description

<div class="content"><p><span style="font-size: medium">沫沫非常喜欢看足球赛，但因为沉迷于射箭游戏，错过了最近的一次足球联赛。此次联 赛共N支球队参加，比赛规则如下： <br/>
(1) 每两支球队之间踢一场比赛。 (2) 若平局，两支球队各得1分。 <br/>
(3) 否则胜利的球队得3分，败者不得分。 <br/>
尽管非常遗憾没有观赏到精彩的比赛，但沫沫通过新闻知道了每只球队的最后总得分， 然后聪明的她想计算出有多少种可能的比赛过程。 <br/>
譬如有3支球队，每支球队最后均积3分，那么有两种可能的情况：<br/>
 可能性1    可能性2 <br/>
球队  A  B  C  得分   球队 A  B  C  得分 <br/>
A        -  3  0  3             A     -  0  3  3 <br/>
B        0  -  3  3             B    3  -  0  3 <br/>
C        3  0  -  3            C    0  3  -  3 <br/>
但沫沫发现当球队较多时，计算工作量将非常大，所以这个任务就交给你了。请你计算 出可能的比赛过程的数目，由于答案可能很大，你只需要输出答案对109+7取模的结果</span></p></div>

# Input

<div class="content"><p class="MsoNormal" align="left" style="margin: 0.25pt 53.05pt 0pt 18pt; line-height: 16pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">第一行是一个正整数</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">N</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">，表示一共有</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">N</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">支球队。</span><span style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman"> </font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">接下来一行</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">N</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">个非负整数，依次表示各队的最后总得分。</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman"> <o:p></o:p></font></span></p>
<p class="MsoNormal" align="left" style="margin: 0.25pt 53.05pt 0pt 18pt; line-height: 16pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">输入保证</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">20%</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">的数据满足</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">N≤4</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">，</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">40%</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">的数据满足</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">N≤6</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">，</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">60%</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">的数据满足</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">N≤8</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">，</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">100%</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">的数据</span><span style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman"> </font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">满足</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">3≤N≤10</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">且至少存在一组解。</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman"> <o:p></o:p></font></span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">仅包含一个整数，表示答案对</span><span lang="EN-US" style="font-size: 11pt; color: black; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 12.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">10^9+7</span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-bidi-font-family: &#39;Times New Roman&#39;">取模的结果</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
4 3 6 4 </span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

