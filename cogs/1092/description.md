# 题目描述


<h2>
	【背景】
</h2>
<p>
	<span style="color:#355F29;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;line-height:16.66666603088379px;background-color:#FFFFFF;">  Lucky为了掩护大部队，单枪匹马同敌人周旋，后来被敌人包围在某山头……等等，为什么怎么听怎么像狼牙山五壮士！不过不用着急，这次Lucky携带了足够的弹药，完全可以将涌上来的敌人一个一个干掉。Lucky是个神枪手，只要他的枪膛中有子弹，他就能将在他射程m（用从敌人位置到山头的直线距离算）以内的一个敌人瞬间射杀。但如果在射程内没有敌人，出于节约子弹考虑和面子问题，Lucky会等待敌人靠近然后射击。</span> 
</p>
<h3>
	【题目描述】
</h3>
<p>
	<span style="color:#355F29;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;line-height:16.66666603088379px;background-color:#FFFFFF;"> 正当Lucky为自己的强大而自我膨胀时，他忽然发现了一个致命的失误：他携带的枪是单发枪，每射出一发子弹都必须花k秒钟的时间装子弹。而凶残的敌人才不会花时间等你换子弹呢。他们始终在以1m/s的速度接近山头。而如果在一个敌人到达山头时Lucky无法将他击毙，那么我们可怜的Lucky就将牺牲在敌人的刺刀下。现在Lucky用心灵感应向你发出求助：要保住自己的性命并且歼灭所有敌人，Lucky最多只能用多少时间给枪装上一发子弹？</span><br/>
<br/>
<span style="color:#355F29;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;line-height:16.66666603088379px;background-color:#FFFFFF;">    说明：假设一开始Lucky的枪中就有一发子弹，并且一旦确定一个装弹时间，Lucky始终会用这个时间完成子弹的装卸。希望你能帮助Lucky脱离险境。</span> 
</p>
<h3>
	【输入格式】
</h3>
<p>
	<span style="color:#355F29;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;line-height:16.66666603088379px;background-color:#FFFFFF;">   针对每组输入数据，第一行有两个整数n和m，（2≤n≤100,000; 1≤m≤10,000,000）n代表敌人个数，m代表Lucky的射程。</span><br/>
<span style="color:#355F29;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;line-height:16.66666603088379px;background-color:#FFFFFF;">    接下来有n行，每行一个整数mi,（1≤mi≤10,000,000），代表每个敌人一开始相对山头的距离（单位为米）。</span> 
</p>
<h3>
	【输出格式】
</h3>
<p>
	<span style="color:#355F29;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;line-height:16.66666603088379px;background-color:#FFFFFF;">每组输出数据仅有一个整数，代表Lucky的换弹时间（单位为秒）。</span> 
</p>
<h3>
	【样例输入】
</h3>
<pre>6 100
236
120
120
120
120
120</pre>
<h3>
	【样例输出】
</h3>
<pre>25
</pre>
<h3>
	【提示】
</h3>
<p>
	<span style="color:#355F29;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;line-height:16.66666603088379px;background-color:#FFFFFF;">各个测试点1s</span>
</p>
<h3>
	【来源】
</h3>
<p>
	<span style="color:#355F29;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;line-height:16.66666603088379px;background-color:#FFFFFF;">题后剧情：</span><br/>
<span style="color:#355F29;font-family:&#39;Hiragino Sans GB W3&#39;, sans-serif;line-height:16.66666603088379px;background-color:#FFFFFF;">    Lucky最终在您的帮助下歼灭了所有包围他的敌人，在保证了大部队安全的情况下，还缴获了大量敌军的精良装备。这次战斗，大大地挫退了敌人的嚣张气焰，大大地鼓舞了我军的士气。从此， Lucky也踏上了他的英雄之路。</span>
</p>
