# 题目描述

<p>在 NOIP2044 的赛场上，小 D 遇到了这样一道题：</p>
<p>给出一个 $n$ 个点的图，其中有 $m$ 条带边权的有向边，有 $q$ 个询问，每个询问形如从 $u$ 号点走到 $v$ 号点，长度为 $w$ 的道路数量有多少？你只需要输出答案对 $P$ 取模的结果即可。</p>
<p>小 D 思考了良久也不会做这道题，悻悻离场后，他从官网上取得了这道题的数据，共有 $10$ 组数据。小 D 怎么也想做出来这道题，于是他开始寻求你的帮助，将 $10$ 组数据的输入给了你。聪明的你一定可以帮小 D 计算出每组数据的输出的！</p>

# 输入格式


<p>输入文件 noip1.in~noip10.in 已经在下载文件中。</p>
<p>每个输入文件的第一行包括 $4$ 个正整数 $n,m,q,P$，表示图中点数、边数、询问数目以及模数。点的编号为从 $1$ 到 $n$ 的整数。</p>
<p>接下来 $m$ 行每行描述 $m$ 条带权有向边，其中第 $i$ 行包含 $3$ 个整数 $a_i,b_i,c_i$，表示第 $i$ 条边的起点为 $a_i$，终点为 $b_i$，权值为 $c_i$。</p>
<p>接下来 $q$ 行描述询问，其中第 $k$ 行包含 $3$ 个整数 $u_k,v_k,w_k$，表示第 $k$ 个询问需要输出从 $u_k$ 号店走到 $v_k$ 号点，长度为 $w_k$ 的道路数量对 $P$ 取模的结果。</p>

# 输出格式


<p>输出文件为 noip1.out~noip10.out，分别对应相应的输入文件。</p>
<p>每个输出文件中不超过 $q$ 行，每行包含一个小于 $P$ 的非负整数，表示该测试点前 $q$ 个询问的答案。</p>

# 样例一


<h4>input</h4>
<pre>3 4 2 10
1 1 2
1 3 1
2 3 3
1 3 5
1 3 3

</pre>

<h4>output</h4>
<pre>2
1

</pre>

<h4>explanation</h4>
<p>对于第一组询问，一共有两条从 $1$ 号点到 $3$ 号点、长度为 $5$ 的路径。假定边的编号从 $1$ 到 $4$，则这两条路径经过的边为：</p>
<p>第 $1$ 条：$2 \rightarrow 4$</p>
<p>第 $2$ 条：$1 \rightarrow 1 \rightarrow 3$。</p>

# 更多样例


<p>我们给出了 noip1.sampleout~noip10.sampleout，分别对应每一个测试点第一个询问的正确输出。</p>

# 子任务及部分分


<p>每个测试点单独评分。每个测试点你还可能获得部分分。</p>
<p>最终评测时，我们将根据你在每个数据中回答正确的询问个数进行积分。</p>
<p>如果你的输出不超过 $q$ 行，且每行只包含一个不超过 $P$ 的非负整数，在最终评测时我们将认为你在第 $i$ 行的输出是在回答对应测试点的第 $i$ 个询问。</p>
<p>对于每个测试点，我们设置了 $10$ 个评分参数 $a_1,a_2,...,a_{10}$。在你的方案中，若正确回答的询问个数为 $w_{\mathrm{user}}$，你的分数将会由下表给出（若符合表中多个条件，取分数最高的）：</p>
<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>得分</th><th>条件</th><th>得分</th><th>条件</th></tr></thead><tbody><tr><td>$10$</td><td>$w_{\mathrm{user}} \geq a_{10}$</td><td>$5$</td><td>$w_{\mathrm{user}} \geq a_{5}$</td></tr><tr><td>$9$</td><td>$w_{\mathrm{user}} \geq a_{9}$</td><td>$4$</td><td>$w_{\mathrm{user}} \geq a_{4}$</td></tr><tr><td>$8$</td><td>$w_{\mathrm{user}} \geq a_{8}$</td><td>$3$</td><td>$w_{\mathrm{user}} \geq a_{3}$</td></tr><tr><td>$7$</td><td>$w_{\mathrm{user}} \geq a_{7}$</td><td>$2$</td><td>$w_{\mathrm{user}} \geq a_{2}$</td></tr><tr><td>$6$</td><td>$w_{\mathrm{user}} \geq a_{6}$</td><td>$1$</td><td>$w_{\mathrm{user}} \geq a_{1}$</td></tr></tbody></table></div>

<p>如果你的输出不符合格式要求，例如出现不小于 $P$ 的整数或负数，输出超过了 $q$ 行等，我们将不保证你能得到分数。</p>
<p>评分参数文件 noip.score 已在试题目录下。该文件共 $10$ 行，第 $i$ 行描述测试点 $i$ 的评分参数。每行包含 $10$ 个整数，依次表示 $a_1,a_2,...,a_{10}$。</p>

# 提示


<p>本题可能用到的知识：</p>
<p><strong>特征多项式</strong>：对于 $n \times n$ 的矩阵 $A$，定义以 $\lambda$ 为变量的 $n$ 次多项式 $f(\lambda)=\det(\lambda I-A)$，其中 $I$ 是 $n$ 阶单位矩阵，$\det$ 是行列式。称 $f(\lambda)$ 为 $A$ 的特征多项式。</p>
<p><strong>Cayley-Hamilton 定理</strong>：对于方阵 $A$ 的特征多项式 $f(\lambda)$，一定有 $f(A)=0$。即将矩阵本身作为变量带入特征多项式，结果为零矩阵。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=200">选手文件下载</a></p>
