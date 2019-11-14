# 题目描述


<h3>
【题目描述】
</h3>
<p>
</p><p>
<span style="font-size:medium;">一棵树上有n个节点，编号分别为1到n，每个节点都有一个权值w。我们将以下面的形式来要求你对这棵树完成一些操作： </span>
</p>
<p>
<span style="font-size:medium;">I. CHANGE u t : 把结点u的权值改为t </span>
</p>
<p>
<span style="font-size:medium;">II. QMAX u v: 询问从点u到点v的路径上的节点的最大权值 </span>
</p>
<p>
<span style="font-size:medium;">III. QSUM u v: 询问从点u到点v的路径上的节点的权值和 </span>
</p>
<p>
<span style="font-size:medium;">注意：从点u到点v的路径上的节点包括u和v本身</span> 
</p>
<p></p>
<h3>
【输入格式】
</h3>
<p>
</p><p>
<span style="font-size:medium;">输入的第一行为一个整数n，表示节点的个数。</span>
</p>
<p>
<span style="font-size:medium;">接下来n – 1行，每行2个整数a和b，表示节点a和节点b之间有一条边相连。</span>
</p>
<p>
<span style="font-size:medium;">接下来n行，每行一个整数，第i行的整数wi表示节点i的权值。</span>
</p>
<p>
<span style="font-size:medium;">接下来1行，为一个整数q，表示操作的总数。</span>
</p>
<p>
<span style="font-size:medium;">接下来q行，每行一个操作，以“CHANGE u t”或者“QMAX u v”或者“QSUM u v”的形式给出。 </span>
</p>
<p>
<span style="font-size:medium;">对于100％的数据，保证1&lt;=n&lt;=30000，0&lt;=q&lt;=200000；中途操作中保证每个节点的权值w在-30000到30000之间。</span> 
</p>
<p></p>
<h3>
【输出格式】
</h3>
<div class="content">
<p>
<span style="font-size:medium;">对于每个“QMAX”或者“QSUM”的操作，每行输出一个整数表示要求输出的结果。</span> 
</p>
</div>
<h3>
【样例输入】
</h3>
<pre>4
1 2
2 3
4 1
4 2 1 3
12
QMAX 3 4
QMAX 3 3
QMAX 3 2
QMAX 2 3
QSUM 3 4
QSUM 2 1
CHANGE 1 5
QMAX 3 4
CHANGE 3 6
QMAX 3 4
QMAX 2 4
QSUM 3 4
  </pre>
<h3>
【样例输出】
</h3>
<pre>4
1
2
2
10
6
5
6
5
16
</pre>
<h3>
【提示】
</h3>
<div class="content">
</div>
<h3>
【来源】
</h3>
<h3>
【题目来源】
</h3>
<a href="http://www.lydsy.com/JudgeOnline/problem.php?id=1036">耒阳大世界（衡阳八中） OJ 1036</a>
