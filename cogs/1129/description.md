# 题目描述


<h3>
	<span></span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【题目描述】</span> 
</h3>
<p style="text-indent:21.0000pt;">
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">汤姆斯生活在一个等级为</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">0</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的星球上。那里的环境极其恶劣，每天</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">12</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">小时的工作和成堆的垃圾让人忍无可忍。他向往着等级为</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的星球上天堂般的生活。</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">有一些航班将人从低等级的星球送上高一级的星球，有时需要向驾驶员支付一定金额的费用，有时却又可以得到一定的金钱。</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">汤姆斯预先知道了从</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">0</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">等级星球去</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">等级星球所有的航线和需要支付（或者可以得到）的金钱，他想寻找一条价格最低（甚至获得金钱最多）的航线。</span> 
</p>
<h3>
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第一行一个正整数</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">N(N</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">100)</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，接下来的数据可分为</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">个段落每段的第一行一个整数</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">Ki(Ki</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">100)</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，表示等级为</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的星球有</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">Ki</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">个。</span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">接下来的</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">Ki</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">中第</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">Tij</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">行依次表示与等级为</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">，编号为</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">i</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的星球相连的等级为</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">i-l</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的星球的编号和此航线需要的费用（正数表示支出，负数表示收益，费用的绝对值不超过</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">1000</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">）。</span> 
</p>
<p>
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">每行以</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">0</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">结束，每行的航线数≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">100</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">。</span> 
</p>
<h3>
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p>
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输出所需（或所得）费用。正数表示支出，负数表示收益。</span> 
</p>
<h3>
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【样例输入】</span> 
</h3>
<pre> 3
 2
 1 15 0
 1 5 0
 3
 1 -5 2 10 0
 1 3 0
 2 40 0
 2
 1 1 2 5 3 -5 0
 2 -19 3 -20 0</pre>
<h3>
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【样例输出】</span> 
</h3>
<pre>-1</pre>
<h3>
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【提示】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"> </span> 
</p>
<p style="text-indent:21.0000pt;">
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">100%</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">的数据</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">N</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">100 Ki</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">≤</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">100</span><span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">。<span></span></span> 
</p>
<h3>
	<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【写真】</span> 
</h3>
<p>
	<span><span style="font-size:15px;line-height:17px;"><img src="/upload/image/20121010/20121010081258_74493.jpg" alt=""/><span></span><br/>
</span></span> 
</p>
