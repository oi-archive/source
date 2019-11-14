
# Description

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 24pt; mso-char-indent-count: 2.0"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">XP</span><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">的百货商场很快就要开张啦，他希望能够确保百货商场的安全。<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 24pt; mso-char-indent-count: 2.0"><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">商场包括<span lang="EN-US">n</span>层，从<span lang="EN-US">1</span>到<span lang="EN-US">n</span>标号，每层楼都有一些小商店供顾客选购商品。百货商场的电梯连接着相邻的两层楼的商店（我们不妨假设<span lang="EN-US">1</span>楼到<span lang="EN-US">n</span>楼也是相邻的），对于每一层楼，一共有</span><span lang="EN-US" style="font-size: 15pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">K<sub>i</sub></span><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">个小商店，从<span lang="EN-US">1</span>到</span><span lang="EN-US" style="font-size: 15pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">K<sub>i</sub></span><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">标号。而百货商场总共有<span lang="EN-US">N</span>个小商店。<span lang="EN-US">XP</span>希望安置一些警卫在商店里看守，但是他有两个要求：<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">1.</span><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">一个商店最多由一个警卫看守<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">2.</span><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">电梯的两端不能同时放置警卫进行看守<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 24pt; mso-char-indent-count: 2.0"><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">在满足条件的情况下，<span lang="EN-US">XP</span>想知道最多能安置多少个警卫。<span lang="EN-US"><o:p></o:p></span></span></p>
<p></p></div>

# Input

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">输入第一行一个整数<span lang="EN-US">n</span>，表示百货商场有<span lang="EN-US">n</span>层。<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">接下来若干行，每行若干个数，每<span lang="EN-US">3</span>个数代表一个电梯。其中<span lang="EN-US">A,B,C</span>表示由一个电梯从第<span lang="EN-US">C</span>层的<span lang="EN-US">A</span>号房连向第<span lang="EN-US">C+1</span>层的<span lang="EN-US">B</span>号房（第<span lang="EN-US">n</span>层连向第<span lang="EN-US">1</span>层）。<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12"><span lang="EN-US"><o:p></o:p></span></span></p></div>

# Output

<div class="content"><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">输出一个整数，表示最多能安置的警卫个数。<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">Limits<o:p></o:p></span></p>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span lang="EN-US" style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">10</span><span style="font-size: 12pt; font-family: 宋体; mso-font-kerning: 0pt; mso-bidi-font-family: CMBX12">≤<span lang="EN-US">n</span>≤<span lang="EN-US">50<span style="mso-spacerun: yes">    </span><span style="mso-spacerun: yes">    </span>n</span>≤<span lang="EN-US">N</span>≤<span lang="EN-US">100<o:p></o:p></span></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
1  1  1  1  1  2  1  1  3  1  1  4  1  1  5  1  1  6  1  1  7  1  1  8  1  1  9  1  1  10<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

