# 题目描述


<h3>
	【背景】
</h3>
<p style="text-indent:20.2500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">当<span>Caesar</span><span>，</span><span>Pearl</span><span>和他们的宠物们完成了种玫瑰的任务之后，已是黄昏。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:20.2500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">Pearl<span>对</span><span>Caesar</span><span>说：“哎呀，肚子好饿呀，</span><span>Caesar</span><span>我们的晚餐由谁来做呀？”</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:20.2500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">“当然由我来搞定了！”<span>Caesar</span><span>拍拍胸脯说。“但今天我也很累了，不如我们就在回家的路上找一个地方野餐吧。”</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:20.2500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">“好呀好呀！”同样工作了一天的宠物们高兴地欢呼起来。</span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<p style="text-indent:20.2500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">Caesar<span>的脸色变得严峻起来。他知道这些宠物是不好养的。宠物们会选一个最贵的地方进行野餐。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<h3>
	【题目描述】
</h3>
<p style="text-indent:20.2500pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">Caesar<span>专注地看着回家的地图，地图上标有</span><span>n</span><span>（</span><span>n&lt;=200</span><span>）个野餐点和野餐点之间的直达道路以及每条道路的过路费。</span><span>Caesar</span><span>还知道在每一个野餐点野餐的费用。你的程序会收到一些询问（</span><span>i</span><span>，</span><span>j</span><span>）满足</span><span>i&lt;&gt;j</span><span>。对于</span><span>Caesar</span><span>他们当前在</span><span>i</span><span>野餐点，要回到位于</span><span>j</span><span>野餐点的家，回家路线由</span><span>Caesar</span><span>决定，</span><span>Caesar</span><span>要求你求出最小费用。（费用</span><span>=</span><span>过路费</span><span>+</span><span>路径上最贵的野餐点的费用，起点和终点也有可能成为野餐的地方）</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<h3>
	【输入格式】
</h3>
<p style="text-indent:21.0000pt;">
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;">第一行<span>n</span><span>，</span><span>m</span><span>表示结点数和边数。边是双向的。接下来一行</span><span>n</span><span>个数，第</span><span>i</span><span>个数表示在</span><span>i</span><span>点野餐的费用。接下来</span><span>m</span><span>行，每行三个数</span><span>i</span><span>，</span><span>j</span><span>，</span><span>k</span><span>，表示</span><span>i</span><span>点与</span><span>j</span><span>点有一条直达路线，过路费为</span><span>k</span><span>。再下来一个数</span><span>t</span><span>单独一行，表示有</span><span>t(1&lt;=t&lt;=40000)</span><span>个询问。最后</span><span>t</span><span>行，每行</span><span>2</span><span>个数</span><span>i</span><span>，</span><span>j</span><span>，表示询问（</span><span>i</span><span>，</span><span>j</span><span>）。</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<h3>
	【输出格式】
</h3>
<p>
	<span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"> 输出<span>t</span><span>行，依次为每个询问的答案。每个答案都不会超过2^31-1.</span></span><span style="font-size:10.5000pt;font-family:&#39;宋体&#39;;"></span> 
</p>
<h3>
	【样例输入】
</h3>
<pre>5 7
3 4 5 4 3
1 2 6
2 3 2
3 4 2
4 5 6
1 5 10
1 4 7
2 5 7
5
1 3
2 4
3 5
1 4
2 3</pre>
<h3>
	【样例输出】
</h3>
<pre>13
9
13
11
7</pre>
<h3>
	【来源】
</h3>
<p>
	<span></span>中小学电脑报<span> NOI导刊 NOIP2012河南省实验中学培训 Day4 Exercise Problem 5<br/>
</span> 
</p>
