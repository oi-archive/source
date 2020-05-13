# 题目描述

<p>IOI2015 开幕式正在进行最后一个环节。按计划，在开幕式期间，每个代表队都将收到由主办方发放的一个装有纪念品的盒子。然而所有志愿者都被精彩的开幕式所吸引，除 Aman 以外其他人完全忘记了发放纪念品这件事。Aman 是一位热情的志愿者，为使得 IOI 尽量圆满，他要用最短的时间将所有纪念品发放出去。</p>
<p>开幕式的场地是一个被划分成 $L$ 个完全相等的区域的圆环，这些区域的编号依次是 $0$ 到 $L-1$，也就是说，对于 $0\leq i \leq L-2$，区域 $i$ 与区域 $i+1$ 相邻，且区域 $L-1$ 与区域 $0$ 相邻。场地上一共有 $N$ 个代表队，每队坐在上面的某个区域上，每个区域可以包含任意多个代表队，也可以为空。</p>
<p>一共有 $N$ 个相同的纪念品。一开始，Aman 和所有纪念品都在区域 $0$。Aman 应该给每队一个纪念品，并且在发放完最后一个纪念品后他必须回到区域 $0$ 。注意，有些队可能坐在区域 $0$。</p>
<p>Aman 可以花费 $1$ 秒的时间从一个区域移动到与他相邻的区域(顺时针或者逆时针都可以)，当 Aman 经过区域 $0$ 时他可以拿走若干纪念品，拿走纪念品是不需要时间的。任意时刻，Aman 身上只能携带不超过 $K$ 个纪念品，Aman 可以给所在区域的队伍发纪念品，这也是不需要时间的。</p>
<p>你的任务是：计算 Aman 从区域 $0$ 出发，给每个队伍发送纪念品并且最后回到区域 $0$ 至少需要多少时间（秒）。</p>

# 样例


<p>在这个样例中，代表队的数目 $N=3$，Aman 最多携带纪念品的数量 $K=2$，区域的数量 $L=8$。这些代表队分别位于区域 $1$，$2$和$5$。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/229/boxes.png" alt="样例"/></p>
<p>上图是最优解之一。</p>
<p>第一步：Aman 在起点拿走 $2$ 个纪念品，一个发给区域 $2$，一个发给区域 $5$，然后顺便绕回到起点，刚好走了一圈，花费了 $8$ 秒钟。</p>
<p>第二步：Aman 在起点拿走 $1$ 个纪念品，发给区域 $1$，然后原路返回，花费了 $2$ 秒钟。</p>
<p>于是总用时是 $10$ 秒钟。</p>

# 任务


<p>你需要实现函数 delivery，对于给定的 $N$，$K$，$L$，以及所有代表队所在的区域，计算并返回 Aman 所需要的最短时间（秒钟）。</p>
<ul><li>delivery(N, K, L, positions)<ul><li>N：代表队的数目</li>
<li>K：Aman每次最多能携带的纪念品数量。</li>
<li>L：开幕式场地上的区域数目。</li>
<li>positions：一个长度为 N 的数组，positions[0],positions[1]...positions[N-1]给出了所有代表队所在的区域的编号，positions的元素按非递减排序。</li>
<li>该函数应当返回 Aman 所需要的最短时间（秒数）。</li>
</ul></li>
</ul>
# 子任务


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$N$</th>
<th>$K$</th>
<th>$L$</th>
</tr></thead><tbody><tr><td>1</td><td>10</td><td rowspan="2">$1 \leq N \leq 1000$</td><td>$K=1$</td><td rowspan="6">$1 \leq L \leq 10^9$</td></tr><tr><td>2</td><td>10</td><td>$K = N$</td></tr><tr><td>3</td><td>15</td><td>$1 \leq N \leq 10$</td><td rowspan="2">$1 \leq K \leq N$</td></tr><tr><td>4</td><td>15</td><td>$1 \leq N \leq 1000$</td></tr><tr><td>5</td><td>20</td><td>$1 \leq N \leq 10^6$</td><td>$1 \leq K \leq 3000$</td></tr><tr><td>6</td><td>30</td><td>$1 \leq N \leq 10^7$</td><td>$1 \leq K \leq N$</td></tr></tbody></table></div>


# 实现细节


<p>本题只支持 C/C++。</p>
<p>你只能提交一个源文件实现如上所述的 delivery 函数，并且遵循下面的命名和接口。你需要包含头文件 boxes.h。</p>
<pre><code class="sh_cpp">long long delivery(int N, int K, int L, int positions[]);</code></pre>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ol><li>第 $1$ 行：$N$ $K$ $L$</li>
<li>第 $2$ 行：$positions[0] ... positions[N-1]$</li>
</ol><p>评测系统将调用 $delivery$ 并输出它的返回值。</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$1500\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=229">样例及测评库下载</a></p>
