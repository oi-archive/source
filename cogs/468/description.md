# 题目描述


<h2 style="margin:auto 0cm;text-align:center;" align="center">
<span style="color:black;"><span style="font-family:宋体;">超级钢琴</span></span> 
</h2>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-outline-level:2;" align="left">
<b><span style="font-size:18pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">【问题描述】<span lang="EN-US"><o:p></o:p></span></span></b> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:21pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">小<span lang="EN-US">Z</span>是一个小有名气的钢琴家，最近<span lang="EN-US">C</span>博士送给了小<span lang="EN-US">Z</span>一架超级钢琴，小<span lang="EN-US">Z</span>希望能够用这架钢琴创作出世界上最美妙的音乐。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:21pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">这架超级钢琴可以弹奏出<span lang="EN-US">n</span>个音符，编号为<span lang="EN-US">1</span>至<span lang="EN-US">n</span>。第<span lang="EN-US">i</span>个音符的美妙度为<span lang="EN-US">A<sub>i</sub></span>，其中<span lang="EN-US">A<sub>i</sub></span>可正可负。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:21pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">一个<span lang="EN-US">“</span>超级和弦<span lang="EN-US">”</span>由若干个<b><u>编号连续的</u></b>音符组成，包含的音符个数不少于<span lang="EN-US">L</span>且不多于<span lang="EN-US">R</span>。我们定义超级和弦的<b><u>美妙度</u></b>为其包含的所有音符的美妙度之和。两个超级和弦被认为是相同的，当且仅当这两个超级和弦所包含的音符集合是相同的。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:21pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">小<span lang="EN-US">Z</span>决定创作一首由<span lang="EN-US">k</span>个超级和弦组成的乐曲，为了使得乐曲更加动听，小<span lang="EN-US">Z</span>要求该乐曲由<span lang="EN-US">k</span>个<b><u>不同的</u></b>超级和弦组成。我们定义一首<b><u>乐曲的美妙度</u></b>为其所包含的所有超级和弦的美妙度之和。小<span lang="EN-US">Z</span>想知道他能够创作出来的乐曲美妙度最大值是多少。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-outline-level:2;" align="left">
<b><span style="font-size:18pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">【输入格式】<span lang="EN-US"><o:p></o:p></span></span></b> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:21pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">输入文件名为<span lang="EN-US">piano.in</span>。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:21pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">输入文件第一行包含四个正整数<span lang="EN-US">n, k, L, R</span>。其中<span lang="EN-US">n</span>为音符的个数，<span lang="EN-US">k</span>为乐曲所包含的超级和弦个数，<span lang="EN-US">L</span>和<span lang="EN-US">R</span>分别是超级和弦所包含音符个数的下限和上限。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">接下来<span lang="EN-US">n</span>行，每行包含一个整数<span lang="EN-US">A<sub>i</sub></span>，表示按编号从小到大每个音符的美妙度。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-outline-level:2;" align="left">
<b><span style="font-size:18pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">【输出格式】<span lang="EN-US"><o:p></o:p></span></span></b> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:21pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">输出文件为<span lang="EN-US">piano.out</span>。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:21pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">输出文件只有一个整数，表示乐曲美妙度的最大值。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-outline-level:2;" align="left">
<b><span style="font-size:18pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">【样例输入】<span lang="EN-US"><o:p></o:p></span></span></b> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;" lang="EN-US">4 3 2 3<o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;" lang="EN-US">3<o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;" lang="EN-US">2<o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;" lang="EN-US">-6<o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;" lang="EN-US">8<o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-outline-level:2;" align="left">
<b><span style="font-size:18pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">【样例输出】<span lang="EN-US"><o:p></o:p></span></span></b> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;" lang="EN-US">11</span> 
</p>
<p>
<br/>
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<b><span style="font-size:18pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">【样例说明】<span lang="EN-US"><o:p></o:p></span></span></b> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">共有<span lang="EN-US">5</span>种不同的超级和弦：<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<ol style="margin-top:0cm;" type="1">
<li class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-list:l0 level1 lfo1;tab-stops:list 36.0pt;">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">音符<span lang="EN-US">1 ~ 2</span>，美妙度为<span lang="EN-US">3 + 2 = 5<o:p></o:p></span></span> 
</li>
<li class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-list:l0 level1 lfo1;tab-stops:list 36.0pt;">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">音符<span lang="EN-US">2 ~ 3</span>，美妙度为<span lang="EN-US">2 + (-6) = -4<o:p></o:p></span></span> 
</li>
<li class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-list:l0 level1 lfo1;tab-stops:list 36.0pt;">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">音符<span lang="EN-US">3 ~ 4</span>，美妙度为<span lang="EN-US">(-6) + 8 = 2<o:p></o:p></span></span> 
</li>
<li class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-list:l0 level1 lfo1;tab-stops:list 36.0pt;">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">音符<span lang="EN-US">1 ~ 3</span>，美妙度为<span lang="EN-US">3 + 2 + (-6) = -1<o:p></o:p></span></span> 
</li>
<li class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-list:l0 level1 lfo1;tab-stops:list 36.0pt;">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">音符<span lang="EN-US">2 ~ 4</span>，美妙度为<span lang="EN-US">2 + (-6) + 8 = 4<o:p></o:p></span></span> 
</li>
</ol>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">最优方案为：乐曲由和弦<span lang="EN-US">1</span>，和弦<span lang="EN-US">3</span>，和弦<span lang="EN-US">5</span>组成，美妙度为<span lang="EN-US">5 + 2 + 4 = 11</span>。</span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;mso-outline-level:2;" align="left">
<b><span style="font-size:18pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">【数据规模和约定】<span lang="EN-US"><o:p></o:p></span></span></b> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:18pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">总共<span lang="EN-US">10</span>个测试点，数据范围满足：</span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:18pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;"><span lang="EN-US"><o:p><img alt="" src="/images/clip_image001.png" height="430" width="570"/></o:p></span></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;" lang="EN-US"><o:p></o:p></span> 
</p>
<p class="MsoNormal" style="margin:0cm 0cm 0pt;text-indent:21pt;text-align:left;mso-pagination:widow-orphan;" align="left">
<span style="font-size:12pt;font-family:宋体;mso-font-kerning:0pt;mso-bidi-font-family:宋体;">所有数据满足：<span lang="EN-US">-1000 ≤ A<sub>i</sub> ≤ 1000</span>，<span lang="EN-US">1 ≤ L ≤ R ≤ n</span>且保证一定存在满足要求的乐曲。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
