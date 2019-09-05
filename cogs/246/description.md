# 题目描述


<p>
	由于他们的谍报人员最近发生了不幸，中央情报局驻Byteland决定提升其特工人员的活动能力。为了让其特工人员能安全会晤，这是迄今为止麻烦最 大的一次准备活动。我们的程序就是为了解决这些问题。对于一给定的Byteland的公路网络，以及俩特工人员的初始位置，我们应该能够回答他们的安全会 晤是不是可能的。同时，为了使安全会晤成为可能，特工人员要做到以下几点：
</p>
<ul>
	<li>
		特工人员白天行动，碰面只能在晚上；
	</li>
	<li>
		特工人员必须每天改变他的行踪（一天内不能呆在同一城市）；
	</li>
	<li>
		特工人员只能沿着连接俩城市的公路走（不幸的是，在Byteland，公路是单向的）；
	</li>
	<li>
		特工人员不能走的太快（避免怀疑）---一天内他顶多只能从一个城市到另一城市；
	</li>
	<li>
		任意俩城市的距离都很短，特工人员早上从一城市出发傍晚之前就能到达另一城市；
	</li>
	<li>
		安全的碰面意味着俩特工人员在同一个傍晚到达同一城市。
	</li>
</ul>
<p>
	要求
</p>
<p>
	编写一程序：
</p>
<ol>
	<li>
		从文件中读入Byteland的城市个数、公路网络描述，以及特工人员的初始位置；
	</li>
	<li>
		核对是否存在一安全的碰面，若存在，则计算须多少天来安排这次会晤；
	</li>
	<li>
		结果写入文件中。
	</li>
</ol>
<p>
	输入
</p>
<p>
	在第一行为俩整数n、m，1&lt;=n&lt;=250,0&lt;=m&lt;=n*(n-1)。n表示城市的个数，m表示道路的条 数。第二行的整数a(1),a(2)分别表示1号和2号特工人员的出发位置。接下来的m行每行为俩自然数a、b，用空格隔开，1&lt;=a、b&amp; lt;=n,并且a&lt;&gt;b,表示从城市a到城市b存在一道路。
</p>
<p>
	输出
</p>
<p>
	或者恰有一正整数，它表示安排这次安全会晤的最小时间（以天数作为单位），如果这样的碰面可能的话；或者为一单词NIE，如果这样的碰面不可能的话。
</p>
<p>
	样例输入
</p>
<pre>6 7
1 5
1 2
4 5
2 3
3 4
4 1
5 4
5 6
</pre>
<p>
	样例输出
</p>
<pre>3
</pre>