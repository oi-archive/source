# 题目描述


<h3>
【题目描述】
</h3>
<p>
</p><p>
在一个拙劣的尝试中，贝茜为提高自己的获奖机会，增强了流动性，，农夫约翰给每个贝茜的腿已经附加了一个弹簧高跷。
</p>
<p>
贝茜现在可以很快的跳过农场，但她没有学会慢下来。
</p>
<p>
<br/>
</p>
<p>
为了帮助贝茜更好的控制跳跃，农民约翰在通过农场的一维路径上开设了实践课。他在路径不同的位置上设置了N个目标，让贝茜尝试落地(1 &lt;= N &lt;= 1000) 。
</p>
<p>
<br/>
</p>
<p>
目标i位于x(i),如果贝茜落在这个目标上，则得p(i)分。
</p>
<p>
可以把开始点自己选择在任何目标的位置，但只允许向一个方向跳，从目标到目标。每一跳必须至少为前一跳的距离，并且必须落在土地上的目标上。
</p>
<p>
<br/>
</p>
<p>
贝茜收到为她设置的每一个目标（包括初始目标）。请计算她可以获得的最大分数。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
</p><p>
第1行：整数N.
</p>
<p>
<br/>
</p>
<p>
第2..1+N行: 第i+1行 包含x（i）和P（i），每一个整数的范围0..1,000,000。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
</p><p>
1行：贝茜可以得到的最大分数。
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<pre><p>
6

5 6

1 1

10 5

7 6

4 8

8 10
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>25</pre>
<h3>
【提示】
</h3>
<p>
</p><p>
输入详细信息：
</p>
<p>
<br/>
</p>
<p>
有6个目标。第一是在位置x = 5的,能得6分，等等。
</p>
<p>
输出的细节：
</p>
<p>
贝茜跳从位置x = 4（8点）到位置x = 5（6分）到位置x = 7（6点）到位置x = 10（5分）。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【来源】
</h3>
<p>
在此键入。
</p>