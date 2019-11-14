
# Description

<div class="content"><p class="MsoNormal" style="text-indent:21.0pt;mso-char-indent-count:2.0"><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">小欣在公园玩时发现有个玩小游戏的地方，小游戏的规则是：有两排标有字符的球，字符属于</span><span lang="EN-US">{A</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri">，</span><span lang="EN-US">T</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">，</span><span lang="EN-US">C</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri">，</span><span lang="EN-US">G}</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">，第</span><span lang="EN-US">1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri">排有</span><span lang="EN-US">N1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">个球，第</span><span lang="EN-US">2</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri">排有</span><span lang="EN-US">N2</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">个球（</span><span lang="EN-US">1&lt;=N1,N2&lt;=50000)</span><span style="font-family:宋体;mso-ascii-font-family:
Calibri;mso-hansi-font-family:Calibri">，在第</span><span lang="EN-US">1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">排的球中选出</span><span lang="EN-US">1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri">些来和第</span><span lang="EN-US">2</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">排的配对，每配出</span><span lang="EN-US">1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri">对就得</span><span lang="EN-US">1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">分，已经配对了的就不能再用了。小欣觉得这个游戏太简单了，不就是用个</span><span lang="EN-US">…</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri">就可以了吗？但他发现规则的最后</span><span lang="EN-US">1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">行说：配对的连线不能相交，相交的概念就是对于第</span><span lang="EN-US">1</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri">排的</span><span lang="EN-US">I</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">，</span><span lang="EN-US">J</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri">这</span><span lang="EN-US">2</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">个球，它们配对的分别是</span><span lang="EN-US">F[I]</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;
mso-hansi-font-family:Calibri">，</span><span lang="EN-US">F[J]</span><span style="font-family:宋体;mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">，它们相交当且仅当</span><span lang="EN-US">I&lt;J and F[I]&gt;F[J]</span><span style="font-family:宋体;
mso-ascii-font-family:Calibri;mso-hansi-font-family:Calibri">。这就难倒小欣了，现在请你帮助小欣编程求出最大得分。</span></p>
<p></p></div>

# Input

<div class="content"><div>
<p class="MsoNormal" align="left"><span style="font-family: 宋体;">第<span lang="EN-US">1</span>行<span lang="EN-US">: </span>两个数<span lang="EN-US">: N1</span>，<span lang="EN-US">N2<o:p></o:p></span></span></p>
<p class="MsoNormal" align="left"><span style="font-family: 宋体;">第<span lang="EN-US">2</span>行：<span lang="EN-US">N1</span>个字符</span></p>
<p class="MsoNormal" align="left"><span style="font-family: 宋体;"><span lang="EN-US"><o:p></o:p></span></span><span style="font-family: 宋体;">第<span lang="EN-US">3</span>行：<span lang="EN-US">N2</span>个字符<span lang="EN-US"><o:p></o:p></span></span></p>
<p class="MsoNormal" align="left"></p>
</div>
<div>
<p></p>
</div></div>

# Output

<div class="content"><p class="MsoNormal" align="left" style="text-indent: 5.25pt;"><span style="text-indent: 5.25pt;">2 2</span></p>
<p class="MsoNormal" align="left" style="text-indent: 5.25pt;">CT</p>
<p class="MsoNormal" align="left" style="text-indent: 5.25pt;">AG</p>
<p class="MsoNormal" align="left" style="text-indent: 5.25pt;"></p>
<p class="MsoNormal" align="left"></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">0</span></div>

# Sample Output

<div class="content"><span class="sampledata"></span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

