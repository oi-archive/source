# 题目描述


<div>
	<p style="text-indent:21.7500pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第<span>XXXX</span><span>届</span><span>NOI</span><span>期间，为了加强各省选手之间的交流，组委会决定组织一场省际电子竞技大赛，每一个省的代表队由</span><span>n</span><span>名选手组成，比赛的项目是老少咸宜的网络游戏泡泡堂。每一场比赛前，对阵双方的教练向组委会提交一份参赛选手的名单，决定了选手上场的顺序，一经确定，不得修改。比赛中，双方的一号选手，二号选手……，</span><span>n</span><span>号选手捉对厮杀，共进行</span><span>n</span><span>场比赛。每胜一场比赛得</span><span>2</span><span>分，平一场得</span><span>1</span><span>分，输一场不得分。最终将双方的单场得分相加得出总分，总分高的队伍晋级</span><span>(</span><span>总分相同抽签决定</span><span>)</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:21.7500pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">作为<span>HN</span><span>队的领队，你已经在事先将各省所有选手的泡泡堂水平了解的一清二楚，并将其用一个实力值来衡量。为简化问题，我们假定选手在游戏中完全不受任何外界因素干扰，即实力强的选手一定可以战胜实力弱的选手，而两个实力相同的选手一定会战平。由于完全不知道对手会使用何种策略来确定出场顺序，所以所有的队伍都采取了这样一种策略，就是完全随机决定出场顺序。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:21.7500pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">当然你不想这样不明不白的进行比赛。你想事先了解一下在最好与最坏的情况下，<span>HN</span><span>队最终分别能得到多少分。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-align:center;">
		<img src="/upload/image/20121007/20121007221221_45108.png" alt=""/><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;"></span> 
	</p>
	<p>
		<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;Calibri&#39;;">输入： </span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入文件的第一行为一个整数<span>n</span><span>，表示每支代表队的人数。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来<span>n</span><span>行，每行一个整数，描述了</span><span>n</span><span>位</span><span>HN</span><span>队的选手的实力值。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">接下来<span>n</span><span>行，每行一个整数，描述了你的对手的</span><span>n</span><span>位选手的实力值。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">20<span>％的数据中，</span><span>1&lt;=n&lt;=10</span><span>；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:21.0000pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">40<span>％的数据中，</span><span>1&lt;=n&lt;=100</span><span>；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:21.0000pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">60<span>％的数据中，</span><span>1&lt;=n&lt;=1000</span><span>；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p style="text-indent:21.0000pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">100<span>％的数据中，</span><span>1&lt;=n&lt;=100000</span><span>，且所有选手的实力值在</span><span>0</span><span>到</span><span>10000000</span><span>之间。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;Calibri&#39;;">输出</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;Calibri&#39;;">：</span><span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输入文件中包括两个用空格隔开的整数，分别表示<span>HN</span><span>队在最好与最坏的情况下分别能得多少分。不要在行末输出多余的空白字符。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">样例</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">bnb.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">bnb.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">样例说明</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">我们分别称<span>4</span><span>位选手为</span><span>A,B,C,D</span><span>。则可能出现以下</span><span>4</span><span>种对战方式，最好情况下可得</span><span>2</span><span>分，最坏情况下得</span><span>0</span><span>分。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<table style="border-collapse:collapse;padding:0.0000pt 5.4000pt 0.0000pt 5.4000pt;" align="center">
		<tbody>
			<tr>
				<td style="border:0.5000pt solid #000000;" valign="top" width="70">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
<br/>
				</td>
				<td colspan="3" style="border:0.5000pt solid #000000;" valign="top" width="108">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td colspan="3" style="border:0.5000pt solid #000000;" valign="top" width="108">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">二</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td colspan="3" style="border:0.5000pt solid #000000;" valign="top" width="108">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">三</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td colspan="3" style="border:0.5000pt solid #000000;" valign="top" width="108">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">四</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td style="border:0.5000pt solid #000000;" valign="top" width="70">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
<br/>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">HN</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">???</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">结果</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">HN</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">???</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">结果</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">HN</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">???</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">结果</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">HN</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">???</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">结果</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td style="border:0.5000pt solid #000000;" valign="top" width="70">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一号选手</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">A</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">C</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">负</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">A</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">D</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">负</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">B</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">C</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">胜</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">B</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">D</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">负</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td style="border:0.5000pt solid #000000;" valign="top" width="70">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">二号选手</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;">B</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">D</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">负</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">B</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">C</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">胜</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">A</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">D</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">负</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="32">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">A</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="33">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">C</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td style="border:0.5000pt solid #000000;" valign="top" width="42">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">负</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
			</tr>
			<tr>
				<td style="border:0.5000pt solid #000000;" valign="top" width="70">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">总得分</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td colspan="3" style="border:0.5000pt solid #000000;" valign="top" width="108">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td colspan="3" style="border:0.5000pt solid #000000;" valign="top" width="108">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td colspan="3" style="border:0.5000pt solid #000000;" valign="top" width="108">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
				<td colspan="3" style="border:0.5000pt solid #000000;" valign="top" width="108">
					<p style="text-align:center;">
						<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
					</p>
				</td>
			</tr>
		</tbody>
	</table>
	<p>
		<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;Calibri&#39;;">样例</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">bnb.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">6</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">10000000</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">10000000</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">10000000</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">10000000</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">10000000</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">10000000</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">0</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">bnb.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">12 12</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;">样例说明</span><span style="font-size:12.0000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">对手都是认真学习的好孩子，不会打游戏。无论如何排列出场顺序都无法改变被蹂躏的结果。<span>HN</span><span>队总能取得全胜的结果。</span></span> 
	</p>
	<p>
		<span style="background-color:#000000;color:#FFE500;">此题较难，只要求完成60%的数据，即n&lt;=1000的情况。</span><br/>
<span style="background-color:#000000;color:#FFE500;">另外，前两个输入数据的后面同时附上了最大得分和最小得分相应的对阵情况，便与调试。</span><br/>
<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"><span></span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;Calibri&#39;;"><br/>
</span> 
	</p>
</div>
