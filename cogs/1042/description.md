# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><strong>题目叙述</strong></span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">Freda 的旅行社开通了一条暑期旅行路线，路线可以被看成是一条直线。这条路线一共</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">经过N 个地区，N 个地区的管辖范围完全覆盖了整条旅行路线且管辖范围之间两两没有重合。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">我们知道，地区与地区之间的气温可能是不同的，第i 个地区的气温设为ti.报名旅行</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">的M 名游客都要乘车从第1 个地区前往第N 个地区,每辆车的容量没有限制。当然，谁也不想</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">让自己乘坐的车里温度太高。假设经过第i 个地区的时候，一辆车上面有k 名乘客，那么这</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">辆车上的温度就是ti+k。如果某辆车上的温度超过了这个地区的“最热限制”Ti(ti+k&gt;Ti)，</span><br/>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">这辆车上的每个乘客都会向旅行社索赔xi 元钱，用法律武器维护自己合法权益。</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-size:14px;"></span><br/>
</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-size:14px;">还有很特殊的一点，游客所乘坐的车不是从1~N 直达的，而是在各个地区分别租用的。</span><br/>
<span style="font-size:14px;"> 在第i 个地区租用的车只能在第i 个地区的管辖范围内行驶。即进入第i 个地区时，租用第</span><br/>
<span style="font-size:14px;"> i 个地区的车，离开第i 个地区时，就要继续租用第i+1 个地区的车。在第i 个地区，你可</span><br/>
<span style="font-size:14px;"> 以租用任意数量的车，租用一辆车的费用是ci。</span><br/>
<br/>
</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-size:14px;">下面，Freda 请你帮忙设计一个花费最小的方案，即设计在每个地区的租车数目以及此</span><br/>
<span style="font-size:14px;"> 时安排到每辆车上的乘客数目。这个方案的花费是租车费用+给乘客的赔偿金（如果有的话）,</span><br/>
<span style="font-size:14px;"> 输出这个最小花费。</span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-size:14px;"></span><br/>
<strong></strong><strong><span style="font-size:14px;">输入格式</span></strong><br/>
<span style="font-size:14px;"> 第一行两个整数N，M，表示地区数目和乘客数目。</span><br/>
<span style="font-size:14px;"> 接下来N 行每行4 个整数，第i 行的4 个整数表示ti,Ti,xi,ci.含义如上所示。</span></span> 
</p>
<p>
	<span></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong><span style="font-size:14px;">输出格式</span></strong><strong></strong><span></span><br/>
<span style="font-size:14px;"> 一行一个整数表示最小花费。</span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong><span style="font-size:14px;">输入样例</span></strong><strong></strong><strong></strong><br/>
</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-size:14px;">2 10</span><br/>
<span style="font-size:14px;"> 30 35 1 100</span><br/>
<span style="font-size:14px;"> 20 35 10 10</span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"><strong>输出样例</strong></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">120</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong><span style="font-size:14px;">样例解释</span><br/>
</strong></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-size:14px;">在第1 个地区，租用1 辆车，车内温度为30+10=40&gt;35，需要给乘客每人1 元补偿费。</span><br/>
<span style="font-size:14px;"> 在第2 个地区，租用1 辆车，车内温度为20+10=30&lt;35，不需要给乘客补偿费。</span><br/>
<span style="font-size:14px;"> 总费用为100（第一个地区的租车费用）+10（第二个地区的租车费用）+10（第一个地</span><br/>
<span style="font-size:14px;"> 区的补偿费用）=120.</span></span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><strong><span style="font-size:14px;">数据范围与约定</span></strong><strong></strong><br/>
</span> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-size:14px;">对于50%的数据，N&lt;=100, M&lt;=100.</span><br/>
<span style="font-size:14px;"> 对于100%的数据，0</span><n<=10^5, 0<m<="10^6," 0<xi,ci,ti,ti<="10^6.&lt;/span"> </n<=10^5,></span> 
</p>
