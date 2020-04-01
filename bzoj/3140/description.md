
# Description

<div class="content"><p><span style="font-size: medium">最近在生物实验室工作的小T遇到了大麻烦。 <br/>
由于实验室最近升级的缘故，他的分格实验皿是一个长方体,其尺寸为a*b*c，a、b、c 均为正整数。为了实验的方便，它被划分为a*b*c个单位立方体区域，每个单位立方体尺寸<br/>
为1*1*1。用(i,j,k)标识一个单位立方体，1 ≤i≤a，1≤j≤b，1≤k≤c。这个实验皿已经很久没有人用了，现在，小T被导师要求将其中一些单位立方体区域进 行消毒操作（每个区域可以被重复消毒）。而由于严格的实验要求，他被要求使用一种特定 的F试剂来进行消毒。 这种F试剂特别奇怪，每次对尺寸为x*y*z的长方体区域（它由x*y*z个单位立方体组 成）进行消毒时，只需要使用min{x,y,z}单位的F试剂。F试剂的价格不菲，这可难倒了小 T。现在请你告诉他，最少要用多少单位的F试剂。(注：min{x,y,z}表示x、y、z中的最小 者。) <br/>
</span></p></div>

# Input

<div class="content"><div style="margin: 1.25pt 52.45pt 0pt 18pt; line-height: 15.5pt"><span style="font-size: medium"><span style="color: black">第一行是一个正整数</span><span style="color: black">D</span><span style="color: black">，表示数据组数。</span><span style="color: black">接下来是</span><span style="color: black">D</span><span style="color: black">组数据，每组数据开头是三个数</span><span style="color: black">a,b,c</span><span style="color: black">表示实验皿的尺寸。接下来会出现</span><span style="color: black">a</span><span style="color: black">个</span><span style="color: black">b </span><span style="color: black">行</span><span style="color: black">c</span><span style="color: black">列的用空格隔开的</span><span style="color: black">01</span><span style="color: black">矩阵，</span><span style="color: black">0</span><span style="color: black">表示对应的单位立方体不要求消毒，</span><span style="color: black">1</span><span style="color: black">表示对应的单位立方</span><span style="color: black">体需要消毒；例如，如果第</span><span style="color: black">1</span><span style="color: black">个</span><span style="color: black">01</span><span style="color: black">矩阵的第</span><span style="color: black">2</span><span style="color: black">行第</span><span style="color: black">3</span><span style="color: black">列为</span><span style="color: black">1</span><span style="color: black">，则表示单位立方体</span><span style="color: black">(1,2,3)</span><span style="color: black">需要被</span><span style="color: black">消毒。</span></span><span style="font-size: medium"><span style="color: black">输入保证满足</span><span style="color: black">a*b*c≤5000,T≤3</span><span style="color: black">。</span></span></div>
<p></p></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="margin: 1.25pt 52.3pt 0pt 18pt; line-height: 15pt; text-align: left; mso-line-height-rule: exactly; mso-layout-grid-align: none"><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">仅包含</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">D</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">行，每行一个整数，表示对应实验皿最少要用多少单位</span><span style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman"> </font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">的</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman">F</font></span><span style="font-size: 11pt; color: black; font-family: 宋体; mso-bidi-font-size: 12.0pt; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-font-kerning: 0pt">试剂。</span><span lang="EN-US" style="font-size: 11pt; color: black; mso-bidi-font-size: 12.0pt; mso-font-kerning: 0pt"><font face="Times New Roman"> <o:p></o:p></font></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">1                  <br/>
4  4 4<br/>
1  0 1 1<br/>
0  0 1 1<br/>
0  0 0 0<br/>
0  0 0 0<br/>
0  0 1 1<br/>
1  0 1 1<br/>
0  0 0 0<br/>
0  0 0 0<br/>
0  0 0 0<br/>
0  0 0 0<br/>
1  0 0 0<br/>
0  0 0 0<br/>
0  0 0 0<br/>
0  0 0 0<br/>
0  0 0 0<br/>
1  0 0 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3</span></div>

# Hint

<div class="content"><p></p><p><span style="line-height: 17px; font-size: 11pt; font-family: 宋体;">对于区域</span><span lang="EN-US" style="line-height: 17px; font-size: 11pt;"><font face="Times New Roman">(1,1,3)-(2,2,4)</font></span><span style="line-height: 17px; font-size: 11pt; font-family: 宋体;">和</span><span lang="EN-US" style="line-height: 17px; font-size: 11pt;"><font face="Times New Roman">(1,1,1)-(4,4,1)</font></span><span style="line-height: 17px; font-size: 11pt; font-family: 宋体;">消毒，分别花费</span><span lang="EN-US" style="line-height: 17px; font-size: 11pt;"><font face="Times New Roman">2</font></span><span style="line-height: 17px; font-size: 11pt; font-family: 宋体;">个单位和</span><span lang="EN-US" style="line-height: 17px; font-size: 11pt;"><font face="Times New Roman">1</font></span><span style="line-height: 17px; font-size: 11pt; font-family: 宋体;">个单位的</span><span lang="EN-US" style="line-height: 17px; font-size: 11pt;"><font face="Times New Roman">F</font></span><span style="line-height: 17px; font-size: 11pt; font-family: 宋体;">试剂。2017.5.26新加两组数据By Leoly，未重测.</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

