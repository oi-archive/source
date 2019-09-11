# 题目描述


<h3>
【题目描述】
</h3>
<p>
福克斯·雪儿（Fox Ciel）正在学习数学。
</p>
<p>
她称一个包含非负整数的非空集合S是完美的，当且仅当对于任意<img src="/upload/image/20141119/20141119150821_12158.png" alt=""/>(a可能等于b)，都有<img src="/upload/image/20141119/20141119150844_29210.png" alt=""/>。其中xor是异或的意思。
</p>
<p>
请计算完美集合的数量，要求集合只包含不超过k的整数。答案可能非常大，只需要输出它摸1000000007（即10^9+7）的值
</p>
<h3>
【输入格式】
</h3>
<p>
一行一个整数k（0&lt;=k&lt;=10^9）。
</p>
<h3>
【输出格式】
</h3>
<p>
一行一个整数，即符合条件的完美集合数量模10^9+7的值。
</p>
<h3>
【样例】
</h3>
<p>
以下为四组样例：
</p>
<div class="sample-test">
<div class="input">
<div class="title">
Input
</div>
<pre>1
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>2
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>2
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>3
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>3
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>5
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>4
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>6</pre>
</div>
</div>
<h3>
【提示】
</h3>
<p>
在样例1中，有2个这样的集合：{0}和{0,1}。注意{1}不是完美集合，因为1 xor 1 = 0但{1}不包含0.
</p>
<p>
在样例4中，有6个这样的集合：{0},{0,1},{0,2},{0,3},{0,4},{0,1,2,3}。
</p>
<h3>
【来源】
</h3>
<p>
Codeforces Round #228 (Div.1)
</p>
