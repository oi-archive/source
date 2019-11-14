# 题目描述

<p>成为鸽王的三个要求之一，出色的咕咕咕能力。</p>
<p>为了比拼咕咕咕能力，主持人交给了码农同学$n$个待办事项，最初第$i$个待办事项还剩下$a_i$天的待办时间。</p>
<p>接下来码农同学和主持人会进行$9^{9^9}$轮交互，每一轮交互如下：</p>
<p>首先，码农同学可以找到不超过$A$个借口，并将这些借口任意分配给各个待办事项，每个借口都可以使某一个的待办事项增加$1$天的待办时间。</p>
<p>然后，主持人会选择$B$个待办事项，要求码农同学立即完成这些待办事项，将这些待办事项的待办时间清零。当然，这些待办事项的待办时间依然可以在后续轮次的交互中被增加。</p>
<p>在$9^{9^9}$轮交互全部完成之后，码农同学发现在整个交互过程中，在他某一次找借口后，某一个待办事项的待办时间达到了历史最大值$M$天，他可以借这个数值$M$来吹嘘自己的咕咕咕能力。</p>
<p>码农同学自然希望数值$M$尽量大，而主持人的目的则是让数值$M$尽量小。</p>
<p>观看大赛的观众们想要请你预测，假如码农同学和主持人一直使用最优策略，最终的数值$M$会是多少。</p>

# 输入格式


<p>输入的第一行包括三个整数 $ n, A, B $ 。</p>
<p>接下来一行包括 $ n $ 个非负整数，表示序列 $ a $ ，即每个待办事项的初始待办天数。</p>

# 输出格式


<p>输出共包括一行，表示答案。</p>

# 样例一


<h4>input</h4>
<pre><code>3 5 1
1 2 3</code></pre>
<h4>output</h4>
<pre><code>11</code></pre>
<h4>explanation</h4>
<p>一种交互过程如下：</p>
<p>$ \{1, 2, 3\} \rightarrow \{3, 4, 4\}\rightarrow \{3, 4, 0\}\rightarrow \{6, 6, 0\} \rightarrow \{6, 0, 0\} \rightarrow \{11, 0, 0\} $</p>

# 样例二


<h4>input</h4>
<pre><code>5 5 1
0 2 1 0 3</code></pre>
<h4>output</h4>
<pre><code>14</code></pre>

# 样例三


<h4>input</h4>
<pre><code>5 100 5
1 2 3 4 5</code></pre>
<h4>output</h4>
<pre><code>105</code></pre>

# 样例四


<h4>input</h4>
<pre><code>19 23333 7
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0</code></pre>
<h4>output</h4>
<pre><code>30471</code></pre>

# 样例五


<h4>input</h4>
<pre><code>10 1 1
100 90 80 70 60 50 40 30 20 10</code></pre>
<h4>output</h4>
<pre><code>101</code></pre>

# 样例六


<h4>input</h4>
<pre><code>8 3 1
5 1 2 2 0 2 5 1</code></pre>
<h4>output</h4>
<pre><code>9</code></pre>

# 限制与约定


<p>对于 $ 100 \% $ 的数据，$ 1 \le B \le n \le 10^5, 0 \le a_i, A \le 10^{12} $ 。 下表是更详细的数据范围，表中留空代表无特殊限制。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>子任务编号</th><th>$n$</th><th>$A$</th><th>$B$</th><th>$a_i$</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$\le 10$</td><td>$=1$</td><td>$=1$</td><td>$\le 1$</td><td>$17$</td></tr><tr><td>$2$</td><td>$\le 100$</td><td>$\le 100$</td><td></td><td>$\le 100$</td><td>$16$</td></tr><tr><td>$3$</td><td>$\le 2000$</td><td></td><td></td><td>$=0$</td><td>$11$</td></tr><tr><td>$4$</td><td>$\le 2000$</td><td></td><td></td><td></td><td>$27$</td></tr><tr><td>$5$</td><td></td><td></td><td></td><td></td><td>$29$</td></tr></tbody></table></div>

<p><strong>时间限制: $ 2 $s </strong></p>
<p><strong>空间限制: $ 512 $MB </strong></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=484">样例数据下载</a></p>
