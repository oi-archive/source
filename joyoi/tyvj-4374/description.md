# 

 
 # 题目背景 
<p>印尼巴厘岛的公路上有许多的雕塑，我们来关注它的一条主干道。&nbsp;</p> 

 
 # 题目描述 
<p>在这条主干道上一共有<img align="absmiddle" alt="N" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_Tg==.latex" />座雕塑，为方便起见，我们把这些雕塑从1到<img align="absmiddle" alt="N" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_Tg==.latex" />连续地进行标号，其中第<img align="absmiddle" alt="i" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_aQ==.latex" />座雕塑的年龄是<img align="absmiddle" alt="Y_{i}" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_WV97aX0=.latex" />年。为了使这条路的环境更加优美，政府想把这些雕塑分成若干组，并通过在组与组之间种上一些树，来吸引更多的游客来巴厘岛。&nbsp;</p>

<p>下面是将雕塑分组的规则：&nbsp;</p>

<p>这些雕塑必须被分为恰好<img align="absmiddle" alt="X" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_WA==.latex" />组，其中<img align="absmiddle" alt="A\leq X\leq B" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_QVxsZXEmYW1wO3NwYWNlO1hcbGVxJmFtcDtzcGFjZTtC.latex" />，每组必须含有至少一个雕塑，每个雕塑也必须属于且只属于一个组。同一组中的所有雕塑必须位于这条路的连续一段上。&nbsp;</p>

<p>当雕塑被分好组后，对于每个组，我们首先计算出该组所有雕塑的年龄和，然后计算将每组年龄和按位<strong><u>取或</u></strong>（即对上述年龄和按位取或），我们把<strong><u>按位取或</u></strong>后得到的结果称为这一分组的最终优美度（颜值）。&nbsp;</p>

<p>请问政府能得到的最小的最终优美度（<strong>颜值</strong>）是多少？</p> 

 
 # 输入格式 
<p style="margin: 0cm 0cm 0pt; text-indent: 21pt;"><span style="mso-bidi-font-size:10.5pt;font-family:宋体;mso-ascii-font-family:&quot;Times New Roman&quot;;&#10;mso-hansi-font-family:&quot;Times New Roman&quot;"><font color="#000000" size="3">输入的第一行包含三个用空格分开的整数</font></span><img align="absmiddle" alt="N,A,B" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_TixBLEI=.latex" /><span lang="EN-US" style="font-size:10.5pt;mso-bidi-font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;&#10;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:&#10;minor-fareast;mso-hansi-theme-font:minor-latin;mso-bidi-font-family:&quot;Times New Roman&quot;;&#10;mso-bidi-theme-font:minor-bidi;position:relative;top:4.0pt;mso-text-raise:-4.0pt;&#10;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA"><v:shapetype coordsize="21600,21600" filled="f" id="_x0000_t75" o:preferrelative="t" o:spt="75" path="m@4@5l@4@11@9@11@9@5xe" stroked="f"><v:stroke joinstyle="miter"><v:f eqn="if lineDrawn pixelLineWidth 0"><v:f eqn="sum @0 1 0"><v:f eqn="sum 0 0 @1"><v:f eqn="prod @2 1 2"><v:f eqn="prod @3 21600 pixelWidth"><v:f eqn="prod @3 21600 pixelHeight"><v:f eqn="sum @0 0 1"><v:f eqn="prod @6 1 2"><v:f eqn="prod @7 21600 pixelWidth"><v:f eqn="sum @8 21600 0"><v:f eqn="prod @7 21600 pixelHeight"><v:f eqn="sum @10 21600 0"></v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:f></v:f><v:path gradientshapeok="t" o:connecttype="rect" o:extrusionok="f"><o:lock aspectratio="t" v:ext="edit"></o:lock></v:path></v:stroke></v:shapetype><v:shape id="_x0000_i1025" style="width:36pt;&#10; height:15pt" type="#_x0000_t75"><v:imagedata chromakey="white" o:title="" src="file:///C:\Users\lifu\AppData\Local\Temp\msohtmlclip1\01\clip_image001.png">&nbsp;</v:imagedata></v:shape></span><span style="mso-bidi-font-size:10.5pt;font-family:&#10;宋体;mso-ascii-font-family:&quot;Times New Roman&quot;;mso-hansi-font-family:&quot;Times New Roman&quot;"><font color="#000000" size="3">。</font></span></p>

