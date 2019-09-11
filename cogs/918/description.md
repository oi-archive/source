# 题目描述


<p>
	</p><table style="padding:0pt 5.4pt;border-collapse:collapse;">
		<tbody>
			<tr>
				<td width="111" valign="top" style="background:#9BBB59;border:1pt solid #B3CC82;" colspan="2">
					<p>
						<span style="color:#FFFFFF;font-family:" calibri";font-size:16pt;font-weight:bold;"="">Problem 1</span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
					</p>
				</td>
				<td width="552" valign="top" style="background:#9BBB59;border:1pt solid #B3CC82;">
					<p>
						<span style="color:#FFFFFF;font-family:" calibri";font-size:16pt;font-weight:bold;"="">东风谷早苗<span>(android.cpp/c/pas)</span></span><span style="color:#FFFFFF;font-size:16pt;font-weight:bold;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="82" valign="top" style="background:#E6EED5;border:1pt solid #B3CC82;">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">题目描述</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
					</p>
				</td>
				<td width="581" valign="top" style="background:#E6EED5;border:1pt solid #B3CC82;" colspan="2">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">在幻想乡，东风谷早苗是以高达控闻名的高中生宅巫女。某一天，早苗终于入手了最新款的钢达姆模型。作为最新的钢达姆，当然有了与以往不同的功能了，那就是它能够自动行走，厉害吧（好吧，我自重）。早苗的新模型可以按照输入的命令进行移动，命令包含<span>’E’</span><span>、</span><span>’S’</span><span>、</span><span>’W’</span><span>、</span><span>’N’</span><span>四种，分别对应四个不同的方向，依次为东、南、西、北</span></span><span style="font-size:10.5pt;">。</span><span style="font-family:" calibri";font-size:10.5pt;"="">执行</span><span style="font-size:10.5pt;">某个</span><span style="font-family:" calibri";font-size:10.5pt;"="">命令时，它会向着对应方向移动一个单位。作为新型机器人，自然不会只单单执行一个命令</span><span style="font-size:10.5pt;">，它可以执行命令串</span><span style="font-family:" calibri";font-size:10.5pt;"="">。对于输入的命令串，每一秒它会按照命令行动一次。而执行完命令串最后一个命令后，会自动从头开始循环。</span><span style="font-size:10.5pt;">在<span>0</span><span>时刻时</span></span><span style="font-family:" calibri";font-size:10.5pt;"="">早苗将钢达姆放置在了<span>(0,0)</span><span>的位置，并且输入了命令串。她想要知道</span><span>T</span><span>秒后钢达姆所在的位置坐标。</span></span><span style="font-size:16pt;font-weight:bold;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="82" valign="top" style="border:1pt solid #B3CC82;">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输入格式</span><span style="font-size:10.5pt;"></span> 
					</p>
				</td>
				<td width="581" valign="top" style="border:1pt solid #B3CC82;" colspan="2">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">第<span>1</span><span>行：一个字符串，表示早苗输入的命令串</span></span><span style="font-size:10.5pt;">，保证至少有<span>1</span><span>个命令</span></span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
					</p>
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">第<span>2</span><span>行：一个正整数</span><span>T</span></span><span style="font-size:10.5pt;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="82" valign="top" style="background:#E6EED5;border:1pt solid #B3CC82;">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输出格式</span><span style="font-size:16pt;font-weight:bold;"></span> 
					</p>
				</td>
				<td width="581" valign="top" style="background:#E6EED5;border:1pt solid #B3CC82;" colspan="2">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">第<span>1</span><span>行：两个整数，表示</span><span>T</span><span>秒时，钢达姆的坐标</span></span><span style="font-size:16pt;font-weight:bold;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="82" valign="top" style="border:1pt solid #B3CC82;">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输入样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
					</p>
				</td>
				<td width="581" valign="top" style="border:1pt solid #B3CC82;" colspan="2">
					<p>
						<span style="font-size:10.5pt;">NSWWNSNEEWN</span><span style="font-size:10.5pt;"></span> 
					</p>
					<p>
						<span style="font-size:10.5pt;">12</span><span style="font-size:10.5pt;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="82" valign="top" style="background:#E6EED5;border:1pt solid #B3CC82;">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">输出样例</span><span style="font-size:10.5pt;font-weight:bold;"></span> 
					</p>
				</td>
				<td width="581" valign="top" style="background:#E6EED5;border:1pt solid #B3CC82;" colspan="2">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">-1 3</span><span style="font-size:10.5pt;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="82" valign="top" style="border:1pt solid #B3CC82;">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">数据范围</span><span style="font-size:16pt;font-weight:bold;"></span> 
					</p>
				</td>
				<td width="581" valign="top" style="border:1pt solid #B3CC82;" colspan="2">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">对于<span>60%</span><span>的数据：</span><span>T &lt;= 500,000</span><span>且命令串长度 </span><span>&lt;= 5,000</span></span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
					</p>
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">对于<span>100%</span><span>的数据：</span><span>T &lt;= 2,000,000,000</span><span>且命令串长度</span><span>&lt;= 5,000</span></span><span style="font-size:10.5pt;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td width="82" valign="top" style="background:#E6EED5;border:1pt solid #B3CC82;">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;font-weight:bold;"="">注意</span><span style="font-size:10.5pt;font-weight:bold;"> </span><span style="font-size:10.5pt;"></span> 
					</p>
				</td>
				<td width="581" valign="top" style="background:#E6EED5;border:1pt solid #B3CC82;" colspan="2">
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">向东移动，坐标改变改变为<span>(X+1,Y);</span></span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
					</p>
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">向南移动，坐标改变改变为<span>(X,Y-1);</span></span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
					</p>
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">向西移动，坐标改变改变为<span>(X-1,Y);</span></span><span style="font-family:" calibri";font-size:10.5pt;"=""></span> 
					</p>
					<p>
						<span style="font-family:" calibri";font-size:10.5pt;"="">向北移动，坐标改变改变为<span>(X,Y+1);</span></span><span style="font-size:10.5pt;"></span> 
					</p>
				</td>
			</tr>
		</tbody>
	</table>
<span><span style="line-height:normal;"><img alt="" src="/images/upload/image/20120715/20120715145730_83627.jpg"/><br/>
</span></span> 
<p></p>
