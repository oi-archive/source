# 题目描述


<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【问题描述】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">一堆木头棍子共有<span>n</span><span>根，每根棍子的长度和宽度都是已知的。棍子可以被一台机器一个接一个地加工。机器处理一根棍子之前需要准备时间。准备时间是这样定义的：</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一根棍子的准备时间为<span>1</span><span>分钟；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">如果刚处理完长度为<span>L</span><span>，宽度为</span><span>W</span><span>的棍子，那么如果下一个棍子长度为</span><span>L</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，宽度为<span>W</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，并且满足<span>L</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&gt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">＝<span>L</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>W</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&gt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">＝<span>W</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">i</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，这个棍子就不需要准备时间，否则需要<span>1</span><span>分钟的准备时间；</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">计算处理完<span>n</span><span>根棍子所需要的最短准备时间。比如，你有</span><span>5</span><span>根棍子，长度和宽度分别为</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4, 9</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5, 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2, 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3, 5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1, 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，最短准备时间为<span>2</span><span>（按</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4, 9</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">、</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">3, 5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">、</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">1, 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">、</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5, 2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">、</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2, 1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">的次序进行加工）。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输入】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行是一个整数<span>n</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">(</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">&lt;</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">＝<span>5000</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">)</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，第<span>2</span><span>行是</span><span>2n</span><span>个整数，分别是</span><span>L</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>W</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">1</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>L</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>w</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">2</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，…，<span>L</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">，<span>W</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;vertical-align:sub;">n</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">。<span>L</span><span>和</span><span>W</span><span>的值均不超过</span><span>10000</span><span>，相邻两数之间用空格分开。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【输出】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">仅一行，一个整数，所需要的最短准备时间。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;">【样例】</span><span style="font-weight:bold;font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">stick.in</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">5</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">4 9 5 2 2 1 3 5 1 4</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">stick.out</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">2 </span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span>
</p>
<p>
	<br/>
</p>
