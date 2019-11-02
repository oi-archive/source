# 

 
 # 题目描述 
<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">给出<span lang="EN-US">n</span>个大于<span lang="EN-US">1</span>的整数<span lang="EN-US">a<sub>i</sub></span>（<span lang="EN-US">1&le;a<sub>i</sub>&le;n</span>），它们的积一定可以表示为<span lang="EN-US">x<sup>y</sup></span>的形式（<span lang="EN-US">x,y</span>都为正整数），求最大的<span lang="EN-US">y</span>。<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体"><span lang="EN-US"><o:p></o:p></span></span></p> 

 
 # 输入格式 
<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">在键盘上输入（<span lang="EN-US">n+1</span>）行。<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">第<span lang="EN-US">1</span>行：<span lang="EN-US">1</span>个正整数，<span lang="EN-US">n</span>。</span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">第<span lang="EN-US">2</span>～（<span lang="EN-US">n+1</span>）行：<span lang="EN-US">1</span>个大于<span lang="EN-US">1</span>的整数，<span lang="EN-US">a<sub>i</sub></span>（<span lang="EN-US">1&le;a<sub>i</sub>&le;n</span>）。<span lang="EN-US"><o:p></o:p></span></span></p> 

 
 # 输出格式 
<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">在屏幕上输出<span lang="EN-US">1</span>行。</span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;1</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">个数，最大的<span lang="EN-US">y</span>。<span lang="EN-US"><o:p></o:p></span></span></p> 

 
 # 提示 
<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【样例输入】<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">4<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">5<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">40<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">2<o:p></o:p></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">9<o:p></o:p></span></p>

<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【样例输出】<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">2<o:p></o:p></span></p>

<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【样例解释】<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;5&times;40&times;2&times;9</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">＝<span lang="EN-US">3600</span>＝<span lang="EN-US">60<sup>2</sup></span>，<span lang="EN-US">2</span>是最大的<span lang="EN-US">y</span>。<span lang="EN-US"><o:p></o:p></span></span></p>

<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【数据规模】</span></p>

<table border="1" cellpadding="0" cellspacing="0" class="MsoTableGrid" style="border-collapse:collapse;border:none;mso-border-alt:solid windowtext .5pt;
 mso-yfti-tbllook:1536;mso-padding-alt:0cm 5.4pt 0cm 5.4pt">
	<tbody>
		<tr>
			<td style="width:138.25pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">测试点<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
			<td style="width:138.25pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">n<o:p></o:p></span></p>
			</td>
			<td style="width:138.3pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">a<sub>i</sub></span><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">（<span lang="EN-US">1&le;i&le;n</span>）<span lang="EN-US"><o:p></o:p></span></span></p>
			</td>
		</tr>
		<tr>
			<td style="width:138.25pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">1</span><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">～<span lang="EN-US">3<o:p></o:p></span></span></p>
			</td>
			<td style="width:138.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">1&le;n&le;20<o:p></o:p></span></p>
			</td>
			<td style="width:138.3pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span style="font-size:14.0pt;
  font-family:宋体;mso-bidi-font-family:宋体">乘积<span lang="EN-US">&le;2&times;10<sup>9</sup><o:p></o:p></span></span></p>
			</td>
		</tr>
		<tr>
			<td style="width:138.25pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">4</span><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">～<span lang="EN-US">6<o:p></o:p></span></span></p>
			</td>
			<td style="width:138.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">1&le;n&le;100<o:p></o:p></span></p>
			</td>
			<td style="width:138.3pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">2&le;a<sub>i</sub>&le;1,000<o:p></o:p></span></p>
			</td>
		</tr>
		<tr>
			<td style="width:138.25pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">7</span><span style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">～<span lang="EN-US">10<o:p></o:p></span></span></p>
			</td>
			<td style="width:138.25pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">1&le;n&le;10,000<o:p></o:p></span></p>
			</td>
			<td style="width:138.3pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt" valign="top" width="184">
			<p class="MsoNormal"><span lang="EN-US" style="font-size:14.0pt;font-family:宋体;mso-bidi-font-family:宋体">2&le;a<sub>i</sub>&le;100,000<o:p></o:p></span></p>
			</td>
		</tr>
	</tbody>
</table>

<p class="MsoNormal"><span style="font-size:14.0pt;
mso-bidi-font-size:12.0pt;font-family:宋体;mso-bidi-font-family:宋体">【资源限制】</span></p>

<p class="MsoNormal"><span lang="EN-US" style="font-size:
14.0pt;font-family:宋体;mso-bidi-font-family:宋体">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="font-size:14.0pt;
font-family:宋体;mso-bidi-font-family:宋体">时间限制：<span lang="EN-US">1</span>秒。内存限制：<span lang="EN-US">128MB</span>。<span lang="EN-US"><o:p></o:p></span></span></p> 
