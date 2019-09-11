# 题目描述


<h3>
【题目描述】
</h3>
<p>
<img src="/upload/image/20140113/20140113131905_51805.png" alt=""/> 
</p>
<p>
组合数学主要研究计数问题。比如，
</p>
<p>
-从n个人中选2个人的方法有多少种方法？
</p>
<p>
-圆周上有n个点，两两相连之后最后能把圆面分成多少部分？
</p>
<p>
-有一个金字塔，从塔顶开始每一层分别有，1×1,2×2，...n×n个小正方体，问一共有多少个小立体？
</p>
<p>
很多问题的答案都可以被写成多项式的形式。对应上面的问题，答案是：
</p>
<p>
<strong>-  n(n-1)/2</strong> 
</p>
<p>
-  <strong>(n^4 - 6n^3 + 23n^2 - 18^n + 24)/24</strong> 
</p>
<p>
-  <strong>n(n + 1)(2n + 1)/6</strong><strong>, or </strong><strong>(2n^3 + 3n^2 + n)/6</strong> 
</p>
<p>
由于上述3个多项式都是计数问题的答案，因此当n取任意正整数时，这些多项式的值都是整数。当然，对于其他多项式，这个性质并不一定成立。
</p>
<p>
给一个形式如<strong>P/D</strong>(其中P是整系数多项式，D是正整数)的多项式，判断它是否在所有正整数处取的整数值。
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含多组数据。每组数据仅一行，即一个多项式<strong>(P)/D</strong>,其中P是若干个形如<strong>Cn^E</strong>的项之和，其中系数C和E满足以下条件：
</p>
<p>
(1)E是一个满足0≤E≤100的整数。如果E=0，则<strong>Cn^E</strong>写成C；如果E=1，<strong>Cn^E</strong>写成<strong>Cn</strong>，除非<strong>C</strong>=1或者-1(c=1时写成n=-1是写成-n).
</p>
<p>
(2)C是一个整数。如果C为1或-1且E不是0或1，则<strong>Cn^E</strong>写成<strong>n^E</strong>或<strong>-n^E</strong>.
</p>
<p>
(3)只有不在第一项的非负C的前面才会有一个加号。
</p>
<p>
(4)E的数值严格递减。
</p>
<p>
(5)C和D都在32位带符号整数范围内。
</p>
<p>
输入结束标志为单个句号(.)。
</p>
<h3>
【输出格式】
</h3>
<p>
对于每组数据，如果满足条件，输入&#34;Always an integer&#34;,否则输出&#34;Not always an integer&#34;
</p>
<h3>
【样例输入】
</h3>
<pre>(n^2-n)/2
(2n^3+3n^2+n)/6
(-n^14-11n+1)/3
.
</pre>
<h3>
【样例输出】
</h3>
<pre>Case 1: Always an integer
Case 2: Always an integer
Case 3: Not always an integer
</pre>
<h3>
【提示】
</h3>
<p>
Difference Series
</p>
<h3>
【来源】
</h3>
<p>
UVa 1069 Always an Integer,World Finals 2008,LA 4119
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2.4
</p>
