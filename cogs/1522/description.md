# 题目描述


<h3>
【题目描述】
</h3>
<p>
Farmer Johnson的公牛们非常喜欢打篮球。但它们都不愿意一起打篮球，因为所有公牛都认为其他的牛弱爆了。Farmer Johnson有N头牛（我们把它们编号为1~N）和M个牛棚（我们把它们编号为1~M），这些牛棚就是公牛们的篮球场。但FJ的公牛非常挑剔，它们只会在自己喜欢的牛棚打球，并且都不愿意和其他的牛共享牛棚。
</p>
<p>
因此安排他的公牛对Farmer Johnson来说是一项艰难的任务，他希望得到你的帮助。当然，找到一种方案是容易的，但你的任务是找出一共有多少种方案。
</p>
<p>
一个方案是一种使得所有公牛都能在它喜欢的牛棚中快乐玩耍，并且没有两只牛共享一个牛棚的安排方式。
</p>
<p>
答案不会超过<strong>32位无符号整数范围</strong>。（其实用unsigned int 会溢出，懒得改数据了，直接用unsigned int就好了，别用long long！）
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有两个正整数N，M（1&lt;=N,M&lt;=20）。
</p>
<p>
接下来有N行，第i行的开头有一个正整数P(1&lt;=P&lt;=M)，代表第i头牛喜欢的牛棚数量。接下来有P个正整数，即P个牛棚的编号。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个正整数，即方案总数。
</p>
<h3>
【样例输入】
</h3>
<pre class="sio">3 4
2 1 4
2 1 3
2 2 4
</pre>
<h3>
【样例输出】
</h3>
<pre class="sio">4</pre>
<h3>
【来源】
</h3>
<div class="ptx" lang="zh-CN">
<a href="searchproblem?field=source&amp;key=POJ+Monthly">POJ Monthly</a>,TN
</div>
<a href="http://www.poj.org/problem?id=2441&amp;lang=zh-CN&amp;change=true"> 北京大学 POJ 2441</a>
