# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">联络完毕的圣战的战士们，终于等到了集结的号角。他们蜂拥而上，前往与Bugall军团交锋的战场。<br/>
 Varpro已经准备好了一辆通往战场的飞艇，按照他的计划，这个飞艇将能容纳最多N个战士，当然他希望这N个战士总战斗力最强。<br/>
 不幸的是，由于组织者没有进行合理的秩序安排，战士们在通往战场的飞艇前挤成了一个大堆；由于时间和空间关系，Varpro已经无法对战士按照战斗力重新列队，只能从这一堆人中靠前的挑选战士。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">  我们可以将圣战的战士们挤成的一个堆抽象成一个树的模型；树的根就是飞艇。一个战士可以进入飞艇，当且仅当他到飞艇上的路径中的战士已经全部进入了飞艇。当然，Varpro已经在飞艇上等待大家了（我们可以认为他，也就是树根，是0号节点），他可是拥有4千万战斗力的勇士呢。<br/>
 现在请你帮Varpro计算，他最多可以带上的勇士的战斗力之和最大是多少。<br/>
</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第一行包括两个数M，N，分别代表战士的总人数和飞艇上能容纳的战士数。<br/>
 第2~m+1行每行描述了一个战士，分别代表该战士之前的战士（树中的父节点）的编号xi，和这个战士的战斗力wi。<br/>
</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">只有一行，飞艇最多可以带的勇士的战斗力之和（包括已经在飞艇上的Varpro的战斗力）。</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输入】</span> 
</h3>
<pre>7 5
2 2
0 1
0 4
2 1	
7 1
7 6
2 2
 </pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【样例输出】</span> 
</h3>
<pre>40000013</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">20%的数据保证：1&lt;=m,n&lt;=50；<br/>
 70%的数据保证：1&lt;=m,n&lt;=500；<br/>
 100%的数据保证：1&lt;=m&lt;=10000，1&lt;=n&lt;=500，0&lt;=xi&lt;=n，0&lt;=wi&lt;=500。<br/>
 提示：对于已经在飞艇上的Varpro，他的战斗力是常量40000000并且不在数据中出现。<br/>
 <br/>
</span> 
</p>
