# 题目描述


<h3>
【题目描述】
</h3>
<p>
HA的MK 以前曾经同时与一些傻二哈交♂往♂，傻二哈们之间的关系成一棵树。
</p>
<p>
一开始每个傻二哈对他都有一个好感度。因为 MK 太神犇了，所以很多傻二哈给他出了一些题目，
</p>
<p>
他每 AC 一道 编号为WCG的傻二哈 出给他的题目会导致以 WCG为根的子树中除了 WCG 以外所有的傻二哈对他的好♂感♂度
</p>
<p>
下降。
</p>
<p>
操作 1: MK AC 了 WCG 出的题目导致以 WCG为根的子树中除了 WCG 以外所有的傻二哈对他的好♂感♂度下
</p>
<p>
降。
</p>
<p>
操作 2: MK 想要知道以 WCG 为根的子树中除了 WCG 以外还有几个对他好感度&gt;0 的。
</p>
<p>
树根处的傻二哈编号为 0，它对 MK 的好♂感♂度♂可以看做是无限的
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个整数 N。
</p>
<p>
代表有 N+1 个傻二哈，编号分别是 0~N。
</p>
<p>
接下来 N 行每行两个整数，第一个整数表示编号为 i 的傻二哈的好♂感♂度♂ H，第二个整数表示第
</p>
<p>
i 个傻二哈在树上的父亲 Fi。（保证傻二哈 i 的父亲的编号小于 i）。
</p>
<p>
接下来一行一个整数 Q。
</p>
<p>
接下来 Q 行，每行一个操作。
</p>
<p>
第一类操作读入三个参数{1,Ai,Xi}表示 QY 使以 Ai 为根的子树中除了 Ai 以外所有的傻二哈
</p>
<p>
对他的好感度下降 Xi。
</p>
<p>
第二类操作读入两个参数{2,Ai}表示询问以 Ai 为根的子树中除了 Ai 以外有几个傻二哈对 MK
</p>
<p>
的好感度&gt;0。
</p>
<h3>
【输出格式】
</h3>
<p>
对于每一个第二类操作，输出一行一个整数，表示所询问的答案。
</p>
<h3>
【样例输入】
</h3>
<pre>4
1 0
2 0
2 2
1 2
4
1 2 1
2 2
1 0 1
2 0
</pre>
<h3>
【样例输出】
</h3>
<pre>1
1
</pre>
<h3>
【提示】
</h3>
<p>
对于 30%的数据，满足 1&lt;=N&lt;=1000，1&lt;=Q&lt;=1000。
</p>
<p>
对于另外 20%的数据，保证数据纯随机生成。
</p>
<p>
对于 100%的数据，满足 1&lt;=N&lt;=10^5，1&lt;=Q&lt;=10^5，0&lt;=Ai&lt;=N，1&lt;=Hi&lt;=10^9，1&lt;=Xi&lt;=10^4，
</p>
<p>
0&lt;=Fi&lt;i。
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>
