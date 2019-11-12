# 题目描述


<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">小<span>x</span><span>刚买了一个字母轮盘（如下图所示），这个轮盘被分成了</span><span>N</span><span>部分，每部分上被标记了一个大写英文字符。并且保证这个英文字符只会出现一次。这个轮盘只会顺指针转动，并且有一个指针会指向一个字符，下图中的轮盘分成</span><span>8</span><span>部分，每部分都有一个大写英文字符，指针指向 ‘</span><span>H</span><span>’ 。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<img src="/upload/image/20120907/20120907085346_55179.png" alt=""/><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">小<span>x</span><span>玩这个轮盘的过程是这样的：小</span><span>x</span><span>会转动这个轮盘</span><span>m</span><span>次，每次他都会记录</span></span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">指针指向的字符改变次数<span>ci</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，还会记录</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">改变<span>ci</span><span>次后最后指针指向的字符</span><span>chi</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">小<span>x</span><span>将这</span><span>m</span><span>次的结果记录在了一张纸上，经过了</span><span>n</span><span>年，小</span><span>x</span><span>又发现了这张纸，而字母轮盘却再也找不到了。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">现在小<span>x</span><span>的问题是，能不能根据纸上的记录，还原轮盘。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">题目包含多组数据，每组数据格式如下：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:5.6500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">首先第一行包含两个整数：<span>N</span></span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;Garamond&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">(2</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">≤</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;"> </span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;Garamond&#39;;">N</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;Garamond&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">≤</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">25)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">和<span>m</span></span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;Garamond&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">(1≤</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;"> </span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;宋体&#39;;">m</span><span style="font-weight:bold;font-size:12.0000pt;font-family:&#39;Garamond&#39;;"> </span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">≤ 100)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，意义如题目描述。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="margin-left:5.6500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来<span>m</span><span>行，每行一个整数，</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一个字符，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">分别是<span>ci</span><span>和</span><span>chi</span><span>。意义如题目描述</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">对于每组数据，输出相应的结果：</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">如果记录上的值有矛盾，输出</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">‘!’</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.7500pt;">
	<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">如果记录上的值可以确定一轮盘，那么按顺时针方向依次输出轮盘的字符，第一个字符为最后一次显示的字符的值，如果某个字符无法确定，在不确定的字符输出</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">‘</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">?</span><span style="font-size:12.0000pt;font-family:&#39;Garamond&#39;;">’</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入输出样例<span>1</span><span>】</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
	<tbody>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">wheel</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.in</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p>
					<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">wheel</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;">.out</span><span style="font-size:10.5000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
			</td>
		</tr>
		<tr>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">3 3</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">1 A</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 B</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">3 C</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">5 6</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">1 A</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 B</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">5 B</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">1 C</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 A</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">2 B</span><span style="font-size:11.0000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">8 8</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">4 V</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">3 I</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">7 T</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">7 A</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">6 R</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">5 N</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">1 O</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">9 H</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
			<td style="border:0.5000pt solid #000000;" valign="top" width="282">
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">!</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p style="text-align:left;">
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">B?A?C</span><span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;"></span> 
				</p>
				<p>
					<span style="font-size:11.0000pt;font-family:&#39;Courier New&#39;;">HONITAVR</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
				</p>
			</td>
		</tr>
	</tbody>
</table>
<p>
	<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">【样例解释】</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">第三组数据 就是样例所示</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">【数据范围】 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">   每个测试文件保证测试数据不超过<span>5</span><span>组。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p>
	<span style="font-size:16.0000pt;font-family:&#39;宋体&#39;;"><br/>
</span> 
</p>
<p>
	<br/>
</p>
