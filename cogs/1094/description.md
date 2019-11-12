# 题目描述


<h3>
	【题目描述】
</h3>
<p>
	<br/>
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	有n个工作排成一个队列，每个工作有一个优先级，优先级是一个1到9之间的整数。
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	处理这些工作的流程如下：
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	1.把队头的工作取出
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	2.如果队列中有哪个工作的优先级比取出的这个工作要高，则把这个工作放到队尾去
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	3.否则，执行这个工作，不再放回队列
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	按照一开始在队列中的位置，工作们从左到右以0、1、2、……、n-1编号。告诉你每个工作的优先级，需要你求出一开始编号为m的工作是第几个被执行的。
</p>
<p>
	<br/>
</p>
<h3>
	【输入格式】
</h3>
<p>
	<br/>
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	第一行两个数n和m，n是队列中工作的个数，保证1≤n≤100，m是我所关心的那个工作的最初编号。保证0≤m≤n-1。
</p>
<p style="text-indent:21.0000pt;vertical-align:;">
	第二行n个1到9的整数，按顺序表示了n个工作的优先级。
</p>
<p>
	<br/>
</p>
<h3>
	【输出格式】
</h3>
<p>
	<br/>
</p>
<p>
	一个整数，表示我所关心的那个工作是第几个被执行的。
</p>
<p>
	<br/>
</p>
<h3>
	【样例输入】
</h3>
<pre>4 2
1 2 3 4</pre>
<h3>
	【样例输出】
</h3>
<pre>2</pre>
<p>
	<br/>
</p>
