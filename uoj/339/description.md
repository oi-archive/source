# 题目描述


# 题目背景


<p>小Y是一个心灵手巧的OIer，她有许多二叉树模型。</p>
<p>小Y的二叉树模型中，每个结点都具有一个编号，小Y把她最喜欢的一个二叉树模型挂在了墙上，树根在最上面，左右子树分别在树根的左下方与右下方，且他们也都满足这样的悬挂规则。为了让这个模型更加美观，小Y选择了一种让这棵二叉树的中序遍历序列最小的悬挂方法。所谓中序遍历最小，就是指中序遍历的结点编号序列的字典序最小。</p>
<p>一天，这个模型不小心被掉在了地上，幸运的是，所有结点和边都没摔坏，但是她想不起这个模型原来是怎么悬挂的了，也就是说：她想不起来树根节点的编号了。</p>
<p>小Y最近忙于准备清华集训，所以没太多时间处理别的事情，她只好找到同样心灵手巧的你帮忙复原她的二叉树模型。</p>

# 题目描述


<p>给定小Y的二叉树模型，结点的编号为 $1$ ~ $n$ ，你需要给出其可能的最小的中序遍历，方便小Y更快的摆好她的模型。</p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>第一行为一个正整数 $n$ ，表示点的个数。</p>
<p>后接 $n$ 行，每行若干个整数：</p>
<p>第 $i+1$ 行的第一个整数为 $k_i$ ，表示编号为 $i$ 的结点的度数，后接 $k_i$ 个整数 $a_{i,j}$ ，表示编号为 $i$ 的结点与编号为 $a_{i,j}$ 的结点之间有一条边。</p>
<p>同一行输入的相邻两个元素之间，用恰好一个空格隔开。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>输出共一行， $n$ 个整数，表示字典序最小的中序遍历。</p>

# 样例一


<h4>input</h4>
<pre><code class="sh_plain">4
3 2 3 4
1 1
1 1
1 1</code></pre>
<h4>output</h4>
<pre><code class="sh_plain">2 1 3 4</code></pre>
<h4>explanation</h4>
<p>样例的一组最优解如下：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/339/339-optimal.webp" style="width:120px;" alt="最优解"/></p>
<p>其中结点$4$为根，结点$1$为结点$4$的左儿子，结点$2,3$分别为结点$1$的左右儿子。</p>

# 限制与约定


<p>本题共20个测试点，每个测试点5分。各个测试点的数据范围如下：</p>
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">测试点编号</th><th rowspan="1">$n \le$</th><th rowspan="1">$k_i$</th><th rowspan="1">特殊条件</th></tr></thead><tbody><tr><td rowspan="1">1</td><td rowspan="1">5</td><td rowspan="8">1,2,3</td><td rowspan="8">无</td></tr><tr><td rowspan="1">2</td><td rowspan="1">10</td></tr><tr><td rowspan="1">3</td><td rowspan="1">15</td></tr><tr><td rowspan="1">4</td><td rowspan="1">20</td></tr><tr><td rowspan="1">5</td><td rowspan="1">100</td></tr><tr><td rowspan="1">6</td><td rowspan="1">1000</td></tr><tr><td rowspan="1">7</td><td rowspan="1">2000</td></tr><tr><td rowspan="1">8</td><td rowspan="1">5000</td></tr><tr><td rowspan="1">9</td><td rowspan="1">1000000</td><td rowspan="4">1,2</td><td rowspan="1">结点$i$与结点$i-1$相连</td></tr><tr><td rowspan="1">10</td><td rowspan="1">100000</td><td rowspan="3">无</td></tr><tr><td rowspan="1">11</td><td rowspan="1">300000</td></tr><tr><td rowspan="1">12</td><td rowspan="1">1000000</td></tr><tr><td rowspan="1">13</td><td rowspan="1">100000</td><td rowspan="2">1,3</td><td rowspan="1">保证数据随机</td></tr><tr><td rowspan="1">14</td><td rowspan="1">1000000</td><td rowspan="1">无</td></tr><tr><td rowspan="1">15</td><td rowspan="1">20000</td><td rowspan="6">1,2,3</td><td rowspan="2">保证数据随机</td></tr><tr><td rowspan="1">16</td><td rowspan="1">200000</td></tr><tr><td rowspan="1">17</td><td rowspan="1">100000</td><td rowspan="4">无</td></tr><tr><td rowspan="1">18</td><td rowspan="1">500000</td></tr><tr><td rowspan="1">19</td><td rowspan="1">800000</td></tr><tr><td rowspan="1">20</td><td rowspan="1">1000000</td></tr></tbody></table><p>随机数据的生成方式如下：</p>
<p>对于第13个测试点，从一棵两个结点的树开始，每次随机一个树上的度数为1的结点（即叶结点），并生成两个与之直接相连的结点，直到这棵树上有 $n$ 个结点。显然，在这个测试点中，$n$ 是一个偶数。</p>
<p>对于第15和第16个测试点，从一棵一个结点的树开始，每次随机一个树上的度数不超过2的结点，并生成一个与之直接相连的结点，直到这棵树上有 $n$ 个结点。</p>

# 提示


<p>我们提供了一个只包含输入和输出功能的程序 binary_sample.cpp。</p>
<p>关于该程序的说明，见 readme.txt。</p>
<p>你可以在答题时使用该程序的代码，也可以不使用，这将与你的得分无关。</p>
<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=339">样例数据及附加文件下载</a></p>
