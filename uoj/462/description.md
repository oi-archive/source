# 题目描述

<p>在DoubleDog成功辨别出来种族之后，旁边出现了一群小黄鸭和一只<span class="uoj-username" data-rating="1740">wangyisong1996</span>。</p>
<p><span class="uoj-username" data-rating="1740">wangyisong1996</span>拦住了这些DoubleDog，说他可以给他们以帮助，但是他们需要先做出来一道题。</p>
<p><span class="uoj-username" data-rating="1740">wangyisong1996</span>有一颗$n$个节点的有根树，根节点为$1​$，他想在这颗树上跑树链剖分。</p>
<p>他已经实现了除了树链剖分以外的其他所有东西，现在他想要知道最优的一种树链剖分方案。</p>
<p>树链剖分的时间复杂度如下：</p>
<p>定义树上的一个树链剖分为一种将边集划分为重边和轻边的方法使得每个节点和他的儿子之间最多只有一条重边。</p>
<p>在下面的表示中，我们将重边称为$0$边，轻边称为$1$边。</p>
<p>定义树上的$(x,y)​$序列为从$x​$到$y​$依次经过的每一条边的类型拼接而成的一个$01​$串$(x!=y)$</p>
<p>对于一个长度为$l​$的全$1​$串,我们设$f(x)=l​$</p>
<p>对于一个长度为$l​$的全$0​$串,我们设$f(x)=\left\lceil\log_2l\right\rceil+1​$</p>
<p>对于一个01串，我们有$f(x)=\sum f(每一个极大连续全0/1子串)​$</p>
<p>例如:$f(&#39;0011101&#39;)=(1+1)+3+(0+1)+1=7$</p>
<p>对于一个轻重边划分方案$T$，我们有$O(T)=\sum^{n}_{i=2}f((1,i))$</p>
<p>现在<span class="uoj-username" data-rating="1740">wangyisong1996</span>想要知道所有可行的树链剖分方案中，时间复杂度(也就是O(方案))最小的值是多少</p>

# 输入格式


<p>第一行一个正整数$n$，表示有根树的节点数。</p>
<p>接下来$n-1$行，每一行两个数字$x,y$,表示树上的一条连接$x,y$的边。</p>

# 输出格式


<p>一行一个数字，表示答案。</p>

# 样例一


<h4>input</h4>
<pre>7
1 2
2 3
2 4
2 5
2 6
2 7
</pre>

<h4>output</h4>
<pre><code class="sh_txt">11</code></pre>
<h4>explanation</h4>
<p>将边$(1,2),(2,3)$设为重边：</p>
<p>此时$f(2)=1,f(3)=f(4)=f(5)=f(6)=f(7)=2$，可以证明这是最优解。</p>

# 样例二至样例四


<p>见样例数据下载。</p>

# 限制与约定


<p><strong>Subtask 1 (5 分):</strong> $n\le 20$,内存限制$\texttt{1GB}$</p>
<p><strong>Subtask 2 (15 分):</strong> $n\le 200$,内存限制$\texttt{1GB}$</p>
<p><strong>Subtask 3 (15 分):</strong> $n\le 5000$,内存限制$\texttt{1GB}$</p>
<p><strong>Subtask 4 (30 分):</strong> $n\le 100000$,内存限制$\texttt{1GB}$</p>
<p><strong>Subtask 5 (35 分):</strong> $n\le 100000$,内存限制$\texttt{200MB}$</p>
<p><strong>时间限制</strong>：$\texttt{3s}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=462">样例数据下载</a></p>
