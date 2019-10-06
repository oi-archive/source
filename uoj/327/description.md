# 题目描述

<p>Scape和Mythological交流了玩几何冲刺的经验之后，Mythological非常高兴，又推荐给Scape一款游戏To the moon。</p>
<p>游戏中一位老人John的记忆被药物尘封，进行了解除尘封的仪式之后，Scape走入了他的记忆。</p>
<p>John的记忆中有一个唤做River女孩的身影，有着数不尽的纸兔子，有一个沙包，一只鸭嘴兽玩偶，一座灯塔。Scape被深深的打动了。</p>
<p>”我的鸭嘴兽和沙包又在哪里呢？” Scape这样想到，不禁幻想出Mythological决定给他送 $n$ 份礼物，其中第 $i$ 份的种类是 $a_i$。这些礼物按顺序排成一行。</p>
<p>她挑选礼物的方式很特别，她每次会选择两份<strong>种类相同</strong>的礼物，并且这对礼物满足它们之间没有<strong>尚未拿走</strong>的礼物，并将这对礼物拿走。</p>
<p>现在Scape给出了若干次询问，每次询问如果他送给她的是区间 $\left [L_i,R_i\right ]$ 之间的礼物，那么她最多能拿走多少份礼物。</p>

# 任务


<p>你需要编写两个函数/过程，以完成题目的任务：</p>
<ul><li>init(n, m, a[], t);<ul><li>在程序最开始运行时会调用一次来完成初始化。</li>
<li>$n$ 表示 $a$ 的长度是 $n$，$m$ 表示 $a_i$ 的最大可能值，$a$ 数组的下标从 $1$ 开始，$t$ 表示子任务编号。</li>
</ul></li>
<li>query(l, r);<ul><li>表示询问区间 $\left [L ,R\right ]$ 的答案 。</li>
<li>保证 $L\leq R$。</li>
</ul></li>
</ul>
# 实现细节


<p>本题只支持 C/C++。</p>
<p>你只能提交一个源文件实现如上所述的 init 和 query 函数/过程，并且遵循下面的命名和接口。你需要包含头文件 mythological.h。</p>
<pre><code class="sh_cpp">void init(int n, int m, int a[], int t);
int query(int l, int r);</code></pre>
<p>如果有不清楚的地方，见样例及测评库下载，<strong>内附了样例程序</strong>。</p>
<p>评测库大概需要占用$8\texttt{MB}$的内存和$100\texttt{ms}$的时间。</p>
<p>因为评测库使用了fread来进行快速读入，所以用命令行输入数据的选手需要在输入数据完毕后用&#34;<samp>Ctrl+D<samp>&#34;来输入EOF。</samp></samp></p>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ol><li>第 $1$ 行：四个整数 $n,m,q,t$，分别是这组测试数据的大小，$a_i$ 的最大可能值，询问个数和子任务编号。</li>
<li>第 $2$ 行：$n$ 个整数，第 $i$ 个整数表示 $a_i$。</li>
<li>第 $2+i$ 行（$1\le i\le q$）：两个整数 $L_i,R_i$，表示询问的区间。</li>
</ol>
# 样例一


<h4>input</h4>
<pre>9 10 3 0
1 1 3 2 1 1 2 3 1
2 9
1 2
2 5

</pre>

<h4>output</h4>
<pre>8
2
0

</pre>


# 样例二


<h4>input</h4>
<pre>10 10 3 0
1 2 3 4 5 6 7 8 9 10
1 9
2 3
4 5

</pre>

<h4>output</h4>
<pre>0
0
0

</pre>



# 样例三


<p>见样例及测评库下载。</p>

# 限制与约定


<p>对于所有数据，$1\le n\le 1\times 10^5$，$1\le m\le 1\times10^5$，$ q\leq 2\times 10^6$，$ L_i \le  R_i$。</p>
<p>为了拿到每个子任务的分数，你必须通过<strong>所有</strong>他依赖的子任务。</p>
<div class="table-responsive">
 <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
    <th>分值</th>
    <th>$n$</th>
    <th>$q$</th>
    <th>其他性质</th>
    <th>依赖的subtask</th>
   </tr></thead><tbody><tr><td>1</td>
    <td>20</td>
    <td>$\le 1000$</td>
    <td>$\le 1000$</td>
    <td>无</td>
    <td>无</td>
   </tr><tr><td>2</td>
    <td>16</td>
    <td>$\le 1\times 10^5$</td>
    <td>$\le 1\times 10^5$</td>
    <td>每种权值最多出现两次</td>
    <td>$1$</td>
   </tr><tr><td>3</td>
    <td>25</td>
    <td>$\le 1\times 10^5$</td>
    <td>$\le 1\times 10^5$</td>
    <td>询问的 $L,R$ 生成方式给出（见下）</td>
    <td>$1$</td>
   </tr><tr><td>4</td>
    <td>19</td>
    <td>$\le 1\times 10^5$</td>
    <td>$\le 1\times 10^5$</td>
    <td>无</td>
    <td>$1,2,3$</td>
   </tr><tr><td>5</td>
    <td>20</td>
    <td>$\le 1\times 10^5$</td>
    <td>$\le 2\times 10^6$</td>
    <td>无</td>
    <td>$1,2,3,4$</td>
   </tr></tbody></table></div>



<p>子任务3生成询问的方式如下：</p>
<p>定义
$$F_i=(2000i^2+629i+2333) \bmod n+1$$</p>
<p>则对所有的 $1\le i\le q$，有
$$L_i = \min\left\{F_{2i-1},F_{2i} \right\}$$
$$R_i = \max\left\{F_{2i-1},F_{2i} \right\}$$</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=327">样例数据下载</a></p>
