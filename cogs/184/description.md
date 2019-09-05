# 题目描述


<p>
勤奋的农夫约翰想要修建一个4面的篱笆墙把他的奶牛们围起来。他有一块长为N的木板$（4&lt;=N&lt;=2500）$于是他想要在三个点把他们切断用以得到4块木板。
</p>
<p>
只要能构成成四边形篱笆，这4块板子的长度可以是任意正整数。那么为了得到完整的篱笆农夫约翰有多少不同的种方法切这个长木板呢？
</p>
<p>
注意：
</p>
<ul>
<li>
对于两种方案而言，只要一方存在一个另一方没有的切割点，那它们就将视为不同的方案。不必担心对称或那个其他复杂的情况的排除。
</li>
<li>
请注意，篱笆所围的面积应当大于0。
</li>
<li>
你将高兴的是，我们保证答案适合有符号的32位整型变量。
</li>
</ul>
<p>
分数：250
</p>
<p>
问题名称：quad
</p>
<p>
输入格式：
</p>
<ul>
<li>
第1行：一个单独的整数：N
</li>
</ul>
<p>
输入样例（file quad.in）：
</p>
<pre>6
</pre>
<p>
输入说明：这个板子的长度是6。
</p>
<p>
输出格式：
</p>
<ul>
<li>
第1行：一个单独的整数表示切割方案数。
</li>
</ul>
<p>
输出样例：
</p>
<p>
6
</p>
<p>
输出说明：
</p>
<p>
农夫约翰有10种方法切割木板：
</p>
<p>
$(1, 1, 1, 3); (1, 1, 2, 2); (1, 1, 3, 1); (1, 2, 1, 2); (1, 2, 2, 1);$
</p>
<p>
$(1, 3, 1, 1); (2, 1, 1, 2); (2, 1, 2, 1); (2, 2, 1, 1); (3, 1, 1, 1).$
</p>
<p>
但是其中的4种--$(1, 1, 1, 3), (1, 1, 3, 1), (1, 3, 1, 1), (3 ,1, 1, 1)$是不能构成篱笆的。
</p>