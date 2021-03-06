# 题目描述


<h3>
题目描述
</h3>
<p>
小X 是个聪明的孩子，他记得斐波那契数列
</p>
\[ \begin{array}{ll}
f(x)=f(x-1)+f(x-2) &amp; x&gt;2 \\
f(x)=1  &amp; 0 &lt; x \le 2 
\end{array} \]
<p>
中前1000个数。不过由于学业的压力，他无法记得每一个数在数列中的位置。他现在知道数列中的一个数f(x)模P后的值N（即N=f(x)ModP）以及x可能的最大值M，如果再对于斐波那契数列中每一个数都模P，他想知道所知道的这个数可能出现在第几个。不过小X 还要做作业呢，这个问题就交给你由编程来解决了。
</p>
<h3>
输入
</h3>
<p>
一行，共3个整数，第一个数为N，第二个数为P，第三个数为M，三个数以空格隔开。
</p>
<h3>
输出
</h3>
<p>
一个整数，满足f(i)ModP=N的最小的i，如果不存在则输出-1。
</p>
<h3>
样例输入
</h3>
<pre>3 7 5</pre>
<h3>
样例输出
</h3>
<pre>4</pre>
<h3>
提示
</h3>
<p>
斐波那契数列前5项为1 1 2 3 5，全部模7后仍为1 1 2 3 5，则3最早出现在第4个，即满足f(x) ≡ N(ModP)的最小的x为4。
</p>
<h3>
【数据范围与约定】
</h3>
<p>
对于20%的数据，保证0＜M≤50
</p>
<p>
对于50%的数据，保证0＜M≤100
</p>
<p>
对于70%的数据，保证0＜M≤500
</p>
<p>
对于100%的数据，保证0＜M≤1000，0≤N
</p>
<p>
请注意，最终评测采用文件读写。输入输出文件名在输入输出格式中有
</p>
<p>
请注意查看答疑贴，程序请发到邮箱，最后统一评测
</p>
