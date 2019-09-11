# 题目描述


<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">某收费有线电视网计划转播一场重要的足球比赛。他们的转播网和用户终端构成一棵树状结构，这棵树的根结点位于足球比赛的现场，树叶为各个用户终端，其他中转站为该树的内部节点。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">从转播站到转播站以及从转播站到所有用户终端的信号传输费用都是已知的，一场转播的总费用等于传输信号的费用总和。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    现在每个用户都准备了一笔费用想观看这场精彩的足球比赛，有线电视网有权决定给哪些用户提供信号而不给哪些用户提供信号。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    写一个程序找出一个方案使得有线电视网在不亏本的情况下使观看转播的用户尽可能多。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    输入文件的第一行包含两个用空格隔开的整数<span>N</span><span>和</span><span>M</span><span>，其中</span><span>2</span><span>≤</span><span>N</span><span>≤</span><span>3000</span><span>，</span><span>1</span><span>≤</span><span>M</span><span>≤</span><span>N</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1<span>，</span><span>N</span><span>为整个有线电视网的结点总数，</span><span>M</span><span>为用户终端的数量。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    第一个转播站即树的根结点编号为<span>1</span><span>，其他的转播站编号为</span><span>2</span><span>到</span><span>N</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">M<span>，用户终端编号为</span><span>N</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">M+1<span>到</span><span>N</span><span>。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    接下来的<span>N</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">M<span>行每行表示—个转播站的数据，第</span><span>i+1</span><span>行表示第</span><span>i</span><span>个转播站的数据，其格式如下：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">    K  A</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">  C</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">  A</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">  C</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">  …  A</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;vertical-align:sub;">k</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;">  C</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;vertical-align:sub;">k</span><span style="font-size:10.5000pt;font-family:&#39;Times New Roman&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">    K<span>表示该转播站下接</span><span>K</span><span>个结点</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">转播站或用户</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，每个结点对应一对整数<span>A</span><span>与</span><span>C</span><span>，</span><span>A</span><span>表示结点编号，</span><span>C</span><span>表示从当前转播站传输信号到结点</span><span>A</span><span>的费用。最后一行依次表示所有用户为观看比赛而准备支付的钱数。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">输出文件仅一行，包含一个整数，表示上述问题所要求的最大用户数。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<img src="http://cojs.tk/upload/image/20121019/20121019171404_44089.png" width="188" height="190" align="right" alt=""/>
<div>
</div>
<p>
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span>
</p>
<p>
	<span style="font-size:10.5pt;font-family:宋体;">tele.in</span><span style="font-size:10.5pt;font-family:宋体;">                    </span><span style="font-size:10.5pt;font-family:宋体;"></span><span style="font-size:10.5pt;font-family:宋体;"></span><span style="font-size:10.5pt;font-family:宋体;"></span><span style="font-size:10.5pt;font-family:宋体;"></span><span style="font-size:10.5pt;font-family:宋体;">tele.out</span>
</p>
<div>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5 3                       </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 2 2 5 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 3 2 4 3</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3 4 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
	</p>
	<p>
		<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例解释】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
	</p>
	<p style="text-align:left;text-indent:21.75pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">如右图所示，共有五个结点。结点①为根结点，即现场直播站，②为一</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">个中转站，③④⑤为用户端，共M个，编号从N</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">-</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">M+1到N，他们为观看比</span><span style="font-family:宋体;font-size:10.5pt;">赛分别准备的钱数为</span><span style="font-family:宋体;font-size:10.5pt;">3</span><span style="font-family:宋体;font-size:10.5pt;">、</span><span style="font-family:宋体;font-size:10.5pt;">4</span><span style="font-family:宋体;font-size:10.5pt;">、</span><span style="font-family:宋体;font-size:10.5pt;">2</span><span style="font-family:宋体;font-size:10.5pt;">，从结点①可以传送信号到结点②，费用为</span><span style="font-family:宋体;font-size:10.5pt;">2</span><span style="font-family:宋体;font-size:10.5pt;">，</span><span style="font-family:宋体;font-size:10.5pt;">也可以传送信号到结点⑤，费用为</span><span style="font-family:宋体;font-size:10.5pt;">3</span><span style="font-family:宋体;font-size:10.5pt;">（第二行数据所示），从结点②可以传输信号到结点③，费用为</span><span style="font-family:宋体;font-size:10.5pt;">2</span><span style="font-family:宋体;font-size:10.5pt;">。也可传输信号到结点④，费用为</span><span style="font-family:宋体;font-size:10.5pt;">3</span><span style="font-family:宋体;font-size:10.5pt;">（第三行数据所示），如果要让所有用户（③④⑤）都能看上比赛，则信号传输的总费用为：</span>
	</p>
	<p>
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
	</p>
	<p style="text-indent:21.7500pt;">
		<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2+3+2+3=10<span>，大于用户愿意支付的总费用</span><span>3+4+2=9</span><span>，有线电视网就亏本了，而只让③④两个用户看比赛就不亏本了。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
	</p>
	<p>
		<br/>
	</p>
</div>
