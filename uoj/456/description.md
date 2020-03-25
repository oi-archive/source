# 题目描述

<p>圣诞节就要到了，小C想买一棵圣诞树。自然，请客请到破产的小C买不起圣诞树，所以，小C计划把过年用的许愿树改造成圣诞树。</p>
<p>许愿树是一棵 $n$ 个节点的<a href="//baike.baidu.com/item/%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91/7077855">二叉搜索树</a>，$n$ 个节点的权值为 $1$ 到 $n$ 的排列。</p>
<p>我们定义一次单旋为：</p>
<p>假设 $x$ 是其父亲 $p$ 的左孩子。我们对它做下图操作，则称为一次单旋。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/456/danxuan.png" alt="单旋例图"/></p>
<p>如果是右孩子，就做其轴对称操作。</p>
<p>圣诞树支持如下三个操作：</p>
<ol><li>点 $x$ 连续不断单旋向上，直至它成为点 $y$ 的儿子，<strong>保证 $y$ 是 $x$ 的祖先</strong></li>
<li>询问点 $x$ 的第 $k$ 级祖先，<strong>保证此时点 $x$ 的第 $k$ 级祖先存在</strong></li>
<li>询问整棵树<a href="//baike.baidu.com/item/%E5%85%88%E5%BA%8F%E9%81%8D%E5%8E%86/6442839">先序遍历</a>中的第 $k$ 个点，<strong>保证此时$1\le k \le n$。</strong></li>
</ol><p>许愿树不支持这些操作，现在小C希望你能帮助他加上这些功能。</p>

# 输入格式


<p>第一行一个正整数 $n$ 表示许愿树的节点数。</p>
<p>第二行 $n$ 个正整数，记第 $i$ 个整数 $f_i$ 表示权值为 $i$ 的节点的父亲。</p>
<p>如果 $f_i=0$，表示该节点是根。
你可以通过 $i$ 与 $f_i$ 的相对大小来确定该节点是其父亲的左孩子还是右孩子。
保证所形成树结构是一棵二叉搜索树。</p>
<p>第三行一个正整数 $m$ 表示操作次数。</p>
<p>接下来 $m$ 行，每行先输入一个整数 $opt$，保证 $1 \le opt \le 3$ 。</p>
<p>如果 $opt=1$ ，则之后还跟着两个正整数 $x,y$ ，表示将点 $x$ 连续不断单旋向上，直至它成为点 $y$ 的儿子。</p>
<p>如果 $opt=2$ ，则之后还跟着两个正整数 $x,k$ ，表示询问询问点 $x$ 的第 $k$ 级祖先。</p>
<p>如果 $opt=3$ ，表示询问整棵树先序遍历中的第 $k$ 个点。</p>

# 输出格式


<p>输出若干行，每行一个整数表示询问的答案。</p>

# 样例一


<h4>input</h4>
<pre>10
2 3 5 3 9 8 6 5 0 9 
10
3 9
1 1 2
2 1 4
1 4 5
1 4 5
2 1 3
1 2 4
2 8 1
2 10 1
2 8 2

</pre>

<h4>output</h4>
<pre>7
9
4
5
9
9

</pre>


# 样例二至样例六


<p>见样例数据下载。</p>

# 限制与约定


<p>本题采用捆绑测试，对于每个子任务，只有通过其中全部数据才可以获得分数。
对于全部数据，$1 \le n,m \le 100000$，$0 \le f_i \le n$</p>
<p>特殊性质 0：保证数据随机。</p>
<p>特殊性质 1：保证所有修改都在询问之前。</p>
<p>特殊性质 2：保证每次一操作中的点 $y$ 都是整棵树的根。</p>
<p>特殊性质 3：保证没有三操作</p>
<p>特殊性质 4：保证所有二操作中$k = 1$。</p>
<p>特殊性质 5：保证没有二操作</p>
 <div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>测试点编号</th><th>$n\le$</th><th>特殊性质</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$1000$</td><td>$0$</td><td>$7$</td></tr><tr><td>$2$</td><td>$100000$</td><td>$0$</td><td>$9$</td></tr><tr><td>$3$</td><td>$100000$</td><td>$1,2,3,4$</td><td>$27$</td></tr><tr><td>$4$</td><td>$100000$</td><td>$2,3,4$</td><td>$16$</td></tr><tr><td>$5$</td><td>$100000$</td><td>$3$</td><td>$23$</td></tr><tr><td>$6$</td><td>$100000$</td><td>$5$</td><td>$10$</td></tr><tr><td>$7$</td><td>$100000$</td><td>无</td><td>$8$</td></tr></tbody></table></div>

<p><strong>时间限制</strong>：$\texttt{1s}$</p>
<p><strong>空间限制</strong>：$\texttt{512MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=456">样例数据下载</a></p>
