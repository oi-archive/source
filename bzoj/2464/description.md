
# Description

<div class="content"><div style="text-indent: 21.75pt">小明最近喜欢玩一个游戏。给定一个n * m的棋盘，上面有两种格子#和@。游戏的规则很简单：给定一个起始位置和一个目标位置，小明每一步能向上，下，左，右四个方向移动一格。如果移动到同一类型的格子，则费用是0，否则费用是1。请编程计算从起始位置移动到目标位置的最小花费。</div></div>

# Input

<div class="content"><div><span>    </span>输入文件有多组数据。</div>
<div><span>    </span>输入第一行包含两个整数n，m，分别表示棋盘的行数和列数。</div>
<div><span>    </span>输入接下来的n行，每一行有m个格子（使用#或者@表示）。</div>
<div><span>    </span>输入接下来一行有四个整数x1, y1, x2, y2，分别为起始位置和目标位置。</div>
<div style="text-indent: 21.2pt">当输入n，m均为0时，表示输入结束。</div></div>

# Output

<div class="content"><div><span>    </span>对于每组数据，输出从起始位置到目标位置的最小花费。每一组数据独占一行。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
@#<br/>
#@<br/>
0 0 1 1<br/>
2 2<br/>
@@<br/>
@#<br/>
0 1 1 0<br/>
0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
0<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: 10.5pt; font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">对于</span><span lang="EN-US" style="font-size: 10.5pt; font-family: &#34;Courier New&#34;; mso-bidi-font-size: 10.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">100%</span><span style="font-size: 10.5pt; font-family: 宋体; mso-ascii-font-family: &#39;Courier New&#39;; mso-hansi-font-family: &#39;Courier New&#39;; mso-bidi-font-family: &#39;Courier New&#39;; mso-bidi-font-size: 10.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">的数据满足：</span><span lang="EN-US" style="font-size: 12pt; font-family: &#34;Times New Roman&#34;; mso-bidi-font-size: 10.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA; mso-fareast-font-family: 宋体">1 &lt; = n, m &lt;= 500</span><span style="font-size: 12pt; font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-size: 10.0pt; mso-font-kerning: 1.0pt; mso-ansi-language: EN-US; mso-fareast-language: ZH-CN; mso-bidi-language: AR-SA">。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

