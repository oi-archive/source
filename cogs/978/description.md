# 题目描述


<p align="center" style="text-align:center;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Encrypt</span>
</p>
<p>
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">为了防止文本机密被泄漏，某Ａ发明了一种加密系统。</span><span></span></span>
</p>
<p>
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">对于一个已知的文本，有如下几种加密操作：</span><span></span></span>
</p>
<table border="1" cellspacing="0" cellpadding="0" width="560" style="width:419.95pt;">
	<tbody>
		<tr>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p align="center" style="text-align:center;">
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">操作代号</span><span></span></span>
				</p>
			</td>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p align="center" style="text-align:center;">
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">加密效果</span><span></span></span>
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p align="center" style="text-align:center;">
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Ａ</span><span></span></span>
				</p>
			</td>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">把文本翻转。比如“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">aB23d”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">变成</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">“d32Ba”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">。</span><span></span></span>
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p align="center" style="text-align:center;">
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Ｃ</span><span></span></span>
				</p>
			</td>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">把文本集体向右移动一个字符，最末移动到第一。比如，“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">aB23d” </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">变成</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">“daB23”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">。</span><span></span></span>
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p align="center" style="text-align:center;">
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Ｅ</span><span></span></span>
				</p>
			</td>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">把文本沿着对称轴将左右部分互换。比如，“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">aB23d” </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">变成</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">“3d2aB</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">e3ac” </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">变成</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"> “ace3”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">。</span><span></span></span>
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p align="center" style="text-align:center;">
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Ｊ</span><span></span></span>
				</p>
			</td>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">把文本集体向左移动一个字符，第一移动到最末。比如，“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">aB23d” </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">变成</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">“B23da”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">。</span><span></span></span>
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p align="center" style="text-align:center;">
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Ｍ</span><span></span></span>
				</p>
			</td>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">把文本中的数字减１，如果数字是０就变成９。比如，“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">aB23d” </span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">变成</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;"> “aB34d”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，</span></span><span style="font-family:&#34;"> </span><span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">e0ac”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">变成</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">“e9ac”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">。</span><span></span></span>
				</p>
			</td>
		</tr>
		<tr>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p align="center" style="text-align:center;">
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">Ｐ</span><span></span></span>
				</p>
			</td>
			<td valign="top" style="border:solid windowtext 1.0pt;">
				<p>
					<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">把文本中的数字加１，如果数字是９就变成０。比如，“</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">aB23d”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">变成</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">“aB34d”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">，</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">“e9ac”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">变成</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">“e0ac”</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">。</span><span></span></span>
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p style="text-indent:24.0pt;">
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">现在你从某</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">A</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">处收到一个文本，它是已经经过一系列加密操作的。你需要把它还原成原始文本。</span><span></span></span>
</p>
<p>
	<span style="font-size:12.0pt;font-family:&#34;"></span>
</p>
<p>
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输入格式</span><span></span></span>
</p>
<p style="margin-left:21.0pt;">
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第一行，依次进行的加密操作代号。</span><span></span></span>
</p>
<p style="margin-left:21.0pt;">
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">第二行，接收到的文件。</span><span></span></span>
</p>
<p>
	<span style="font-size:12.0pt;font-family:&#34;"></span>
</p>
<p>
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输出格式</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">只有一行，原始文件。</span><span></span></span>
</p>
<p>
	<span style="font-size:12.0pt;font-family:&#34;"></span>
</p>
<p>
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">样例</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输入</span><span></span></span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">AM</span>
</p>
<p style="text-indent:21.0pt;">
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">6</span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">      </span><span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">输出</span><span></span></span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">      7</span>
</p>
<p>
	<span style="font-size:12.0pt;font-family:&#34;"></span>
</p>
<p>
	<span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">数据范围</span><span></span></span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">1&lt;=</span><span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">加密操作序列长度</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">&lt;=6</span></span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">1&lt;=</span><span style="font-size:12.0pt;font-family:&#34;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">每个文本的长度</span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:18px;">&lt;=25</span></span>
</p>
