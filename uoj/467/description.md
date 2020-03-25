# 题目描述

<p>九条可怜是一个喜欢数据结构的女孩子，在常见的数据结构中，可怜最喜欢的就是线段树。</p>
<p>线段树的核心是懒标记，下面是一个带懒标记的线段树的伪代码，其中 tag 数组为懒标记：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/467/segcode.webp" style="width:700px;" alt="伪代码"/></p>
<p>其中函数 Lson(Node) 表示 Node 的左儿子，Rson(Node) 表示 Node 的右儿子。</p>
<p>现在可怜手上有一棵 $[1,n]$ 上的线段树，编号为 $1$。这棵线段树上的所有节点的 tag 均为 $0$。接下来可怜进行了 $m$ 次操作，操作有两种：</p>
<ul><li>$1\ l\ r$，假设可怜当前手上有 $t$ 棵线段树，可怜会把每棵线段树复制两份（tag 数组也一起复制），原先编号为 $i$ 的线段树复制得到的两棵编号为 $2i-1$ 与 $2i$，在复制结束后，可怜手上一共有 $2t$ 棵线段树。接着，可怜会对所有编号为奇数的线段树进行一次 $\text{Modify}(\text{root},1,n,l, r)$。</li>
<li>$2$，可怜定义一棵线段树的权值为它上面有多少个节点 tag 为 $1$。可怜想要知道她手上所有线段树的权值和是多少。</li>
</ul>
# 输入格式


<p>第一行输入两个整数 $n,m$ 表示初始区间长度和操作个数。</p>
<p>接下来 $m$ 行每行描述一个操作，输入保证 $1 \leq l \leq r \leq n$。</p>

# 输出格式


<p>对于每次询问，输出一行一个整数表示答案，答案可能很大，对 $998244353$ 取模后输出即可。</p>

# 样例一


<h4>input</h4>
<pre>5 5
2
1 1 3
2
1 3 5
2
</pre>

<h4>output</h4>
<pre>0
1
6
</pre>

<h4>explanation</h4>
<p>$[1,5]$ 上的线段树如下图所示：</p>
<p><img class="img-responsive center-block" src="/source/uoj/467/img/aHR0cHM6Ly9pLmxvbGkubmV0LzIwMTkvMDQvMzAvNWNjODYwYWUxZjM2My5wbmc=.png" alt="5cc860ae1f363.png"/></p>
<p>在第一次询问时，可怜手上有一棵线段树，它所有点上都没有标记，因此答案为 $0$。</p>
<p>在第二次询问时，可怜手上有两棵线段树，按照编号，它们的标记情况为：</p>
<ul><li>点 $[1,3]$ 上有标记，权值为 $1$。</li>
<li>没有点有标记，权值为 $0$。</li>
</ul><p>因此答案为 $1$。</p>
<p>在第三次询问时，可怜手上有四棵线段树，按照编号，它们的标记情况为：</p>
<ul><li>点 $[1,2],[3,3],[4,5]$ 上有标记，权值为 $3$。</li>
<li>点 $[1,3]$ 上有标记，权值为 $1$。</li>
<li>点 $[3,3],[4,5]$ 上有标记，权值为 $2$。</li>
<li>没有点有标记，权值为 $0$。</li>
</ul><p>因此答案为 $6$。</p>

# 样例二至样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点</th>
    <th>$n$</th>
    <th>$m$</th>
    <th>其他约定</th>
  </tr></thead><tbody><tr><td>1</td>
    <td rowspan="4">$\leq 1000$</td>
    <td rowspan="2">$\leq 10$</td>
    <td rowspan="4">无</td>
  </tr><tr><td>2</td>
  </tr><tr><td>3</td>
    <td rowspan="2">$\leq 1000$</td>
  </tr><tr><td>4</td>
  </tr><tr><td>5</td>
    <td rowspan="6">$\leq 10^5$</td>
    <td rowspan="6">$\leq 10^5$</td>
    <td rowspan="3">询问只有一个</td>
  </tr><tr><td>6</td>
  </tr><tr><td>7</td>
  </tr><tr><td>8</td>
    <td rowspan="3">无</td>
  </tr><tr><td>9</td>
  </tr><tr><td>10</td>
  </tr></tbody></table></div>

<p>对于 $100\%$ 的数据，$1 \leq l \leq r \leq n$。</p>
<p><strong>时间限制</strong>：$3\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=467">样例数据下载</a></p>
