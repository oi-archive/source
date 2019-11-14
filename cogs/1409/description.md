# 题目描述


<h3>
【题目描述】
</h3>
<p>
<span style="font-family:宋体;">     </span><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;">幽灵模式是<span lang="EN-US">CF</span>中最受欢迎的模式之一，而巧妙地安放<span lang="EN-US">C4</span>炸弹则是在幽灵模式中取胜的关键。<span lang="EN-US"><!--?xml:namespace prefix = o ns = "urn:schemas-microsoft-com:office:office" /--><o:p></o:p></span></span> 
</p>
<p>
<span style="font-family:宋体;"> </span><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;">    一次，身为潜伏者张神牛把爆炸半径为<span lang="EN-US">r</span>的<span lang="EN-US">C4</span>炸弹安放在了坐标为<span lang="EN-US">(x,y)</span>的点上，在逃离到安全区域后，他突发奇想想计算一下有多少个保卫者会被炸死<span lang="EN-US">(</span>只要在爆炸半径的范围内的人都会被炸死<span lang="EN-US">)</span>，于是，他把<span lang="EN-US">n</span>位队员的坐标<span lang="EN-US">(</span>不包括他自己<span lang="EN-US">)</span>都发给了你，请你来帮他完成这个任务。</span> 
</p>
<h3>
【输入格式】
</h3>
<p>
<span style="font-family:宋体;"> </span><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;">输入文件为<span lang="EN-US">c4.in</span>。<span lang="EN-US"><br/>
</span>第<span lang="EN-US">1</span>行，三个整数<span lang="EN-US">x</span>，<span lang="EN-US">y</span>，<span lang="EN-US">r(</span>分别表示安放<span lang="EN-US">c4</span>的坐标和爆炸半径<span lang="EN-US">)</span>。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p>
<span style="font-family:宋体;"> </span><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;">第<span lang="EN-US">2</span>行，一个整数<span lang="EN-US">n(</span>表示除张神牛外的队员数<span lang="EN-US">)</span>。<span lang="EN-US"><o:p></o:p></span></span> 
</p>
<p>
<span style="font-family:宋体;"> </span><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;">第<span lang="EN-US">3</span>到<span lang="EN-US">n+2</span>行，每行是一位队员的坐标，其中“<span lang="EN-US">L</span>”代表潜伏者，“<span lang="EN-US">P</span>”代表保卫者。</span> 
</p>
<h3>
【输出格式】
</h3>
<p>
<span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">输出文件为<span lang="EN-US">c4.out</span>。<span lang="EN-US"><br/>
</span>输出仅<span lang="EN-US">1</span>行，即被炸死的保卫者的人数。</span> 
</p>
<h3>
【样例输入】
</h3>
<pre><span style="font-family:宋体;font-size:small;"><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;" lang="EN-US"> 
<p style="margin:0cm 0cm 0pt;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;" lang="EN-US">0 0 7</span> 
</p>

<p style="margin:0cm 0cm 0pt;" class="MsoNormal">
5
</p>

<p style="margin:0cm 0cm 0pt;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;" lang="EN-US">L 1 9<o:p></o:p></span> 
</p>

<p style="margin:0cm 0cm 0pt;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;" lang="EN-US">P 2 3<o:p></o:p></span> 
</p>

<p style="margin:0cm 0cm 0pt;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;" lang="EN-US">P 5 6</span> 
</p>

<p style="margin:0cm 0cm 0pt;" class="MsoNormal">
<span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-font-kerning:0pt;" lang="EN-US">L 3 1<o:p></o:p></span> 
</p>
<span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;" lang="EN-US">P 0 7</span></span></span></pre>
<h3>
【样例输出】
</h3>
<pre><span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;" lang="EN-US">2</span></pre>
<h3>
【提示】
</h3>
<p>
<span style="font-family:宋体;font-size:12pt;mso-bidi-font-family:宋体;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA;">所有数据均在<span lang="EN-US">integer</span>范围内</span> 
</p>
