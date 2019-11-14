# 题目描述

<p>我们建立了一个由编号为 $0, \dots , n-1$ 的 $n$ 个人组成的社交网络。网络中的有些对会成为朋友。如果 $x$ 号人成为 $y$ 号人的朋友，则 $y$ 号人同时也会成为 $x$ 号人的朋友。</p>
<p>这些人将通过 $n$ 个阶段加入这个网络，阶段也编号为 $0$ 至 $n - 1$。第 $i$ 号人在第 $i$ 个阶段加入。在阶段 $0$，$0$ 号人加入网络并成为唯一的人。此后 $n - 1$ 个阶段的各个阶段，都有一个人会被主持人加入到网络中，而这个主持人可以是已在网络中的任何一个人。在阶段 $i$ 中 ($1 \leq i \leq n - 1$)，该阶段的主持人可以用如下三种方式之一把第 $i$ 号人加入到网络中：</p>
<ul><li>IAmYourFriend：将第 $i$ 号人仅变成主持人的朋友。</li>
<li>MyFriendsAreYourFriends：将第 $i$ 号人变成主持人当前的每一个朋友的朋友。 注意，这个方式不会将第 $i$ 号人变成主持人的朋友。</li>
<li>WeAreYourFriends：将第 $i$ 号人变成主持人的朋友，同时也变成主持人当前的每一个朋友的朋友。</li>
</ul><p>在建立此网络之后，我们想挑选一个调查的样本，也就是说要从网络中选择一组人。由于朋友之间通常拥有相似的兴趣，因此样本不应包含任何一对互为朋友的人。每个人都会有一个调查的可信度，表示为一个正整数，而我们想要找出一个可信度总和最大的样本。</p>

# 任务


<p>给定各阶段的描述以及每个人的可信度值，请找出一个可信度总和最大的样本。你只需要实现函数 findSample。</p>
<ul><li>findSample(n, confidence, host, protocol)<ul><li>$n$: 人数.</li>
<li>confidence: 大小为 $n$ 的数组；confidence[i]表示第 $i$ 号人的可信度。</li>
<li>host: 大小为 $n$ 的数组；host[i] 表示阶段 $i$ 的主持人。</li>
<li>protocol: 大小为 $n$ 的数组；protocol[i] 表示在阶段 ($0 &lt; i &lt; n$) 所采用的方式的代码: $0$ 代表 IAmYourFriend，$1$ 代表 MyFriendsAreYourFriends，而 $2$ 代表 WeAreYourFriends。</li>
<li>由于在阶段$0$中没有主持人，因此 host[0] 和 protocol[0] 是没有被定义的，而且在你的程序中也不应访问它们。</li>
<li>这个函数应该返回样本可信度总和的最大值。</li>
</ul></li>
</ul>
# 子任务


<p>有些子任务只会使用其中部分方式，如下表所示。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th>$n$</th><th>可信度</th><th>采用的方式</th></tr></thead><tbody><tr><td>1</td><td>11</td><td>$2 \leq n \leq 10$</td><td>$1 \leq \text{confidence} \leq 1000000$</td><td>全部三种方式</td></tr><tr><td>2</td><td>8</td><td>$2 \leq n \leq 1000$</td><td>$1 \leq \text{confidence} \leq 1000000$</td><td>只有 MyFriendsAreYourFriends</td></tr><tr><td>3</td><td>8</td><td>$2 \leq n \leq 1000$</td><td>$1 \leq \text{confidence} \leq 1000000$</td><td>只有 WeAreYourFriends</td></tr><tr><td>4</td><td>19</td><td>$2 \leq n \leq 1000$</td><td>$1 \leq \text{confidence} \leq 1000000$</td><td>只有 IAmYourFriend</td></tr><tr><td>5</td><td>23</td><td>$2 \leq n \leq 1000$</td><td>所有可信度值均为 $1$</td><td>只有 MyFriendsAreYourFriends 和
IAmYourFriend 两种方式</td></tr><tr><td>6</td><td>31</td><td>$2 \leq n \leq 100000$</td><td>$1 \leq \text{confidence} \leq 10000$</td><td>全部三种方式</td></tr></tbody></table></div>


# 实现细节


<p>本题只支持 C/C++。</p>
<p>你只能提交一个源文件实现上述的函数，其命名与接口需遵循下面的要求。你还要在该文件中包含头文件friend.h。</p>
<pre><code class="sh_cpp">int findSample(int n, int confidence[], int host[], int protocol[]);</code></pre>

# 评测方式


<p>评测系统将会读入如下格式的输入数据：</p>
<ul><li>第 $1$ 行: $n$</li>
<li>第 $2$ 行: $\text{confidence[0]}, \dots, \text{confidence[n-1]}$</li>
<li>第 $3$ 行: $\text{host[1]}, \text{protocol[1]}, \text{host[2]}, \text{protocol[2]}, \dots, \text{host[n-1]}, \text{protocol[n-1]}$</li>
</ul><p>评测系统将会输出 findSample 的返回值。</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$16\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=28">样例及测评库下载</a></p>
<p>什么你说样例1和样例6是相同的？IOI原题也是相同的，不要不服。</p>
