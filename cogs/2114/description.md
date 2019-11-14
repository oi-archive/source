# 题目描述


<h3>
【题目描述】
</h3>
<p>
我们知道，斐波那契数被定义为
</p>
<p>
Fn=n,if n&lt;=1
</p>
<p>
Fn=Fn-1+Fn-2,otherwise
</p>
<p>
你的任务很简单，给定一个素数P，和非负整数C，找到最小的非负整数n，满足
</p>
<p>
Fn=C(mod P)
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数T，表示数据组数。接下来T行，每行两个非负整数C、P。
</p>
<h3>
【输出格式】
</h3>
<p>
对于每组数据输出最小的非负整数n，如果满足条件的n不存在，输出-1
</p>
<h3>
【样例输入】
</h3>
<p>
4
</p>
<p>
0 11
</p>
<p>
16 19
</p>
<p>
18 19
</p>
<p>
4 19
</p>
<h3>
【样例输出】
</h3>
<p>
0
</p>
<p>
14
</p>
<p>
16
</p>
<p>
-1
</p>
<h3>
【提示】
</h3>
<p>
1&lt;=T&lt;=100
</p>
<p>
11&lt;=P&lt;=2*10^9 P是素数
</p>
<p>
0&lt;=C&lt;=P - 1
</p>
<p>
(P mod 10)是完全平方数
</p>
<p>
我们保证，如果答案存在，则答案不会超过2*10^9
</p>
<h3>
【来源】
</h3>
<p>
Codechef FN<a href="https://www.codechef.com/problems/FN" target="_blank">CodeChef OCT13 Fibonacci Number</a> 
</p>
