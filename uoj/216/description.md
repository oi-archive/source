# 题目描述

<p>印尼首都雅加达市有 $10^{18}$ 座摩天楼，它们排列成一条直线，我们从左到右依次将它们编号为 $1$ 到 $10^{18}$ 。除了这 $10^{18}$ 座摩天楼外，雅加达市没有其他摩天楼。</p>
<p>有 $10^{18}$ 只叫做 “doge” 的神秘生物在雅加达市居住，它们的编号依次是 $1$ 到 $10^{18}$。编号为 $i$ 的 doge 居住于编号为 $i$ 的摩天楼。每只 doge 都有一种神秘的力量，使它们能够不用跳跃就可以在摩天楼之间传递消息，如果编号为 $i$ 的 doge 和一个编号比他小的编号为 $j$ 的 doge 都知道了一个消息，它们可以使用神秘力量将消息传递给编号为 $i-j$ 的doge。</p>
<p>qmqmqm想知道它们是否掌握了这种力量。他将一条消息告诉了编号为 $a$ 的doge，又告诉了编号为 $b$ 的doge（$a$ 可能和 $b$ 相等），让它们尽快传送给编号为 $c$ 的 doge。</p>
<p>请帮助 doge 们计算是否有方法使用不超过 $400$ 次力量将消息传递到 $c$ 号 doge ，或者告诉它们消息不可能在次数限制内传递到 $c$ 号 doge。</p>

# 输入格式


<p>输入包含一行三个正整数 $a,b,c$ 。</p>

# 输出格式


<p>如果不可能在次数限制内传递，输出一行一个整数 $-1$。</p>
<p>否则，第一行输出你进行操作的次数 $K$。之后 $K$ 行每行两个正整数表示你这次操作选择的 $i$ 和 $j$。</p>

# 样例一


<h4>input</h4>
<pre>19 12 14

</pre>

<h4>output</h4>
<pre>3
19 12
12 7
19 5

</pre>

<h4>explanation</h4>
<p>第一次操作前，知道消息的doge集合为 $\{19,12\}$。</p>
<p>第一次操作后，知道消息的doge集合为 $\{19,12,7\}$。</p>
<p>第二次操作后，知道消息的doge集合为 $\{19,12,7,5\}$。</p>
<p>第三次操作后，知道消息的doge集合为 $\{19,14,12,7,5\}$。此时符合条件了。</p>

# 样例二


<h4>input</h4>
<pre>233 1 233

</pre>

<h4>output</h4>
<pre>0

</pre>

<h4>explanation</h4>
<p>不需进行任何操作，就能使编号 $233$ 的doge知道消息。</p>

# 样例三


<h4>input</h4>
<pre>4 2 1

</pre>

<h4>output</h4>
<pre>-1

</pre>

<h4>explanation</h4>
<p>最初唯一的操作是选择 $i=4,j=2$,但这样会把消息传给编号为 $2$ 的doge，而它已经知道这个消息了，所以知道消息的doge集合没有变化，无法把消息告诉编号为 $1$ 的doge。</p>

# 限制与约定


<p>由于一些原因，本题使用捆绑测试。每个子任务有若干个测试点，分为 $5$ 个子任务，你只有通过一个子任务的所有测试点才能得到这个子任务的分数。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>限制</th>
</tr></thead><tbody><tr><td>1</td><td>10</td><td>$a,b,c \leq 400$</td></tr><tr><td>2</td><td>20</td><td>$b=1$ 且 $a,c\leq 10^{18}$</td></tr><tr><td>3</td><td>20</td><td>$c=1$ 且 $a,b\leq 10^{18}$</td></tr><tr><td>4</td><td>20</td><td>$a,b,c \leq 10^9$</td></tr><tr><td>5</td><td>30</td><td>$a,b,c \leq 10^{18}$</td></tr></tbody></table></div>


<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=216">样例数据下载</a></p>
