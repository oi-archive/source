# 题目描述

<p>零点的钟声马上就要敲响，2016 年即将要拉开序幕，元旦老人轻手轻脚地来到了 <span class="uoj-username" data-rating="1225">xyz111</span> 的床头，准备把他的礼物装进袜子里。</p>
<p>然而，<span class="uoj-username" data-rating="1225">xyz111</span> 居然根本没有去睡觉！毫无防备的元旦老人落入了他的陷阱之中。</p>
<p>原来，<span class="uoj-username" data-rating="1225">xyz111</span> 仰慕正义的元旦老人已经很久了，于是他决定把元旦老人抓来探♂讨哲♂学（病娇脸）。</p>
<p>在经过交涉之后，<span class="uoj-username" data-rating="1225">xyz111</span> 答应，如果元旦老人能回答出他的一些问题，那么就放他走：</p>
<p>最开始 <span class="uoj-username" data-rating="1225">xyz111</span> 有两个长度为 $n$ 的完全相同的数列 $A$ 和 $B$，接下来有 $m$ 次操作，每一次操作都是以下的四种之一：</p>
<ol><li>对于所有的 $i \in [l,r]$，将 $A_i$ 变成 $A_i+c$。</li>
<li>对于所有的 $i \in [l,r]$，将 $A_i$ 变成 $\max(A_i,d)$。</li>
<li>对于所有的 $i \in [l,r]$，询问 $A_i$ 的最小值。</li>
<li>对于所有的 $i \in [l,r]$，询问 $B_i$ 的最小值。</li>
</ol><p>在每一次操作结束之后，<span class="uoj-username" data-rating="1225">xyz111</span> 都会进行一次更新：对于所有的 $i \in [1,n]$，将 $B_i$ 变成 $\min(B_i,A_i)$。</p>
<p>然而留给元旦老人的时间已经所剩无几了，情急之下，他决定向你寻求帮助：你能帮他回答 <span class="uoj-username" data-rating="1225">xyz111</span> 的问题吗。</p>

# 输入格式


<p>第一行两个数：$ n, m $。</p>
<p>接下来一行 $ n $ 个数 $A_i$。（最开始 $B_i$=$A_i$）</p>
<p>接下来 $ m $ 行中，第 $ i $ 行第一个数 $ t_i $ 表示操作类型：</p>
<p>若 $ t_i = 1 $，则接下来三个整数 $ l_i, r_i, c_i $，表示操作一。</p>
<p>若 $ t_i = 2 $，则接下来三个整数 $ l_i, r_i, d_i $，表示操作二。</p>
<p>若 $ t_i = 3 $，则接下来三个整数 $ l_i, r_i$，表示操作三。</p>
<p>若 $ t_i = 4 $，则接下来一个整数 $ l_i, r_i $，表示操作四。</p>

# 输出格式


<p>对于每个询问操作，输出一行表示答案。</p>

# 样例一


<h4>input</h4>
<pre>3 6
1 2 3
4 3 3
1 2 3 -2
3 1 3
4 3 3
2 2 3 4
3 1 3

</pre>

<h4>output</h4>
<pre>3
0
1
1

</pre>


# 样例二


<p>见样例数据下载。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$ 的规模</th><th>$m$ 的规模</th><th>其他约定</th></tr></thead><tbody><tr><td>1</td><td>$n \leq 3000$</td><td>$m \leq 3000$</td><td></td></tr><tr><td>2</td><td>$n \leq 100000$</td><td>$m \leq 100000$</td><td rowspan="2">不存在操作二</td></tr><tr><td>3</td><td>$n \leq 500000$</td><td>$m \leq 500000$</td></tr><tr><td>4</td><td rowspan="5">$n \leq 100000$</td><td rowspan="5">$m \leq 100000$</td><td rowspan="2">数据随机生成</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="5"></td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td><td rowspan="2">$n \leq 500000$</td><td rowspan="2">$m \leq 500000$</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有数据，保证有 $1 \leq l_i \leq r_i \leq n,-2000 \leq c_i \leq 2000$ 和 $-10^9 \leq A_i,d_i \leq 10^9$</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$96\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=169">样例数据下载</a></p>

# 新年快乐！


<p>2016，好好做人。</p>
