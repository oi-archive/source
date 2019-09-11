# 题目描述


<h2 style="text-align:left;color:#1BA1E2;font-family:simsun;font-size:18px;margin-left:0px;">
<span style="font-family:Verdana;">Source: SDOI2010 Round 1,Day 2,Problem 3.</span> 
</h2>
<h2 style="text-align:left;color:#1BA1E2;font-family:simsun;font-size:18px;margin-left:0px;">
<span style="font-family:Verdana;"> </span> 
</h2>
<h2 style="text-align:left;color:#1BA1E2;font-family:simsun;font-size:18px;margin-left:0px;">
<span style="font-family:Verdana;">Description</span> 
</h2>
<div style="text-align:left;color:#323E32;font-family:simsun;font-size:14px;margin-left:0px;">
<span style="font-family:Verdana;">10 年一度的银河系赛车大赛又要开始了。作为全银河最盛大的活动之一，夺得这个项目的冠军无疑是很多人的梦想，来自杰森座 α星的悠悠也是其中之一。 赛车大赛的赛场由 N 颗行星和M条双向星际航路构成，其中每颗行星都有一个不同的引力值。大赛要求车手们从一颗与这 N 颗行星之间没有任何航路的天体出发，访问这 N 颗行星每颗恰好一次，首先完成这一目标的人获得胜利。由于赛制非常开放，很多人驾驶着千奇百怪的自制赛车来参赛。这次悠悠驾驶的赛车名为超能电驴，这是一部凝聚了全银河最尖端科技结晶的梦幻赛车。作为最高科技的产物，超能电驴有两种移动模式：高速航行模式和能力爆发模式。在高速航行模式下，超能电驴会展开反物质引擎，以数倍于光速的速度沿星际航路高速航行。在能力爆发模式下，超能电驴脱离时空的束缚，使用超能力进行空间跳跃——在经过一段时间的定位之后，它能瞬间移动到任意一个行星。天不遂人愿，在比赛的前一天，超能电驴在一场离子风暴中不幸受损，机能出现了一些障碍：在使用高速航行模式的时候，只能由每个星球飞往引力比它大的星球，否则赛车就会发生爆炸。尽管心爱的赛车出了问题，但是悠悠仍然坚信自己可以取得胜利。他找到了全银河最聪明的贤者——你，请你为他安排一条比赛的方案，使得他能够用最少的时间完成比赛。</span> 
</div>
<h2 style="text-align:left;color:#1BA1E2;font-family:simsun;font-size:18px;margin-left:0px;">
<span style="font-family:Verdana;">Input</span> 
</h2>
<div style="text-align:left;color:#323E32;font-family:simsun;font-size:14px;margin-left:0px;">
<span style="font-family:Verdana;">第一行是两个正整数 N, M。 第二行 N 个数 A1~AN，其中Ai表示使用能力爆发模式到达行星 i 所需的定位时间。接下来 M行，每行 3个正整数ui, vi, wi，表示在编号为 ui和vi的行星之间存在一条需要航行wi时间的星际航路。输入数据已经按引力值排序，也就是编号小的行星引力值一定小，且不会有两颗行星引力值相同。</span> 
</div>
<h2 style="text-align:left;color:#1BA1E2;font-family:simsun;font-size:18px;margin-left:0px;">
<span style="font-family:Verdana;">Output</span> 
</h2>
<div style="text-align:left;color:#323E32;font-family:simsun;font-size:14px;margin-left:0px;">
<span style="font-family:Verdana;">仅包含一个正整数，表示完成比赛所需的最少时间。</span> 
</div>
<h2 style="text-align:left;color:#1BA1E2;font-family:simsun;font-size:18px;margin-left:0px;">
<span style="font-family:Verdana;">Sample Input</span> 
</h2>
<p>
<span style="font-family:Verdana;"><span style="font-size:14px;background-color:#CCCCFF;">starrace.in</span></span> 
</p>
<div style="text-align:left;color:#323E32;font-family:simsun;font-size:14px;margin-left:0px;">
</div>
<p>
<span style="font-family:Verdana;"> </span> 
</p>
<div style="text-align:left;color:#323E32;font-family:simsun;font-size:14px;margin-left:0px;">
<span>3 3<br/>
1 100 100<br/>
2 1 10<br/>
1 3 1<br/>
2 3 1</span><span style="font-family:&#34;"> </span><span style="font-family:Verdana;"> </span> 
</div>
<h2 style="text-align:left;color:#1BA1E2;font-family:simsun;font-size:18px;margin-left:0px;">
<span style="font-family:Verdana;">Sample Output</span> 
</h2>
<p>
<span style="font-family:Verdana;"><span style="font-size:14px;background-color:#CCCCFF;">starrace.out</span></span> 
</p>
<p>
<span style="font-family:&#34;">12 </span><span style="font-family:Verdana;"> </span> 
</p>
<h2 style="text-align:left;color:#1BA1E2;font-family:simsun;font-size:18px;margin-left:0px;">
<span style="font-family:Verdana;">HINT</span> 
</h2>
<p style="text-align:left;color:#323E32;font-family:simsun;font-size:14px;margin-left:0px;">
<span style="font-family:Verdana;">说明：先使用能力爆发模式到行星 1，花费时间 1。<br/>
然后切换到高速航行模式，航行到行星 2，花费时间10。<br/>
之后继续航行到行星 3完成比赛，花费时间 1。<br/>
虽然看起来从行星 1到行星3再到行星 2更优，但我们却不能那样做，因为那会导致超能电驴爆炸。<br/>
<br/>
对于 30%的数据 N≤20，M≤50；<br/>
对于 70%的数据 N≤200，M≤4000；<br/>
对于100%的数据N≤800， M≤15000。输入数据中的任何数都不会超过10^6。<br/>
输入数据保证任意两颗行星之间至多存在一条航道，且不会存在某颗行星到自己的航道。</span> 
</p>
