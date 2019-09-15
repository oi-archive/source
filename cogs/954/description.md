# 题目描述


<div>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">【问题描述】</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">莫比乌斯圈<span>(</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">Möbius strip</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">)<span>如下图</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<img src="/images/upload/image/20120722/20120722182330_26894.jpg" alt=""/><img src="/images/upload/image/20120722/20120722182339_40034.jpg" alt=""/><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">可以理解为一个纸带从某处剪断<span>,</span><span>扭一圈</span><span>,</span><span>然后再用胶水粘合的物体</span><span>.</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">关于这个莫比乌斯圈有很多有趣的性质<span>,</span><span>当然也很复杂</span><span>,</span><span>这里不会赘述</span><span>,</span><span>但是需要说一点</span><span>,</span><span>如果你从圈上的某处出发并前进</span><span>,</span><span>那么如果你在走了</span><span>N/2</span><span>个单位距离发现起始点在你的背面</span><span>,</span><span>那么就称这个带的长度为</span><span>N(</span><span>也就意味着你需要绕</span><span>N</span><span>的距离才能返回原点</span><span>) </span></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">我们的问题是<span>:</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">想象</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">”</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">侠盗猎车手</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">”</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">里面的任务骑着摩托车在一个长度为<span>N</span><span>的莫比乌斯带上踩加分点</span><span>(</span><span>我们认为每隔一单位长度就有一个加分点</span><span>,</span><span>这个加分点是个整数</span><span>.</span><span>我们想知道从位置</span><span>a</span><span>开始骑摩托吃分到位置</span><span>b</span><span>所有可能的得分之和</span><span>,</span><span>我们假设只要他经过得分点就一定能得到分</span><span>,</span><span>并且他可能骑车在</span><span>c</span><span>处</span><span>(a&lt;=b&lt;=c)</span><span>停下来</span><span>,</span><span>而放弃</span><span>b+1</span><span>到</span><span>c</span><span>之间的得分</span><span>.</span><span>可是这得分点的分值有时候会变</span><span>,</span><span>我们如果想知道从</span><span>a</span><span>到</span><span>b</span><span>的总分值是多少</span><span>,</span><span>就会询问</span><span>,</span><span>所以</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">【输入】</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">第一行两个整数<span>N,Q,Q</span><span>是操作数</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">第二行<span>N</span><span>个整数表示随便从一个点开始</span><span>,</span><span>到之后</span><span>N</span><span>个单位长度之间</span><span>N</span><span>个加分点的分值</span><span>,</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">第三行一个整数<span>Command,</span><span>表示操作数</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">接下来<span>Command</span><span>行每一行由一个指令类型</span><span>(</span><span>一个字符串</span><span>,</span><span>中间没有空格</span><span>),</span><span>后面跟相应的参数</span><span>.</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">要么是</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">”</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">C</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">”</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;"> a b x<span>表示从</span><span>a</span><span>到</span><span>b</span><span>将键值修加</span><span>x</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">要么是</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">”</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">Q</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">”</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;"> a b <span>表示询问从</span><span>a</span><span>到</span><span>b</span><span>之间我们想询问的值</span><span>,</span><span>具体见题目描述</span><span>.</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">【输出】</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">对于每个询问给出相应的回答一共<span>Command</span><span>行</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">【输入输出样例</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">1</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">】</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;">
		<tbody>
			<tr>
				<td style="border:0.5000pt solid #000000;" valign="top" width="284">
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">mobius.in</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="284">
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">mobius.out</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td style="border:0.5000pt solid #000000;" valign="top" width="284">
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;">4 5</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">C</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"> 1 4 2</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">C</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"> 1 2 -1</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">Q</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"> 1 2</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">Q</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"> 2 4</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">Q</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"> 1 4</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="284">
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">3</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">9</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">13</span><span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;"></span> 
					</p>
					<p>
						<span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
					</p>
				</td>
			</tr>
		</tbody>
	</table>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">【数据范围】</span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"> </span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">40%<span>的数据</span><span>N&lt;=10000 Q&lt;=10000</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;微软雅黑&#39;;">100%<span>的数据</span><span>N&lt;=100000 Q&lt;=100000</span></span><span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.0000pt;font-family:&#39;Calibri&#39;;"><br/>
</span> 
	</p>
</div>
