# 题目描述


<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">DaA 和他的朋友组成一个团队去旅行了。他们每个人都准备了一个背包，用来装旅行用</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 的物品。他们的背包有两个特点：</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 1. 每个人的背包能装无限多的物品，每种物品有一个价值，但只能装一件；</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 2. 每个人都很有个性，所以每个人的背包不会完全相同。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> DaA 的团队中有M 个人，那么对于整个团队，背包价值和最大是多少呢？</span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;"><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第一行两个整数M、N，表示团队的人数和物品的数量。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 接下来一行N 个整数，表示每件物品的价值wi。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"> 数据保证不会出现有空背包人的出现。</span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">一个整数，整个团队背包价值的最大值。</span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>Sample Input 1:
2 3
2 7 1
Sample Output 1:
19
Sample Input 2:
8 4
1 2 3 4
Sample Output 2:
58
</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【提示】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例解释】</span> 
</p>
<p>
	<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">19=(2+7+1)+(2+7)</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">58=(1+2+3+4)+(2+3+4)+(1+3+4)+(1+2+4)+(3+4)+(1+2+3)+(2+4)+(2+3)</span></span> 
</p>
<p>
	<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据规模】</span><br/>
<span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">30%的数据 1&lt;=M,N&lt;=15。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">60%的数据 1&lt;=M&lt;=200，1&lt;=N&lt;=100。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">100%的数据 1&lt;=M&lt;=1,000,000，1&lt;=N&lt;=500，0&lt;wi&lt;=50。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出请注意使用64 位整数（Pascal 中的Int64，C++中的long long）。</span></span><span><wi<=50。< span=""><br/>
<span></span></wi<=50。<></span> </span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【来源】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">清北学堂2012寒假培训 Test2</span> 
</p>
