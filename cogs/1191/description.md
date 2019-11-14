# 题目描述


<span style="font-size:16px;"></span> 
<h3>
	<span style="font-size:14px;">【背景】</span> 
</h3>
<p>
	对于一只猫咪来说，它是有九条命的。但是并不是所有的猫咪都是这样，只有那些造化很高的猫咪才能死而复生。而且对于这样的猫咪，如果它能够活到第九条命，那么它最终可以变成任何一种它想成为的动物（当然也可以继续做猫咪啦），我们称这样的猫咪为猫神。现在一只获得了进化机会的猫咪，受到了女神snowharmony的考验。
</p>
<h3>
	<span style="font-size:16px;"></span> 
</h3>
<h3>
	<span style="font-size:14px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-size:14px;">它拥有t个单位的时间，在每个单位时间里，它可以选择沉默、叫一声“喵”、或者叫两声“喵喵”。对于每个单位时间，均有一个实数v[i]，猫咪叫一声可获得v[i]的进化量，叫两声可以获得(v[i])^2的进化量，然而它在某个单位时间如果叫了两声，下一单位时间必须保持沉默来休息。<br/>
女神Snowharmony要求它以一定的方式叫，只有它最终获得了最大的进化量，它才能进化为猫神，从而变为它想成为的动物——人族zsw95。<br/>
请你帮助它计算最大进化量，使他进化为为猫神zsw95。<br/>
</span> 
</p>
<h3>
	<span style="font-size:14px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-size:14px;">输入：<br/>
第一行一个整数t。<br/>
第二行，t个实数v[i]。<br/>
</span> 
</p>
<h3>
	<span style="font-size:14px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-size:14px;">最大的进化量，保留四位小数。</span> 
</p>
<h3>
	<span style="font-size:14px;">【样例输入】</span> 
</h3>
<pre>3
9 2 1
</pre>
<h3>
	<span style="font-size:14px;">【样例输出】</span> 
</h3>
<pre>82.0000</pre>
<h3>
	<span style="font-size:14px;">【提示】</span> 
</h3>
<p>
	<span style="font-size:14px;">各个测试点1s</span>
</p>
<p>
	<span style="font-size:14px;">1&lt;=t&lt;=800000,-255.00&lt;=v[i]&lt;=255.00<br/>
计算结果不超过maxlongint<br/>
</span> 
</p>
<h3>
	<span style="font-size:14px;">【来源】</span> 
</h3>
<p>
	<span style="font-size:14px;">来源：lydliyudong    Tyvj February二月月赛第二场  第1道</span> 
</p>
