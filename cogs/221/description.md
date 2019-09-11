# 题目描述


<p>
	【问题描述】
</p>
<p>
	Tom最近在研究一个有趣的排序问题。如图所示，通过2个栈S1和s2，Tom希望借助以下4种操作实现将输入序列升序排序。
</p>
<p>
	<span><img height="121" border="0" width="164" src="../../mw/images/f/f9/Noip08st1.jpg" alt="Image:Noip08st1.jpg"/></span>
</p>
<ul>
	<li>
		操作a
		<ul>
			<li>
				如果输入序列不为空，将第一个元素压入栈Sl
			</li>
		</ul>
	</li>
	<li>
		操作b
		<ul>
			<li>
				如果栈S1不为空，将Sl栈顶元素弹出至输出序列
			</li>
		</ul>
	</li>
	<li>
		操作c
		<ul>
			<li>
				如果输入序列不为空，将第一个元素压入栈s2
			</li>
		</ul>
	</li>
	<li>
		操作d
		<ul>
			<li>
				如果栈S2不为空，将S2栈顶元素弹出至输出序列
			</li>
		</ul>
	</li>
</ul>
<p>
	如果一个l～n的排列P可以通过一系列操作使得输出序列为l,2,…,(n-1)，n，Tom就称P是一个“可双栈排序排列”。例如 (1，3，2，4)就是一个“可双栈排序排列”，而(2，3，4，1)不是。下图描述了一个将(1，3，2，4)排序的操作序 列：<a,c,c,b,a,d,d,b></a,c,c,b,a,d,d,b>
</p>
<p>
	<span><img height="532" border="0" width="500" src="../../mw/images/7/7d/Noip08st2.jpg" alt="Image:Noip08st2.jpg"/></span>
</p>
<p>
	当然,这样的操作序列有可能有多个，对于上例(1，3，2，4)，<a，b，a，a，b，b，a，b>是另外一个可行的操作序列。Tom希望知道其中字典序最小的操作序列是什么。</a，b，a，a，b，b，a，b>
</p>
<p>
	【输入】
</p>
<p>
	输入文件twostack.in的第一行是一个整数n。
</p>
<p>
	第二行有n个刚空格隔开的正整数，构成一个1～n的排列。
</p>
<p>
	【输出】
</p>
<p>
	输出文件twostack.out共一行，如果输入的排列不是“可双栈排序排列”，输出数字0；
</p>
<p>
	否则输出字典序最小的操作序列，每两个操作之间用空格隔开，行尾没有空格。
</p>
<p>
	【输入输出样例1】
</p>
<p>
	twostack.in
</p>
<pre>4
1 3 2 4
</pre>
<p>
	towstack.out
</p>
<pre>a b a a b b a b
</pre>
<p>
	【输入输出样例2】
</p>
<p>
	twostack.in
</p>
<pre>4
2 3 4 1
</pre>
<p>
	towstack.out
</p>
<pre>0
</pre>
<p>
	<br/>
【输入输出样例3】
</p>
<p>
	twostack.in
</p>
<pre>3
2 3 1
</pre>
<p>
	towstack.out
</p>
<pre>a c a b b d
</pre>
<p>
	<br/>
【限制】
</p>
<ul>
	<li>
		30%的数据满足： n&lt;=10
	</li>
	<li>
		50%的数据满足： n&lt;=50
	</li>
	<li>
		100%的数据满足：n&lt;=1000
	</li>
</ul>
