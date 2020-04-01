
# Description

<div class="content"><div style="text-indent: 21pt">很多人都曾经听说过数独，但你是否听说过数谜（Karuro）呢？实际上，数谜是数独的更大（且更难）的兄弟问题，而且在日本也是非常受欢迎的。</div>
<div style="text-indent: 21pt">数谜问题和填字游戏类似，不过它要填的不是文字而是数字。数谜游戏的目标是用1-9填满所有空格，且这些数字相加的和满足相应的要求（或者称为“提示”），且在同一栏（“栏”是指一些水平或者竖直的连续的空格，用于提示的格子不算空格）不能填重复的数字。当所有格子按要求被填满后，这个数谜就看作被解决了。图1和图2是一个可能的数谜游戏示例。</div>
<div style="text-indent: 21pt">当然，直接求解数谜问题的话会比较困难。所以现在我们需要解决的是一个更简单的数谜问题。简单数谜的形状是一个(n+1）行乘(m+1)列的矩形。而简单数谜也只有两种要求，就是行要求和列要求，且分别处于第一行和第一列，其他格子则是空格，而左上角是忽略不计的。coolzzz同学爱好简单数谜，他已经给一些简单数谜填好了其中的一些空格。现在，他想寻求你的帮助，来帮他完成这些简单数谜。如图3所示，2和9是coolzzz同学已经填好的空格，图4则是一个基于图3 的一个可能的解答。</div>
<p><img height="314" width="578" alt="" src="/source/bzoj/2469/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTEwOS9iYmIuanBn.jpg"/></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">输入包含多组测试数据。第一行包含一个正整数</span><span lang="EN-US"><font face="Times New Roman">T</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示测试数据数目。每组数据第一行是</span><span lang="EN-US"><font face="Times New Roman">n(n&lt;10)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">和</span><span lang="EN-US"><font face="Times New Roman">m(m&lt;10)</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，表示数谜的形状的大小。接下来一行有</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个整数，是相应的行要求；然后一行是</span><span lang="EN-US"><font face="Times New Roman">m</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个整数，是相应的列要求。接下来的</span><span lang="EN-US"><font face="Times New Roman">n</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">行每行有</span><span lang="EN-US"><font face="Times New Roman">m</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个小于</span><span lang="EN-US"><font face="Times New Roman">10</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">的非负整数，</span><span lang="EN-US"><font face="Times New Roman">0</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">表示该空格还没有被填数字，其他表示</span><span lang="EN-US"><font face="Times New Roman">coolzzz</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">同学已经填好的数字。输入数据保证未填数字的空格不会超过</span><span lang="EN-US"><font face="Times New Roman">16</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个。</span></font></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">对于每组测试数据，输出若干行。如果基于</span><span lang="EN-US"><font face="Times New Roman">coolzzz</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">已填的结果，该数谜只有一个解，则输出该解；如果不止一个解，则输出一行“</span><span lang="EN-US"><font face="Times New Roman">Not unique.</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">”；如果没有解，则输出一行“</span><span lang="EN-US"><font face="Times New Roman">No answer.</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">”。</span></font></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
3 3<br/>
6 6 6<br/>
6 6 6<br/>
0 0 0<br/>
0 3 0<br/>
0 0 0<br/>
2 3<br/>
10 17<br/>
5 16 6<br/>
2 0 0<br/>
0 9 0<br/>
2 2<br/>
3 5<br/>
4 4<br/>
0 0<br/>
0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">Not unique.<br/>
2 7 1<br/>
3 9 5<br/>
No answer.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

