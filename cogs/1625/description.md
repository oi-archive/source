# 题目描述


<h3>
【题目描述】
</h3>
<p>
在2100年，ACM牌巧克力成为了地球上最受欢迎的食品之一。
</p>
<p>
“绿色的，橙色的，棕色的，红色的……”，多彩的糖衣外壳可能是ACM巧克力最吸引人之处。你曾经看到过多少种颜色？如今，据说ACM公司用24色调色板来给他们美味的巧克力豆上色。
</p>
<p>
一天，Sandy用一大包有五种颜色（红黄绿橙棕）的ACM巧克力玩了一个游戏。每次他从包里拿出一颗巧克力豆，并将其放在桌子上。如果桌子上有两个巧克力豆的颜色相同，他就把它们都吃掉。他发现了一个有趣的事实：在大部分时候，桌子上有2或者3颗巧克力豆。
</p>
<p>
现在问题来了。如果包里有C种颜色的ACM巧克力（它们被随机打乱），在从包中拿出N颗巧克力豆后，桌子上恰好有M颗巧克力豆的概率是多少？你能写一个程序解决这个问题吗？
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含多组数据。
</p>
<p>
输入文件的第一行有三个非负整数：C（C&lt;=100），N，M（N,M&lt;=1000000）。
</p>
<p>
输入结束标志为一行一个0.
</p>
<h3>
【输出格式】
</h3>
<p>
对每组数据输出一行一个实数，即所求概率，保留三位小数。
</p>
<h3>
【样例输入】
</h3>
<pre>5 100 2
0</pre>
<h3>
【样例输出】
</h3>
<pre>0.625</pre>
<h3>
【提示】
</h3>
<p>
可以认为包中有无数颗巧克力豆。
</p>
<p>
当且仅当你的答案和标准答案之差不大于0.002时，你的答案被认为是正确的。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://poj.org/problem?id=1322" target="_blank">POJ1322 Chocolate</a> 
</p>
<p>
ACM/ICPC Regional Contest Beijing 2002 Problem F Chocolate
</p>