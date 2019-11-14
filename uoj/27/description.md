# 题目描述

<p>猫空缆车是台北市的一个著名景点。这个缆车系统包括一个环形轨道、一个缆车站和 $n$ 个编号为 $1$ 到 $n$ 的缆车。这些缆车以固定的方向在轨道上循环运行。在缆车 $i$ 经过缆车站之后，下一个经过缆车站的缆车将会是 $i + 1$ （$i &lt; n$ 时），或者是缆车 $1$（$i = n$ 时）。</p>
<p>缆车可能会发生故障。幸运的是，我们有无限多个后备的空闲缆车，其编号依次为 $n + 1, n + 2$ 等等。当某个缆车发生故障时，我们会在轨道上的同一位置用最前一个空闲缆车替换它，也就是说，编号最小的空闲缆车。举个例子，如果当前有五辆缆车而缆车 $1$ 发生了故障，那么我们将用缆车 $6$ 来替换它。</p>
<p>你喜欢去缆车站上观察缆车过站。一个缆车序列是由缆车过站次序形成的 $n$ 个缆车编号的序列。在你到达缆车站之前，有可能会有一到多个缆车发生故障（并且被替换掉），但是在你观察过程中是不会有缆车发生故障的。</p>
<p>注意，在轨道上的相同一组缆车，有可能给出多种缆车序列，这取决于当你到缆车站时哪辆缆车最先过站。举个例子，如果没有任何缆车发生故障，那么 $(2, 3, 4, 5, 1)$ 和 $(4, 5, 1, 2, 3)$ 都可能是缆车序列，但是 $(4, 3, 2, 5, 1)$ 不可能是（因为缆车的次序有误）。</p>
<p>如果缆车 $1$ 发生故障，那么我们可能会观察到缆车序列 $(4, 5, 6, 2, 3)$。如果接着缆车 $4$ 发生故障而我们用缆车 $7$ 替换它，就有可能会观察到缆车序列 $(6, 2, 3, 7, 5)$。如果缆车 $7$ 在此后发生故障而我们用缆车 $8$ 替换它，那么现在就有可能会观察到缆车序列 $(3, 8, 5, 6, 2)$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>故障缆车</th><th>新缆车</th><th>可能的缆车序列</th></tr></thead><tbody><tr><td>$1$</td><td>$6$</td><td>$(4, 5, 6, 2, 3)$</td></tr><tr><td>$4$</td><td>$7$</td><td>$(6, 2, 3, 7, 5)$</td></tr><tr><td>$7$</td><td>$8$</td><td>$(3, 8, 5, 6, 2)$</td></tr></tbody></table></div>

<p>一个替换序列是一个由故障缆车编号组成的序列，其次序与故障发生次序相同。在前面的例子中，替换序列是 $(1, 4, 7)$。如果一个替换序列 $r$ 对应的故障发生后，我们由此有可能观察到缆车序列 $g$，就称替换序列 $r$ 生成缆车序列 $g$。</p>

# 缆车序列检查


<p>在前三个子任务中，你必须检查某个输入序列是否是一个缆车序列。下表举例说明了哪些序列是缆车序列而哪些不是。你需要实现一个函数 valid。</p>
<ul><li>valid(n, inputSeq)<ul><li>$n$: 输入序列长度</li>
<li>inputSeq: 大小为 $n$ 的数组；inputSeq[i] 是输入序列的第 $i$ 个元素，其中 $0 \leq i \leq n - 1$。</li>
<li>当输入序列是一个缆车序列时，函数应返回 $1$，否则返回 $0$。</li>
</ul></li>
</ul>
# 子任务1, 2, 3


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th>$n$</th><th>inputSeq</th></tr></thead><tbody><tr><td>1</td><td>5</td><td>$n \leq 100$</td><td>从 $1$ 到 $n$ 数字恰好出现一次</td></tr><tr><td>2</td><td>5</td><td>$n \leq 100000$</td><td>$1 \leq \text{inputSeq[i]} \leq n$</td></tr><tr><td>3</td><td>10</td><td>$n \leq 100000$</td><td>$1 \leq \text{inputSeq[i]} \leq 250000$</td></tr></tbody></table></div>


# 例子


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>inputSeq</th><th>返回值</th><th>备注</th></tr></thead><tbody><tr><td>1</td><td>$(1, 2, 3, 4, 5, 6, 7)$</td><td>$1$</td><td></td></tr><tr><td>1</td><td>$(3, 4, 5, 6, 1, 2)$</td><td>$1$</td><td></td></tr><tr><td>1</td><td>$(1, 5, 3, 4, 2, 7, 6)$</td><td>$0$</td><td>$1$不能恰好出现在$5$之前</td></tr><tr><td>1</td><td>$(4, 3, 2, 1)$</td><td>$0$</td><td>$4$ 不能恰好出现在 $3$ 之前</td></tr><tr><td>2</td><td>$(1, 2, 3, 4, 5, 6, 5)$</td><td>$0$</td><td>有两个缆车编号都是 $5$</td></tr><tr><td>3</td><td>$(2, 3, 4, 9, 6, 7, 1)$</td><td>$1$</td><td>替换序列是 $(5, 8)$</td></tr><tr><td>3</td><td>$(10, 4, 3, 11, 12)$</td><td>$0$</td><td>$4$ 不能恰好出现在 $3$ 之前</td></tr></tbody></table></div>


# 替换序列