<p style="margin: 0cm 0cm 0pt; text-indent: 21pt;"><span style="mso-bidi-font-size:10.5pt;font-family:宋体;mso-ascii-font-family:&quot;Times New Roman&quot;;&#10;mso-hansi-font-family:&quot;Times New Roman&quot;"><font color="#000000" size="3">第二行包含</font></span><img align="absmiddle" alt="N" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_Tg==.latex" /><span style="mso-bidi-font-size:10.5pt;font-family:宋体;mso-ascii-font-family:&quot;Times New Roman&quot;;&#10;mso-hansi-font-family:&quot;Times New Roman&quot;"><font color="#000000" size="3">个用空格分开的整数</font></span><img align="absmiddle" alt="Y_{1},Y_{2},...,Y_{N}" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_WV97MX0sWV97Mn0sLi4uLFlfe059" /><span lang="EN-US" style="font-size:10.5pt;mso-bidi-font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;&#10;mso-ascii-theme-font:minor-latin;mso-fareast-font-family:宋体;mso-fareast-theme-font:&#10;minor-fareast;mso-hansi-theme-font:minor-latin;mso-bidi-font-family:&quot;Times New Roman&quot;;&#10;mso-bidi-theme-font:minor-bidi;position:relative;top:2.5pt;mso-text-raise:-2.5pt;&#10;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN;mso-bidi-language:AR-SA"><v:shape id="_x0000_i1025" style="width:51pt;height:12pt" type="#_x0000_t75"><v:imagedata chromakey="white" o:title="" src="file:///C:\Users\lifu\AppData\Local\Temp\msohtmlclip1\01\clip_image002.png">&nbsp;</v:imagedata></v:shape></span><span style="mso-bidi-font-size:10.5pt;font-family:&#10;宋体;mso-ascii-font-family:&quot;Times New Roman&quot;;mso-hansi-font-family:&quot;Times New Roman&quot;"><font color="#000000" size="3">。</font></span></p>

<p>&nbsp;</p> 

 
 # 输出格式 
<p>输出一行一个整数，表示最小的最终优美度（<strong>颜值</strong>）。</p> 

 
 # 提示 
<pre>
【输入输出样例】</pre>

<table align="center" border="1" cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td style="width:308px;">
			<pre align="center">
<strong>sculpture.in</strong></pre>
			</td>
			<td style="width:308px;">
			<pre align="center">
<strong>sculpture.out</strong></pre>
			</td>
		</tr>
		<tr>
			<td style="width:308px;height:65px;">
			<pre>
6&nbsp;1&nbsp;3

8&nbsp;1&nbsp;2&nbsp;1&nbsp;5&nbsp;4

</pre>
			</td>
			<td style="width:308px;height:65px;">
			<pre>
11

</pre>
			</td>
		</tr>
	</tbody>
</table>

<pre style="clear: both;">
&nbsp;部分数据满足：<img align="absmiddle" alt="1\leq N\leq 2,000, A=1, 1\leq B\leq N" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MVxsZXEmYW1wO3NwYWNlO05cbGVxJmFtcDtzcGFjZTsyLDAwMCwmYW1wO3NwYWNlO0E9MSwmYW1wO3NwYWNlOzFcbGVxJmFtcDtzcGFjZTtCXGxlcSZhbXA7c3BhY2U7Tg==.latex" />；
</pre>

<p>&nbsp;&nbsp;另一部分数据满足：<img align="absmiddle" alt="1\leq N\leq 100, 1\leq A\leq B\leq N" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MVxsZXEmYW1wO3NwYWNlO05cbGVxJmFtcDtzcGFjZTsxMDAsJmFtcDtzcGFjZTsxXGxlcSZhbXA7c3BhY2U7QVxsZXEmYW1wO3NwYWNlO0JcbGVxJmFtcDtzcGFjZTtO.latex" />。</p>

<p>&nbsp;&nbsp;所有数据满足：<img align="absmiddle" alt="1\leq Y_{i}\leq 1,000,000,000" src="/source/joyoi/tyvj-4374/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_MVxsZXEmYW1wO3NwYWNlO1lfe2l9XGxlcSZhbXA7c3BhY2U7MSwwMDAsMDAwLDAwMA==.latex" />。</p> 
