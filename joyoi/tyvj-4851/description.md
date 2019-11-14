# 

 
 # 题目描述 
<p><span lang="EN-US" style="font-size: 14pt; font-family: 宋体;">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size: 14pt; font-family: 宋体;">给出一组<span lang="EN-US">n</span>元一次方程组，求方程组的解。数据保证有且仅有一个解。</span></p>

<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体"><span lang="EN-US"><o:p></o:p></span></span></p> 

 
 # 输入格式 
<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">在键盘上输入（<span lang="EN-US">n+1</span>）行。<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">第<span lang="EN-US">1</span>行：<span lang="EN-US">1</span>个正整数，<span lang="EN-US">n</span>，表示方程组有<span lang="EN-US">n</span>个方程。</span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">第<span lang="EN-US">2</span>～（<span lang="EN-US">n+1</span>）行：<span lang="EN-US">1</span>个方程，运算符有<span lang="EN-US">+</span>，<span lang="EN-US">-</span>，<span lang="EN-US">*</span>，<span lang="EN-US">/</span>，<span lang="EN-US">(&nbsp;)</span>，<span lang="EN-US">=</span>。各部分不省略乘号。字母不区分大小写。<span lang="EN-US"><o:p></o:p></span></span></p> 

 
 # 输出格式 
<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">在屏幕上输出<span lang="EN-US">n</span>行。</span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">每行<span lang="EN-US">1</span>个未知数的解（四舍五入保留<span lang="EN-US">2</span>位小数）。未知数的解以小写形式按字典序从小到大排列输出。<span lang="EN-US"><o:p></o:p></span></span></p> 

 
 # 提示 
<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【样例输入】<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">2<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">x+1/2=1<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">2*(2*(x+y))=6<o:p></o:p></span></p>

<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【样例输出】<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">x=0.50<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">y=1.00<o:p></o:p></span></p>

<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【数据规模】<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">运算过程中所有数据的绝对值均不超过<span lang="EN-US">2<sup>31</sup></span>。<span lang="EN-US"><o:p></o:p></span></span></p>

<table border="1" cellpadding="0" cellspacing="0" class="MsoTableGrid" style="width:415.35pt;border-collapse:collapse;border:none;mso-border-alt:
 solid windowtext .5pt;mso-yfti-tbllook:1184;mso-padding-alt:0cm 5.4pt 0cm 5.4pt" width="554">
	<tbody>
		<tr>
			<td style="width:138.45pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">测试点<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
			<td style="width:138.45pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">n<o:p></o:p></span></p>
			</td>
			<td style="width:138.45pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal"><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:
  宋体">每个方程长度<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
		</tr>
		<tr>
			<td style="width:138.45pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">1</span><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">～<span lang="EN-US">3<o:p></o:p></span></span></p>
			</td>
			<td style="width:138.45pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">1&le;n&le;2<o:p></o:p></span></p>
			</td>
			<td style="width:138.45pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;
  mso-bidi-font-family:宋体">3&le;</span><span style="font-size:14.0pt;font-family:
  宋体;mso-bidi-font-family:宋体">每个方程长度<span lang="EN-US">&le;10<o:p></o:p></span></span></p>
			</td>
		</tr>
		<tr>
			<td style="width:138.45pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">4</span><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">～<span lang="EN-US">6<o:p></o:p></span></span></p>
			</td>
			<td style="width:138.45pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">1&le;n&le;10<o:p></o:p></span></p>
			</td>
			<td style="width:138.45pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal" style="line-height:17.25pt;mso-line-height-rule:exactly"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">3&le;</span><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">每个方程长度<span lang="EN-US">&nbsp;&le;100<o:p></o:p></span></span></p>
			</td>
		</tr>
		<tr>
			<td style="width:138.45pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">7</span><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">～<span lang="EN-US">10<o:p></o:p></span></span></p>
			</td>
			<td style="width:138.45pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">1&le;n&le;26<o:p></o:p></span></p>
			</td>
			<td style="width:138.45pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="185">
			<p class="MsoNormal" style="line-height:17.25pt;mso-line-height-rule:exactly"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">3&le;</span><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">每个方程长度<span lang="EN-US">&nbsp;&le;1000<o:p></o:p></span></span></p>
			</td>
		</tr>
	</tbody>
</table>

<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【资源限制】</span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">时间限制：<span lang="EN-US">1</span>秒。内存限制：128<span lang="EN-US">MB</span>。<span lang="EN-US"><o:p></o:p></span></span></p> 
