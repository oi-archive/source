# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<center>
<img src="/upload/image/20140119/20140119215914_83767.gif" alt=""/>
</center>
<p>
<br/>
</p>
<p>
你一定听说过Kernighan和Ritchie，他们是《C程序设计语言》的作者。当在C语言中编程时，我们使用不同的控制语句和循环。例如,if-then-else（原文如此——译者注）,for,do-while等等。考虑如下伪代码：
</p>
<pre class="prettyprint lang-js">//execution starts here
do {
	U;
	V;
} while(condition);
W;</pre>
<p>
在上述代码中，每个分支都有一定的执行条件。这一代码可以用流程图表示如下：
</p>
<center>
<img src="/upload/image/20140119/20140119220254_26805.jpg" alt=""/>
</center>
<p>
对每个节点，令其转到任意后继的概率相等。因此，在上面的代码中，U执行的期望次数是2.在这个问题中，给出这样的一个流程图，请你找出每个节点的期望执行次数。
</p>
<h3>
【输入格式】
</h3>
<p>
输入包含至多100组数据。
</p>
<p>
每组数据的第1行是一个正整数n(1&lt;=n&lt;=100)。n是流程图中的节点个数。节点被从1到n编号，并且总是从1开始执行。
</p>
<p>
下面有若干行，每行2个正整数：start和end，意味着执行完start后可以转到end。以2个0结束。
</p>
<p>
下面一行有一个正整数q(1&lt;=q&lt;=100)，描述询问个数。
</p>
<p>
接下来的q行，每行一个正整数x，意味着询问节点x的期望执行次数。
</p>
<p>
输入文件以n=0结束。
</p>
<h3>
【输出格式】
</h3>
<p>
对第i组数据：
</p>
<p>
先输出一行&#34;Case #i:&#34;。
</p>
<p>
接下来输出q行，每行1个实数，表示该查询对应的期望次数。保留三位小数。某个节点有可能被永远执行（例如，一个无穷的for循环）。对于这种情况，输出&#34;infinity&#34;。
</p>
<p>
具体格式见样例。
</p>
<h3>
【样例输入】
</h3>
<pre>3
1 2
2 3
2 1
0 0
3
1
2
3
3
1 2
2 3
3 1
0 0
3
3
2
1
0
</pre>
<h3>
【样例输出】
</h3>
<pre>Case #1:
2.000
2.000
1.000
Case #2:
infinity
infinity
infinity
</pre>
<h3>
【提示】
</h3>
<p>
使用计算机中的“保留3位小数”指令。假设你的计算机能正确进行舍入。
</p>
<h3>
【来源】
</h3>
<p>
UVa10828 Back to Kernighan-Ritchie
</p>
<p>
刘汝佳，《算法竞赛入门经典训练指南》表2-12
</p>
<p>
Problem setter: Mohammad Sajjad Hossain
</p>
<p>
Special Thanks: Shahriar Manzoor
</p>
