
# Description

<div class="content"><div style="margin: 6pt 0cm 0pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">扫雷是陆军战场上一项重要的而危险的任务。为此，AL军工厂专门研制了一种扫雷机器人。这种机器人是专门针对直线形雷阵设计的。所谓直线形雷阵，就是所有的地雷都埋在同一条直线上。例如图 1中黑点表示的雷阵就是直线形雷阵。</span></div>
<div style="margin: 6pt 0cm 0pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium"><img alt="" src="/source/bzoj/2520/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTExMS8xKDUpLmpwZw==.jpg"/></span></div>
<div align="center"></div>
<div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">AL军工厂生产的扫雷机器人的排雷方法只有一种，那就是安全引爆。每次，机器人在所有探测到的地雷中选择一颗引爆。被引爆的地雷会接连引爆不超过它的爆炸威力范围的其它地雷，这些被间接引爆的地雷还能引起进一步的连锁爆炸。例如图1中，用一个圆的半径表示地雷的爆炸威力。如果引爆2号雷，1、2号雷都会爆炸；如果引爆3号雷，4颗地雷全都会爆炸；而如果引爆4号雷，那就只有它一颗爆炸。</span></div>
<div style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">虽然是机器人，但引爆也是危险的。所以，扫雷机器人的订购人希望机器人能在实战中采取引爆次数尽可能少的排雷方案，即引爆次数尽可能少使得所有地雷都爆炸。于是AL军工厂想就此方面对机器人进行测试。为了评估机器人的表现，AL军工厂想知道在一个直线形雷阵（即输入的）完成排雷，至少要进行多少次引爆，至多要进行多少次引爆。现在，请你帮助AL军工厂回答这个问题。</span></div></div>

# Input

<div class="content"><div style="margin: 6pt 0cm; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">输入文件的第一行是一个正整数n，表示地雷的个数。</span></div>
<div style="margin: 6pt 0cm; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">接下去n行，按照地雷的位置顺序，每行描述一颗地雷。其中，第i+1行有两个整数，Xi,Di，分别是地雷的坐标和地雷的爆炸威力。也就是说，第i号地雷的爆炸能直接进一步引爆第j号地雷的条件是|xi-yi|&lt;=Di</span></div>
<div style="margin: 6pt 0cm; text-indent: 21pt; line-height: 150%"><span style="font-size: medium">输入文件保证：|Xi|&lt;=10^8,1&lt;=Di&lt;=10^8,且当i&lt;j时,Xi&lt;Yi</span></div></div>

# Output

<div class="content"><p class="MsoPlainText" style="margin: 6pt 0cm 12pt; text-indent: 21pt; line-height: 150%; mso-para-margin-top: .5gd; mso-char-indent-count: 2.0; mso-para-margin-right: 0cm; mso-para-margin-bottom: 1.0gd; mso-para-margin-left: 0cm"><span style="mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;; mso-bidi-font-family: &#39;Times New Roman&#39;"><font face="宋体" size="3">输出文件只有两行，每行一个整数。第一行的是最少引爆次数，第二行的是最大引爆次数。</font></span><span lang="EN-US" style="font-family: &#34;Times New Roman&#34;"><o:p></o:p></span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
0 1<br/>
2 2<br/>
8 7<br/>
11 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
4<br/>
</span></div>

# Hint

<div class="content"><p></p><p>N&lt;=10^6</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day2">Day2</a></p></div>

