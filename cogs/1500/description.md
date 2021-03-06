# 题目描述


<h3>
【题目描述】
</h3>
<p>
Josephina是一名聪明的妹子，她最近痴迷于机器学习。她花费了大量精力学习线性判别分析，因为其中有不少有趣的性质。
</p>
<p>
为了测试算法的性能，她收集了许多数据。每组数据都分成两个部分：训练数据和测试数据。她在训练数据中解算模型的参数，并且在测试数据中测试这个模型。
</p>
<p>
令她惊讶的是，她发现每组数据的误差曲线都是一条抛物线。一条抛物线对应一个二次函数。在数学中，二次函数指形如$f(x)=ax^2+bx+c$的多项式函数。如果a=0，二次函数就退化为线性函数。
</p>
<p>
</p><center><img src="/upload/image/20140121/20140121202243_13292.jpg" alt=""/></center>
<p></p>
<p>
如果只有一条误差曲线，那么计算最小的误差将非常简单。但这里有多组数据，这意味着Josephina将得到多组误差曲线。Josephina希望调整参数以更好地拟合所有数据。因此她必须统计所有的误差曲线。也就是说，她必须处理许多二次函数，并得出一条新的错误曲线来代表所有的错误。现在，她正关注一个与许多二次函数有关的函数的最小值。
</p>
<p>
这个新函数定义如下：
</p>
<p>
$F(x)=\max({S_i(x)}),i=1,2,...,n$。$x$的范围是$[0,1000]$。$S_i(x)$是一个二次函数。
</p>
<p>
Josephina希望知道$F(x)$的最小值。不幸的是，用代数方法求解过于复杂。作为一名机智的程序员，你能帮她解决这个问题吗？
</p>
<p>
</p><center><img src="/upload/image/20140121/20140121203223_31510.jpg" alt=""/></center>
<p></p>
<h3>
【输入格式】
</h3>
<p>
输入包含多组数据。
</p>
<p>
输入文件的第1行是1个正整数T(T&lt;100)，表示数据组数。
</p>
<p>
每组数据的第1行是一个正整数n(n&lt;=10000)。
</p>
<p>
接下来的n行，每行有3个正整数a(0&lt;=a&lt;=100),b(|b|&lt;=5000),c(|c|&lt;=5000)，描述一个二次方程的相应系数。
</p>
<h3>
【输出格式】
</h3>
<p>
对每组数据，输出一行一个实数，即答案。
</p>
<h3>
【样例输入】
</h3>
<pre>2
1
2 0 0
2
2 0 0
2 -4 2
</pre>
<h3>
【样例输出】
</h3>
<pre>0.0000
0.5000
</pre>
<h3>
【提示】
</h3>
<p>
答案允许有不超过0.01的误差。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://uva.onlinejudge.org/index.php?option=com_onlinejudge&amp;Itemid=8&amp;category=493&amp;page=show_problem&amp;problem=4222" target="_blank">UVa 1476 Error Curves</a> 
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2-14
</p>
