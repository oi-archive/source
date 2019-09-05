# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
你可能记得我们之前的几场，$Vova$真的很喜欢电脑游戏。现在他正在玩一种被称为“帝国愤怒”的战略游戏。
</p>
<p>
在游戏中，$Vova$可以雇佣$n$个不同的战士；第$i$个战士为$a_i$类型。$Vova$希望雇佣来一些战士建立一支平衡的军队。如果在游戏中出现的每一类战士在军队中不超过$k$个此类战士，则此时军队被称为平衡。当然，$Vova$希望他的军队尽可能的大。
</p>
<p>
为了使事情变得更复杂，$Vova$必须考虑$q$种不同的组建军队的计划。第i个计划要求他雇佣勇士的编号在区间$[l_i，r_i]$之间。
</p>
<p>
帮助$Vova$确定每个计划中能使军队平衡的最大规模。
</p>
<p>
请注意，这些计划以一种修改后的方式给出。有关详细信息，请参见输入部分。
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
第一行包含两个数$n$和$k(1≤n，k≤10^5)$。
</p>
<p>
第二行包含n个整数$a_1$，$a_2$，…，$a_n(1≤a_i≤10^5)$。
</p>
<p>
第三行包含一个整数$q(1≤q≤10^5)$。
</p>
<p>
之后有q行，每行两个整数$x_i$和$y_i(1≤x_i，y_i≤n)$。
</p>
<p>
你必须记录上一个计划的结果(让我们把它称为$last$)。开始时$last=$0。然后为了恢复第i计划中$l_i$和$r_i$的价值，你必须做以下工作:
</p>
<p>
  1.$l_i = ((x_i + last) mod  n) + 1$;
</p>
<p>
  2.$r_i = ((y_i + last) mod  n) + 1$;
</p>
<p>
  3.如果$l_i &gt; r_i$，则交换 $l_i$ 和 $r_i$的值。
</p>
<h3>
【输出格式】
</h3>
<p>
输出$q$行，每行一个数字。其中第$i$个数字表示第$i$个计划中能使军队平衡的最大规模。
</p>
<h3>
【样例输入】
</h3>
<pre>6 2
1 1 1 2 2 2
5
1 6
4 3
1 1
2 6
2 6
</pre>
<h3>
【样例输出】
</h3>
<pre>2
4
1
3
2
</pre>
<h3>
【提示】
</h3>
<p>
样例中计划为: 
</p>
<p>
1.1 2 
</p>
<p>
2.1 6 
</p>
<p>
3.6 6 
</p>
<p>
4.2 4 
</p>
<p>
5.4 6
</p>
<h3>
【来源】
</h3>
<p>
codeforces上的Educational Codeforces Round 22 E
</p>
<p>
<a href="http://codeforces.com/contest/813/problem/E" target="_blank">http://codeforces.com/contest/813/problem/E</a> 
</p>