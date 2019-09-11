# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
留意着农场之外的长期职业生涯的可能性，奶牛Bessie开始在不同的在线编程网站上学习算法。
</p>
<p>
她到目前为止最喜欢的算法是“冒泡排序”。这是Bessie的对长度为N的数组A进行排序的奶牛码实现。
</p>
<p>
sorted = false
</p>
<p>
while (not sorted):
</p>
<p>
  sorted = true
</p>
<p>
  moo
</p>
<p>
  for i = 0 to N-2:
</p>
<p>
     if A[i+1] &lt; A[i]:
</p>
<p>
        swap A[i], A[i+1]
</p>
<p>
        sorted = false
</p>
<p>
显然，奶牛码中的“moo”指令的作用只是输出“moo”。奇怪的是，Bessie看上去执着于在她的代码中的不同位置使用这个语句。
</p>
<p>
给定一个输入数组，请预测Bessie的代码会输出多少次“moo”。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
输入的第一行包含N（1≤N≤100,000）。接下来N行描述了A[0]…A[N−1]，每个数都是一个范围为0…10^9的整数。输入数据不保证各不相同。
</p>
<h3>
【输出格式】
</h3>
<p>
输出“moo”被输出的次数。
</p>
<h3>
【样例输入】
</h3>
<pre>5
1
5
3
8
2
</pre>
<h3>
【样例输出】
</h3>
<pre>4</pre>
<h3>
【数据规模】
</h3>
<p>
40%的数据N&lt;=10000;<br/>
60%的数据N&lt;=100000;<br/>
80%的数据大小顺序时混乱的;
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://www.usaco.org/index.php?page=open18results" target="_blank">USACO 2018 OPEN CONTEST</a> Silver Problem 1
</p>
<p>
供题：Brian Dean
</p>
