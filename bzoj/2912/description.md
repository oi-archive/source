
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">在一个无限长的棋盘上玩一种跳棋游戏，其中棋盘被划分成许多区域，每一个区域中可以放置多个的棋子。规定某一个区域的编号为</span><span lang="EN-US"><font face="Times New Roman">0</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，在它开始往左边连续的区域编号为</span><span lang="EN-US"><font face="Times New Roman">-1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">-2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">-3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">…</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，在它的右边连续区域编号为</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">…</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，若区域</span><span lang="EN-US"><font face="Times New Roman">P</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">有棋子，那么棋子有两种跳法：</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">向左跳：则方格</span><span lang="EN-US"><font face="Times New Roman">P-1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">P-2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">中应增加一枚棋子，方格</span><span lang="EN-US"><font face="Times New Roman">P</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">中应减少一枚棋子。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">向右跳：则方格</span><span lang="EN-US"><font face="Times New Roman">P</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">P+1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">中应减少一枚棋子，方格</span><span lang="EN-US"><font face="Times New Roman">P+2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">中应增加一枚棋子。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">对于给定的初始棋局，经过若干步跳棋后，总可以找到一种目标，就是任意两个相邻的区域棋子数目不超过</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">。</span></font></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><span style="mso-tab-count: 1"><font face="Times New Roman">       </font></span></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">你的任务是对给定的一种初始棋局，找到最终的目标棋局。</span></font></p>
<p></p></div>

# Input

<div class="content"><div style="text-indent: 21pt"><font size="3">第一行为一个正整数n, 1 &lt;= n &lt;= 10000, 表示棋盘中放置棋子的状态数，下面的n行描述了每个状态，由两个用空格分隔的整数组成，第一个整数表示区域的位置（不超过10000），第二个整数表示该区域放置的棋子数目（不超过100000000）. </font></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><font size="3">写入最终的棋局，这一行包含若干个整数，其中每一个整数为有棋子的区域编号，所有的区域按从小到大排列。 </font></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
0 5<br/>
3 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">-4 -1 1 3 5<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

