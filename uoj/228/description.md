# 题目描述

<p>sylvia 是一个热爱学习的女孩子，今天她想要学习数据结构技巧。</p>
<p>在看了一些博客学了一些姿势后，她想要找一些数据结构题来练练手。于是她的好朋友九条可怜酱给她出了一道题。</p>
<p>给出一个长度为 $n$ 的数列 $A$，接下来有 $m$ 次操作，操作有三种：</p>
<ol><li>对于所有的 $i \in [l,r]$，将 $A_i$ 变成 $A_i+x$。</li>
<li>对于所有的 $i \in [l,r]$，将 $A_i$ 变成 $\lfloor \sqrt {A_i} \rfloor$。</li>
<li>对于所有的 $i \in [l,r]$，询问 $A_i$ 的和。</li>
</ol><p>作为一个不怎么熟练的初学者，sylvia 想了好久都没做出来。而可怜酱又外出旅游去了，一时间联系不上。于是她决定向你寻求帮助：你能帮她解决这个问题吗。</p>

# 输入格式


<p>第一行两个数：$ n, m $。</p>
<p>接下来一行 $ n $ 个数 $A_i$。</p>
<p>接下来 $ m $ 行中，第 $ i $ 行第一个数 $ t_i $ 表示操作类型：</p>
<p>若 $ t_i = 1 $，则接下来三个整数 $ l_i, r_i, x_i $，表示操作一。</p>
<p>若 $ t_i = 2 $，则接下来三个整数 $ l_i, r_i$，表示操作二。</p>
<p>若 $ t_i = 3 $，则接下来三个整数 $ l_i, r_i$，表示操作三。</p>

# 输出格式


<p>对于每个询问操作，输出一行表示答案。</p>

# 样例一


<h4>input</h4>
<pre>5 5
1 2 3 4 5
1 3 5 2
2 1 4
3 2 4
2 3 5
3 1 5

</pre>

<h4>output</h4>
<pre>5
6

</pre>


# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$ 的规模</th><th>$m$ 的规模</th><th>其他约定</th></tr></thead><tbody><tr><td>1</td><td rowspan="3">$n \leq 3000$</td><td rowspan="3">$m \leq 3000$</td><td rowspan="3"></td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="7">$n \leq 100000$</td><td rowspan="7">$m \leq 100000$</td><td rowspan="2">数据随机生成</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="2">$t_i \neq 1$</td></tr><tr><td>7</td></tr><tr><td>8</td><td rowspan="3"></td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有数据，保证有 $1 \leq l_i \leq r_i \leq n,1 \leq A_i,x_i \leq 10^5$</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=228">样例数据下载</a></p>
