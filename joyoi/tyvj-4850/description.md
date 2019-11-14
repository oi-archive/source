# 

 
 # 题目描述 
<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">给出一个可以<span lang="EN-US">1</span>步将死对方的国际象棋棋盘，求其走法。数据保证有且仅有一种走法，而且不能吃棋子。<span lang="EN-US"><o:p></o:p></span></span></p> 

 
 # 输入格式 
<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">在键盘上输入<span lang="EN-US">8</span>行。<span lang="EN-US"><o:p></o:p></span></span></p>

<p><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:
宋体;mso-font-kerning:1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;
mso-bidi-language:AR-SA">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体;mso-font-kerning:
1.0pt;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:
AR-SA">每行<span lang="EN-US">8</span>个字符，第<span lang="EN-US">i</span>行第<span lang="EN-US">j</span>个字符表示位置为（<span lang="EN-US">i,j</span>）的棋子（<span lang="EN-US">1&le;i,j&le;8</span>）。<span lang="EN-US">0</span>代表无棋子，大写字母代表你的棋子，小写字母代</span><span style="font-family: 宋体; font-size: 14pt;">表对方的棋子。</span></p>

<table border="1" cellpadding="0" cellspacing="0" class="MsoTable15Grid1Light" style="border-collapse:collapse;border:none;mso-border-alt:solid #999999 .5pt;
 mso-border-themecolor:text1;mso-border-themetint:102;mso-yfti-tbllook:1536;
 mso-padding-alt:0cm 5.4pt 0cm 5.4pt">
	<tbody>
		<tr>
			<td style="width:51.9pt;border:solid #999999 1.0pt;
  mso-border-themecolor:text1;mso-border-themetint:102;mso-border-alt:solid #999999 .5pt;
  mso-border-themecolor:text1;mso-border-themetint:102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">字符<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
			<td style="width:51.9pt;border:solid #999999 1.0pt;
  mso-border-themecolor:text1;mso-border-themetint:102;border-left:none;
  mso-border-left-alt:solid #999999 .5pt;mso-border-left-themecolor:text1;
  mso-border-left-themetint:102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:
  text1;mso-border-themetint:102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">0<o:p></o:p></span></p>
			</td>
			<td style="width:51.9pt;border:solid #999999 1.0pt;
  mso-border-themecolor:text1;mso-border-themetint:102;border-left:none;
  mso-border-left-alt:solid #999999 .5pt;mso-border-left-themecolor:text1;
  mso-border-left-themetint:102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:
  text1;mso-border-themetint:102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">K(k)<o:p></o:p></span></p>
			</td>
			<td style="width:51.9pt;border:solid #999999 1.0pt;
  mso-border-themecolor:text1;mso-border-themetint:102;border-left:none;
  mso-border-left-alt:solid #999999 .5pt;mso-border-left-themecolor:text1;
  mso-border-left-themetint:102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:
  text1;mso-border-themetint:102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">Q(q)<o:p></o:p></span></p>
			</td>
			<td style="width:51.9pt;border:solid #999999 1.0pt;
  mso-border-themecolor:text1;mso-border-themetint:102;border-left:none;
  mso-border-left-alt:solid #999999 .5pt;mso-border-left-themecolor:text1;
  mso-border-left-themetint:102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:
  text1;mso-border-themetint:102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">R(r)<o:p></o:p></span></p>
			</td>
			<td style="width:51.9pt;border:solid #999999 1.0pt;
  mso-border-themecolor:text1;mso-border-themetint:102;border-left:none;
  mso-border-left-alt:solid #999999 .5pt;mso-border-left-themecolor:text1;
  mso-border-left-themetint:102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:
  text1;mso-border-themetint:102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">B(b)<o:p></o:p></span></p>
			</td>
			<td style="width:51.9pt;border:solid #999999 1.0pt;
  mso-border-themecolor:text1;mso-border-themetint:102;border-left:none;
  mso-border-left-alt:solid #999999 .5pt;mso-border-left-themecolor:text1;
  mso-border-left-themetint:102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:
  text1;mso-border-themetint:102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">N(n)<o:p></o:p></span></p>
			</td>
			<td style="width:51.9pt;border:solid #999999 1.0pt;
  mso-border-themecolor:text1;mso-border-themetint:102;border-left:none;
  mso-border-left-alt:solid #999999 .5pt;mso-border-left-themecolor:text1;
  mso-border-left-themetint:102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:
  text1;mso-border-themetint:102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">P(p)<o:p></o:p></span></p>
			</td>
		</tr>
		<tr>
			<td style="width:51.9pt;border:solid #999999 1.0pt;
  mso-border-themecolor:text1;mso-border-themetint:102;border-top:none;
  mso-border-top-alt:solid #999999 .5pt;mso-border-top-themecolor:text1;
  mso-border-top-themetint:102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:
  text1;mso-border-themetint:102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">含义<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
			<td style="width:51.9pt;border-top:none;border-left:none;
  border-bottom:solid #999999 1.0pt;mso-border-bottom-themecolor:text1;
  mso-border-bottom-themetint:102;border-right:solid #999999 1.0pt;mso-border-right-themecolor:
  text1;mso-border-right-themetint:102;mso-border-top-alt:solid #999999 .5pt;
  mso-border-top-themecolor:text1;mso-border-top-themetint:102;mso-border-left-alt:
  solid #999999 .5pt;mso-border-left-themecolor:text1;mso-border-left-themetint:
  102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:text1;mso-border-themetint:
  102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">无子<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
			<td style="width:51.9pt;border-top:none;border-left:none;
  border-bottom:solid #999999 1.0pt;mso-border-bottom-themecolor:text1;
  mso-border-bottom-themetint:102;border-right:solid #999999 1.0pt;mso-border-right-themecolor:
  text1;mso-border-right-themetint:102;mso-border-top-alt:solid #999999 .5pt;
  mso-border-top-themecolor:text1;mso-border-top-themetint:102;mso-border-left-alt:
  solid #999999 .5pt;mso-border-left-themecolor:text1;mso-border-left-themetint:
  102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:text1;mso-border-themetint:
  102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">王<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
			<td style="width:51.9pt;border-top:none;border-left:none;
  border-bottom:solid #999999 1.0pt;mso-border-bottom-themecolor:text1;
  mso-border-bottom-themetint:102;border-right:solid #999999 1.0pt;mso-border-right-themecolor:
  text1;mso-border-right-themetint:102;mso-border-top-alt:solid #999999 .5pt;
  mso-border-top-themecolor:text1;mso-border-top-themetint:102;mso-border-left-alt:
  solid #999999 .5pt;mso-border-left-themecolor:text1;mso-border-left-themetint:
  102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:text1;mso-border-themetint:
  102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">后<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
			<td style="width:51.9pt;border-top:none;border-left:none;
  border-bottom:solid #999999 1.0pt;mso-border-bottom-themecolor:text1;
  mso-border-bottom-themetint:102;border-right:solid #999999 1.0pt;mso-border-right-themecolor:
  text1;mso-border-right-themetint:102;mso-border-top-alt:solid #999999 .5pt;
  mso-border-top-themecolor:text1;mso-border-top-themetint:102;mso-border-left-alt:
  solid #999999 .5pt;mso-border-left-themecolor:text1;mso-border-left-themetint:
  102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:text1;mso-border-themetint:
  102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">车<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
			<td style="width:51.9pt;border-top:none;border-left:none;
  border-bottom:solid #999999 1.0pt;mso-border-bottom-themecolor:text1;
  mso-border-bottom-themetint:102;border-right:solid #999999 1.0pt;mso-border-right-themecolor:
  text1;mso-border-right-themetint:102;mso-border-top-alt:solid #999999 .5pt;
  mso-border-top-themecolor:text1;mso-border-top-themetint:102;mso-border-left-alt:
  solid #999999 .5pt;mso-border-left-themecolor:text1;mso-border-left-themetint:
  102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:text1;mso-border-themetint:
  102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">象<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
			<td style="width:51.9pt;border-top:none;border-left:none;
  border-bottom:solid #999999 1.0pt;mso-border-bottom-themecolor:text1;
  mso-border-bottom-themetint:102;border-right:solid #999999 1.0pt;mso-border-right-themecolor:
  text1;mso-border-right-themetint:102;mso-border-top-alt:solid #999999 .5pt;
  mso-border-top-themecolor:text1;mso-border-top-themetint:102;mso-border-left-alt:
  solid #999999 .5pt;mso-border-left-themecolor:text1;mso-border-left-themetint:
  102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:text1;mso-border-themetint:
  102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">马<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
			<td style="width:51.9pt;border-top:none;border-left:none;
  border-bottom:solid #999999 1.0pt;mso-border-bottom-themecolor:text1;
  mso-border-bottom-themetint:102;border-right:solid #999999 1.0pt;mso-border-right-themecolor:
  text1;mso-border-right-themetint:102;mso-border-top-alt:solid #999999 .5pt;
  mso-border-top-themecolor:text1;mso-border-top-themetint:102;mso-border-left-alt:
  solid #999999 .5pt;mso-border-left-themecolor:text1;mso-border-left-themetint:
  102;mso-border-alt:solid #999999 .5pt;mso-border-themecolor:text1;mso-border-themetint:
  102;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="69">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">兵<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
		</tr>
	</tbody>
</table> 

 
 # 输出格式 
<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">在屏幕上输出<span lang="EN-US">2</span>行。<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">第<span lang="EN-US">1</span>行：<span lang="EN-US">2</span>个正整数，<span lang="EN-US">x1</span>，<span lang="EN-US">y1</span>。<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">第<span lang="EN-US">2</span>行：<span lang="EN-US">2</span>个正整数，<span lang="EN-US">x2</span>，<span lang="EN-US">y2</span>。</span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">表示把位置为（<span lang="EN-US">x1,y1</span>）的棋子走到（<span lang="EN-US">x2,y2</span>）可以把对方将死。<span lang="EN-US"><o:p></o:p></span></span></p> 

 
 # 提示 
<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【样例输入】<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">00000000<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">00000000<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">0000k000<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">00000000<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">0B00000Q<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">0000N000<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">K0000000<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">0000r000<o:p></o:p></span></p>

<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【样例输出】<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">5&nbsp;8<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">2&nbsp;5<o:p></o:p></span></p>

<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【资源限制】</span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">时间限制：<span lang="EN-US">1</span>秒。内存限制：<span lang="EN-US">128MB</span>。<span lang="EN-US"><o:p></o:p></span></span></p> 
