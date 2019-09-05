# 题目描述


<h3>
【题目描述】
</h3>
<p>
每一头牛的愿望就是变成一头最受欢迎的牛。现在有N头牛，给你M对整数（A，B），表示牛 A 认为牛 B 受欢迎。这种关系是具有传递性的，如果A认为B受欢迎，B认为C受欢迎，那么牛A也认为牛C受欢迎。你的任务是求出有多少头牛被所有的牛认为是受欢迎的。
</p>
<h3>
【输入格式】
</h3>
<p>
第1行两个整数N，M；
</p>
<p>
接下来M行，每行两个数A，B，意思是A认为B是受欢迎的（给出的信息有可能重复，即有可能出现多个A，B）
</p>
<h3>
【输出格式】
</h3>
<p>
一个数，即有多少头牛被所有的牛认为是受欢迎的。
</p>
<h3>
【样例输入】
</h3>
<pre>3 3
1 2
2 1
2 3
</pre>
<h3>
【样例输出】
</h3>
<pre>1</pre>
<h3>
【数据范围】
</h3>
<p>
10%的数据N&lt;=20,M&lt;=50
</p>
<p>
30%的数据N&lt;=1000,M&lt;=20000
</p>
<p>
70%的数据N&lt;=5000,M&lt;=50000
</p>
<p>
100%的数据N&lt;=10000,M&lt;=50000
</p>