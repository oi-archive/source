# 题目描述


<h3>
【题目背景】
</h3>
<p>
<br/>
</p>
<p>
(原题来自刘汝佳《训练指南》Page187,UVa 11991.)
</p>
<p>
可爱的小F就要过生日啦，为了刷存在感，我们的小F十分诚恳(xian de mei shi)地向女神小E要生日礼物。不过傲娇(2333)的小E当然不会随便答应的啦~为了为难小F，小E就说：
</p>
<p>
“如果你能做出这道简单题，我就给你礼物；如果做不出来，嘿嘿嘿嘿…”
</p>
<p>
小F感到一丝杀气…
</p>
<p>
为了保小命&amp;拿到礼物，信息学渣渣小F只得向你求助，小F能不能拿到梦寐以求的女神的礼物，全靠你了！
</p>
<p>
<br/>
</p>
<h3>
【题目描述】
</h3>
<p>
给出一个包含n个整数的数组，你需要回答m个询问。
</p>
<p>
每次询问两个整数k和v，输出从左到右第k个v的下标(数组下标从左到右编号为1~n)。
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
每组数据第一行为两个整数n和m，第二行包含n个正整数，即待查询的数组。
</p>
<p>
以下m行每行包含两个整数k和v，意义与题目描述中的相同。
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
对于每个查询，输出查询结果。如果不存在，输出0。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
5 3
</p>

<p>
1 2 3 3 5
</p>

<p>
1 1
</p>

<p>
2 5
</p>

<p>
2 3
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
1
</p>

<p>
0
</p>

<p>
4
</p>
</pre>
<h3>
【数据范围】
</h3>
<p>
1&lt;=n,m&lt;=100000.
</p>
<p>
数组中的元素均不超过100000.
</p>
<p>
1&lt;=k&lt;=n,1&lt;=v&lt;=100000.
</p>
<h3>
【提示】
</h3>
<p>
这题PID不错
</p>
<h3>
【来源】
</h3>
<p>
HZOI 2016
</p>