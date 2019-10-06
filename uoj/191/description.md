# 题目描述

<p>原题目名字是“我们仍未知道那天所看见的数据结构的名字”，由于原题目名太长就叫Unknown了……</p>
<p>我们，渐渐地长大了。在这缓缓逝去的季节里，屏幕上闪烁的字符，也在静静地变化着。</p>
<p>那个季节里编写的数据结构，叫什么名字来着呢？</p>
<p>慢慢地，OI渐渐地淡去。而我们则在不断成长，但是那个程序一定仍在某个时空里继续运行着。</p>
<p>Salroey忘了那个数据结构的名字和内容，但她却记得题目，于是她来寻求你的帮助。</p>
<p>有一个元素为向量的序列，下标从1开始，初始时为空，现在你需要支持三个操作：</p>
<p>1.在$S$的末尾添加一个元素$(x,y)$。</p>
<p>2.删除$S$的末尾元素。</p>
<p>3.询问下标在$[l,r]$区间内的元素中，$(x,y) \times S_i$的最大值。</p>
<p>其中$\times$表示向量的叉积，$(x_1,y_1) \times (x_2,y_2) = x_1y_2-x_2y_1$</p>

# 输入格式


<p>第一行一个整数 $tp$ 表示数据类型，接下来输入多组数据(不超过 $3$ 组)，以 $m=0$ 结束，对于每组数据：</p>
<p>第一行一个整数 $m$ 表示操作数。</p>
<p>接下来行，每行有三种格式：</p>
<p>1 x y 在的末尾添加一个元素 $(x,y)$</p>
<p>2 删除的末尾元素</p>
<p>3 l r x y 询问下标在区间 $[l,r]$ 内的元素中，$(x,y) \times S_i$的最大值。</p>

# 输出格式


<p>为避免过多输出，你要将所有询问答案对M=998244353取模(数学意义上，取模的结果在[0,M)区间内)，并输出取模后答案的异或和，每组数据一行。</p>

# 样例一


<h4>input</h4>
<pre>7
6
1 -5 10
3 1 1 7 -9
2
1 2 6
1 -3 5
3 1 2 10 -7
0

</pre>

<h4>output</h4>
<pre>83

</pre>


# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<p>对于所有数据：</p>
<p>$0 \leq tp \leq 7, 1 \leq m \leq 500000$。</p>
<p>任意时刻 $n \geq 0$， $n$ 为当前序列长度。 </p>
<p>1操作个数不超过$300000$，且满足 $-10^9 \leq x \leq 10^9; 1 \leq y \leq 10^9$。</p>
<p>3操作个数不超过$300000$，且满足 $1 \leq x \leq 10^9; -10^9 \leq y \leq 10^9$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$tp$=</th>
<th>$m$ 的规模</th>
<th>其他</th>
</tr></thead><tbody><tr><td>1</td><td>1</td><td rowspan="2">$m \leq 1000$</td><td rowspan="3">无</td></tr><tr><td>2</td><td>1</td></tr><tr><td>3</td><td>2</td><td rowspan="1">$m \leq 100000$</td></tr><tr><td>4</td><td>3</td><td rowspan="3">$m \leq 300000$</td><td>无2操作，3操作的询问全部区间</td></tr><tr><td>5</td><td>4</td><td>所有2操作在1操作的后面，3操作的询问全部区间</td></tr><tr><td>6</td><td>5</td><td>所有3操作都在1操作和2操作后面</td></tr><tr><td>7</td><td>6</td><td rowspan="4">$m \leq 500000$</td><td>对于所有3操作有 $l=1$ ，内存限制为128M</td></tr><tr><td>8</td><td>7</td><td>无</td></tr><tr><td>9</td><td>7</td><td>内存限制为128M</td></tr><tr><td>10</td><td>7</td><td>内存限制为64M</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=191">样例数据下载</a></p>

# IOI赛制


<p>本题在考试时排行榜上显示的成绩即为最终评测结果。</p>
