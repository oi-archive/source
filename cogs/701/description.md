# 题目描述


<p style="text-indent:0cm;">
	<b><span style="font-size:12pt;">问题描述</span></b><span><b><span style="font-family:&#39;Times New Roman&#39;;font-size:12pt;">:</span></b></span> 
</p>
<span></span> 
<p>
	<span>京珠高速公路目前正在建设当中。粤北地区是世界著名的“丹霞地貌”，京珠在这里必须穿过一大片复杂的山区。工程的总设计师</span><span style="font-family:&#39;Times New Roman&#39;;">Bonny</span><span>已经规划好了公路大致的走向，而工程师们则被派往各个多山的路段，以设计这些路段的具体规划。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>现在，你因为在信息学上取得的出色成就，被</span><span style="font-family:&#39;Times New Roman&#39;;">Bonny</span><span>派往一个称为</span><span style="font-family:&#39;Times New Roman&#39;;">DreadfulMess</span><span>的最复杂的路段，并仅仅给了你一张地图和一些数据。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>地图以笛卡尔坐标系描述，其中包括这一地区的所有山峰的数据（俯视图）及两个点</span><span style="font-family:&#39;Times New Roman&#39;;">A</span><span>、</span><span style="font-family:&#39;Times New Roman&#39;;">B</span><span>。每座山的轮廓被假想为四边形，工程师们把这些四边形的顶点称为“测量点”</span><span style="font-family:&#39;Times New Roman&#39;;"> </span><span>，这些四边形不会发生重叠、包含，但有可能有共用的一段边或顶点。山以外的区域被认为是平地。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>你的任务是计算此路段山区的总面积，并设计一条公路，从</span><span style="font-family:&#39;Times New Roman&#39;;">A</span><span>点起始，到</span><span style="font-family:&#39;Times New Roman&#39;;">B</span><span>点终止。设计的原则是：公路是一条折线（即转弯点的个数是有限的）；公路可以修在平地上、沿山脚或山谷（即两座山的结合部），也可以打隧道；隧道口不能是转弯点，除非它又是测量点；修建公路的费用最小。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>费用的计算：平地、沿山脚或山谷的<u>单位</u>修路费用为</span><span style="font-family:&#39;Times New Roman&#39;;">u<sub>0</sub></span><span>，各座山修隧道的<u>单位</u>费用为</span><span style="font-family:&#39;Times New Roman&#39;;">u<sub>i</sub></span><span>。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-indent:0cm;">
	<b><span style="font-size:12pt;">输入</span></b><b><span style="font-family:&#39;Times New Roman&#39;;font-size:12pt;"> (ybhighway.in)</span></b><b><span style="font-size:12pt;">：</span></b><b><span style="font-family:&#39;Times New Roman&#39;;font-size:12pt;"></span></b> 
</p>
<p>
	<span>第一、二行分别为</span><span style="font-family:&#39;Times New Roman&#39;;">A</span><span>、</span><span style="font-family:&#39;Times New Roman&#39;;">B</span><span>点坐标，整数。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>第三行为</span><span style="font-family:&#39;Times New Roman&#39;;">u<sub>0</sub></span><span>，正整数。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>第四行为山峰数</span><span style="font-family:&#39;Times New Roman&#39;;">n</span><span>，</span><span style="font-family:&#39;Times New Roman&#39;;">0&lt;=n&lt;=50</span><span>。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>以下共</span><span style="font-family:&#39;Times New Roman&#39;;">n</span><span>行，每行首先是一个正整数</span><span style="font-family:&#39;Times New Roman&#39;;">u<sub>i</sub></span><span>，然后是</span><span style="font-family:&#39;Times New Roman&#39;;">8</span><span>个整数，按<u>逆时针</u>方向给出表示山的四边形的顶点坐标。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>输入数据保证</span><span style="font-family:&#39;Times New Roman&#39;;">A</span><span>、</span><span style="font-family:&#39;Times New Roman&#39;;">B</span><span>两点不会在任何山的内部，四边形任意</span><span style="font-family:&#39;Times New Roman&#39;;">3</span><span>个顶点不在同一直线上，所有的整数的绝对值不会大于</span><span style="font-family:&#39;Times New Roman&#39;;">1000</span><span>。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>坐标均以整数对的形式给出，第一个数为横坐标，第二个为纵坐标。同一行内若有多个相邻整数，则整数间以至少一个空格隔开。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p style="text-indent:0cm;">
	<b><span style="font-size:12pt;">输出</span></b><b><span style="font-family:&#39;Times New Roman&#39;;font-size:12pt;"> (ybhighway.out)</span></b><b><span style="font-size:12pt;">：</span></b><b><span style="font-family:&#39;Times New Roman&#39;;font-size:12pt;"></span></b> 
</p>
<p>
	<span>第一行为这个区域山的总面积。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>第二行为设计公路的总长。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>第三行为修建所设计公路的费用。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span>输出数据均保留两位小数。</span><span style="font-family:&#39;Times New Roman&#39;;"></span> 
</p>
<p>
	<span> 
	</span></p><table cellspacing="0" cellpadding="0" width="100%">
		<tbody>
			<tr>
				<td>
					<div>
						<p style="text-align:center;" align="center">
							<b><span>ybhighway.in</span></b> 
						</p>
						<p>
							<span>-10 1</span> 
						</p>
						<p>
							<span>10 1</span> 
						</p>
						<p>
							<span>100</span> 
						</p>
						<p>
							<span>2</span> 
						</p>
						<p>
							<span>110 0 0 -5 5 -10 0 -5 -5</span> 
						</p>
						<p>
							<span>300 5 -5 10 0 5 5 0 0</span> 
						</p>
						<p>
							<span></span> 
						</p>
					</div>
				</td>
			</tr>
		</tbody>
	</table>
<b><span style="font-family:宋体;">输入输出样例<span></span></span></b> 
<p></p>
<p>
	<span> 
	</span></p><table cellspacing="0" cellpadding="0" width="100%">
		<tbody>
			<tr>
				<td>
					<div>
						<p style="text-align:center;" align="center">
							<b><span>ybhighway.out</span></b> 
						</p>
						<p>
							<span>100.00</span> 
						</p>
						<p>
							<span>21.93</span> 
						</p>
						<p>
							<span>2252.15</span> 
						</p>
						<p>
							<span></span> 
						</p>
					</div>
				</td>
			</tr>
		</tbody>
	</table>
<span></span> 
<p></p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
<p>
	<span></span> 
</p>