<p>在接下来的三个子任务中，你必须构造一个能够生成给定缆车序列的可能的替换序列。满足条件的任意替换序列都可以。你需要实现一个函数 replacement。</p>
<ul><li>replacement(n, gondolaSeq, replacementSeq)<ul><li>$n$ 是缆车序列的长度。</li>
<li>gondolaSeq: 大小为 $n$ 的数组；gondolaSeq 保证是一个缆车序列，而 gondolaSeq[i] 是序列中的第 $i$ 个元素，这里 $0 \leq i \leq n - 1$。</li>
<li>函数应返回替换序列的长度 $l$。</li>
<li>replacementSeq: 一个足够大的能存下替换序列的数组；你应当将替换序列中的第 $i$ 个元素存放到 replacementSeq[i] 做为返回结果，这里 $0 \leq i \leq l - 1$。</li>
</ul></li>
</ul>
# 子任务4, 5, 6


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th>$n$</th><th>gondolaSeq</th></tr></thead><tbody><tr><td>4</td><td>5</td><td>$n \leq 100$</td><td>$1 \leq \text{gondolaSeq[i]} \leq n + 1$</td></tr><tr><td>5</td><td>10</td><td>$n \leq 1000$</td><td>$1 \leq \text{gondolaSeq[i]} \leq 5000$</td></tr><tr><td>6</td><td>20</td><td>$n \leq 100000$</td><td>$1 \leq \text{gondolaSeq[i]} \leq 250000$</td></tr></tbody></table></div>


# 例子


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>gondolaSeq</th><th>返回值</th><th>replacementSeq</th></tr></thead><tbody><tr><td>4</td><td>$(3, 1, 4)$</td><td>$1$</td><td>$(2)$</td></tr><tr><td>4</td><td>$(5, 1, 2, 3, 4)$</td><td>$0$</td><td>$()$</td></tr><tr><td>5</td><td>$(2, 3, 4, 9, 6, 7, 1)$</td><td>$2$</td><td>$(5, 8)$</td></tr></tbody></table></div>


# 替换序列计数


<p>在接下来的四个子任务中，你必须计算所有能够生成给定序列（有可能是缆车序列，也有可能不是）的可能替换序列的数目，并将其对 $1000000009$ 取模。你需要实现一个函数 countReplacement。</p>
<ul><li>countReplacement(n, inputSeq)<ul><li>$n$: 输入序列的长度。</li>
<li>inputSeq: 大小为 $n$ 的数组；inputSeq[i] 是输入序列的第 $i$ 个元素，其中 $0 \leq i \leq n - 1$。</li>
<li>如果输入序列是一个缆车序列，则计算能够生成该缆车序列的可能的替换序列的数目（有可能会非常大），<strong>然后将该数值对 $1000000009$ 取模做为返回值</strong>。如果输入序列不是一个缆车序列，函数应返回 $0$。如果输入序列是一个缆车序列，但是没有缆车发生故障，函数应返回 $1$。</li>
</ul></li>
</ul>
# 子任务7, 8, 9, 10


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th>$n$</th><th>inputSeq</th></tr></thead><tbody><tr><td>7</td><td>5</td><td>$4 \leq n \leq 50$</td><td>$1 \leq \text{inputSeq[i]} \leq n + 3$</td></tr><tr><td>8</td><td>15</td><td>$4 \leq n \leq 50$</td><td>$1 \leq \text{inputSeq[i]} \leq 100$，初始缆车 $1, \dots, n$ 中至少有 $n - 3$ 个不会发生故障。</td></tr><tr><td>9</td><td>15</td><td>$n \leq 100000$</td><td>$1 \leq \text{inputSeq[i]} \leq 250000$</td></tr><tr><td>10</td><td>10</td><td>$n \leq 100000$</td><td>$1 \leq \text{inputSeq[i]} \leq 1000000000$</td></tr></tbody></table></div>


# 例子


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>inputSeq</th><th>返回值</th><th>替换序列</th></tr></thead><tbody><tr><td>7</td><td>$(1, 2, 7, 6)$</td><td>$2$</td><td>$(3, 4, 5)$ 或 $(4, 5, 3)$</td></tr><tr><td>8</td><td>$(2, 3, 4, 12, 6, 7, 1)$</td><td>$1$</td><td>$(5, 8, 9, 10, 11)$</td></tr><tr><td>9</td><td>$(4, 7, 4, 7)$</td><td>$0$</td><td>inputSeq不是一个缆车序列</td></tr><tr><td>10</td><td>$(3, 4)$</td><td>$2$</td><td>$(1, 2)$ 或 $(2, 1)$</td></tr></tbody></table></div>


# 实现细节


<p>本题只支持 C/C++。</p>
<p>你只能提交一个源文件实现上述的函数，在该文件中应实现前面所述的三个函数（即便你只想解决其中的部分子任务，也要给出全部函数），并遵循下述命名与接口。你还需要包含头文件 gondola.h。</p>
<pre><code class="sh_cpp">int valid(int n, int inputSeq[]);
int replacement(int n, int gondolaSeq[], int replacementSeq[]);
int countReplacement(int n, int inputSeq[]);</code></pre>

# 评测方式


<p>评测系统将会读入如下格式的输入数据：</p>
<ul><li>第 $1$ 行: $T$，你的程序需要解决的子任务编号（$ 1 \leq T \leq 10$）。</li>
<li>第 $2$ 行: $n$，输入序列的长度。</li>
<li>第 $3$ 行: 如果 $T$ 是4、5或者6，此行包含 $\text{gondolaSeq[0]}, \dots, \text{gondolaSeq[n-1]}$。否则此行包含$\text{inputSeq[0]}, \dots, \text{inputSeq[n-1]}$。</li>
</ul><p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=27">样例及测评库下载</a></p>
