
# Description

<div class="content"><div><span>       </span>给定n个不同颜色的球，每个球都有一个分数，同时有m个瓶子，每个瓶子都有固定的容量。现在，你必须把球放到瓶子里面。请编程计算最多能放多少个球到这些瓶子里。</div></div>

# Input

<div class="content"><div style="text-indent: 21.2pt">输入包含多组数据。</div>
<div style="text-indent: 21.2pt">每组数据的第一行为两个整数n, m，分别表示球的个数和瓶子的个数。</div>
<div style="text-indent: 21.2pt">接下来的n行，每一行包含一个整数p，表示相应的球的分数。</div>
<div style="text-indent: 21.2pt">接下来的m行，每一行包含两个整数c和q, 分别表示每个瓶子的容量（最多能装多少个球）和分数上界（放进该瓶子的每个球的分数都不能超过去q）。</div>
<div style="text-indent: 21.2pt">当输入n，m均为0时，表示输入结束。</div></div>

# Output

<div class="content"><div style="text-indent: 21pt">对于每组数据，输出两个整数B和S，分别表示总共能放进瓶子里的球的最大数目，以及在这个前提下，放进瓶子里面的所有球的最大分数总和。B和S以空格隔开，每组答案独占一行。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 1<br/>
2<br/>
3<br/>
1 2<br/>
2 2<br/>
4<br/>
5<br/>
2 4<br/>
2 5<br/>
0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2<br/>
2 9<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 21pt; mso-char-indent-count: 2.0"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">对于全部的数据，有</span><span lang="EN-US"><font face="Times New Roman">1&lt;=n&lt;=200</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">0&lt;=m&lt;=200</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US" style="font-size: 12pt; mso-bidi-font-size: 10.0pt"><font face="Times New Roman">1 &lt;= p &lt;= 10^6, 0 &lt;= c &lt;= 200, 1 &lt;= q &lt;= 10^6.</font></span></font></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

