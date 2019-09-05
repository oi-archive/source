# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
小w来到百度之星的赛场上，准备开始实现一个程序自动分析系统。
</p>
<p>
这个程序接受一些形如xi=xj 或 xi≠xj 的相等/不等约束条件作为输入，判定是否可以通过给每个 w 赋适当的值，来满足这些条件。
</p>
<p>
输入包含多组数据。
</p>
<p>
然而粗心的小w不幸地把每组数据之间的分隔符删掉了。
</p>
<p>
他只知道每组数据都是不可满足的，且若把每组数据的最后一个约束条件去掉，则该组数据是可满足的。
</p>
<p>
请帮助他恢复这些分隔符。
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
<p>
第1行：一个数字L，表示后面输入的总行数。
</p>
<p>
之后L行，每行包含三个整数，i,j,e，描述一个相等/不等的约束条件，若e=1，则该约束条件为xi=xj ，若e=0，则该约束条件为 xi≠xj 。
</p>
<p>
i,j,L≤100000
</p>
<p>
xi,xj≤L
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
输出共T+1行。
</p>
<p>
第一行一个整数T，表示数据组数。
</p>
<p>
接下来T行的第i行，一个整数，表示第i组数据中的约束条件个数。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
6
2 2 1
2 2 1
1 1 1
3 1 1
1 3 1
1 3 0
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
1
</p>

<p>
6
</p>
</pre>
<h3>
【提示】
</h3>
<p>
在此键入。
</p>
<h3>
【来源】
</h3>
<p>
2017百度之星程序设计大赛初赛第一场t2
</p>