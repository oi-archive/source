# 题目描述

<p>健佳正在用大小相同的砖块来砌起一面墙。这面墙由 $n$ 列砖块所组成，它们从左到右的编号为 $0$ 至 $n - 1$。各列的高度可以不同。各列的高度就是该列砖块的数量。</p>
<p>健佳用如下方式来建造这面墙。最开始每列都没有砖块。此后，健佳通过 $k$ 个阶段的增加或移除砖块操作来砌墙。当所有 $k$ 个阶段完成后，这面墙就砌好了。在每个阶段中，健佳都会被告知一个连续的砖块列的范围，以及一个高度值 $h$，然后他就完成如下过程：</p>
<ul><li>在增加砖块阶段，对于给定的列范围中高度小于 $h$ 的列，健佳会增加砖块使它们的高度都恰好等于 $h$。此时他不会改变那些高度大于或等于 $h$ 的列。</li>
<li>在移除砖块阶段，对于给定的列范围中高度大于 $h$ 的列，健佳会移除砖块使它们的高度都恰好等于 $h$。此时他不会改变那些高度小于或等于 $h$ 的列。</li>
</ul><p>你的任务就是计算出这面墙的最后形状。</p>

# 任务


<p>给出这 $k$ 个阶段的描述后，请计算出当所有 $k$ 个阶段都完成之后各列的砖块数量。你需要实现函数 buildWall。</p>
<ul><li>buildWall(n, k, op, left, right, height, finalHeight)<ul><li>$n$: 这面墙中的列数。</li>
<li>$k$: 阶段数。</li>
<li>op: 大小为 $k$ 的数组；op[i] 是第 $i$ 个阶段的类型：1 表示增加阶段而 2 表示移除阶段，其中 $0 \leq i \leq k - 1$。</li>
<li>left 和 right: 大小为 $k$ 的数组；在第 $i$ 个阶段中，列的范围从第 left[i] 列开始到第 right[i] 列结束（包括两端 left[i] 和 right[i]），其中 $0 \leq i \leq k - 1$。这里保证满足 left[i] $\leq$ right[i]。</li>
<li>height: 大小为 $k$ 的数组；height[i] 表示在阶段 $i$ 的高度参数，其中 $0 \leq i \leq k - 1$。</li>
<li>finalHeight: 大小为 $n$ 的数组；你需要把第 $i$ 列砖块的最终数量存放到 finalHeight[i] 中做为返回结果，其中 $0 \leq i \leq n - 1$。</li>
</ul></li>
</ul>
# 子任务


<p>在所有子任务中，所有阶段中的高度参数均为小于或等于 $100000$ 的非负整数。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$n$</th>
<th>$k$</th>
<th>备注</th>
</tr></thead><tbody><tr><td>1</td><td>8</td><td>$1 \leq n \leq 10000$</td><td>$1 \leq k \leq 5000$</td><td>无其他限制</td></tr><tr><td>2</td><td>24</td><td>$1 \leq n \leq 100000$</td><td>$1 \leq k \leq 500000$</td><td>全部增加阶段均在全部移除阶段之前</td></tr><tr><td>3</td><td>29</td><td>$1 \leq n \leq 100000$</td><td>$1 \leq k \leq 500000$</td><td>无其他限制</td></tr><tr><td>4</td><td>39</td><td>$1 \leq n \leq 2000000$</td><td>$1 \leq k \leq 500000$</td><td>无其他限制</td></tr></tbody></table></div>


# 实现细节


<p>本题只支持 C/C++。</p>
<p>你只能提交一个源文件实现上述的函数，其命名与接口需遵循下面的要求。你还要在该文件中包含头文件wall.h。</p>
<pre><code class="sh_cpp">void buildWall(int n, int k, int op[], int left[], int right[], int height[], int finalHeight[]);</code></pre>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ul><li>第 $1$ 行：$n$, $k$。</li>
<li>第 $2+i$ 行：op[i], left[i], right[i], height[i]。</li>
</ul><p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$3\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=25">样例及测评库下载</a></p>
