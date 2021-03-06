# 题目描述


<h3>
【题目描述】
</h3>
<p>
这有一棵带根的树有 N 个节点标号从 0 到 N-1。根标号为 0。每条边连接两个节点，并且有权重。你的工作是找到 $S$，一个顶点集合$\{s_1,s_2,\cdots,s_m\} (0\le m &lt; N)$，满足以下条件：
</p>
<p>
   （1）根不在 $S$ 中，这就意味着：$0&lt;s_i&lt;N (1\le i \le m)$；
</p>
<p>
   （2）$s_i$ 和 $s_j$ 只有一个公共祖先，这就意味着：除根外他们没有公共祖先。
</p>
<p>
   （3）这里有两个联系在 $W=\{w_1,w_2,\cdots,w_m\} $ 和 $D=\{d_1,d_2,\cdots,d_m\}$ ，$w_i$ 是从根到 $s_i$ 的路径权重总和。$d_i$ 是从根到 $s_i$ 的边数总和。这个 $ S = \sum w_i / \sum d_i (1\le i \le m) $ 的平均结果是最大的。
</p>
<h3>
【输入格式】
</h3>
<p>
输入第一行有一个整数 T 表示测试数据个数。每组数据以整数 n 开始 (1≤n≤1000)，树的节点个数。下面 N-1 行每行包括 3 个整数 i, j, k ，表示这是一个有向边从 i 到 j 权重为 k。
</p>
<h3>
【输出格式】
</h3>
<p>
每组数据输出一个实数，S 的最大平均数。
</p>
<h3>
【样例输入】
</h3>
<pre>3
1
2
0 1 2
3
0 1 1
0 2 2
</pre>
<h3>
【样例输出】
</h3>
<pre>0.00
2.00
2.00
</pre>
<h3>
【评测方式】
</h3>
<p>
评测插件判断该答案与标准答案差距不超过 0.01 即可算做正确。每答对一个询问得到 1/T 的分数。
</p>
