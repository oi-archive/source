# 题目描述

<p>零点的钟声马上就要敲响，2016 年即将要拉开序幕，元旦老人轻手轻脚地来到了 <span class="uoj-username" data-rating="1646">shanquan2</span> 的床头，准备把他的礼物装进袜子里。</p>
<p>然而，<span class="uoj-username" data-rating="1646">shanquan2</span> 的礼物居然是一张无向图！无向图怎么才能装进袜子里呢？这让元旦老人犯了难。</p>
<p>经过研究，元旦老人发现：只有满足一定条件的无向图才能被装进袜子里。</p>
<p>对于一张 $n$ 个点 $m$ 条边的无向图，你可以选出若干条边（可以全选也可以不选），如果存在一种方案使得无论是只保留所有你选出的边还是只保留所有你没有选出的边，这张无向图都是一个森林（即没有环），那么这张无向图被称为丛林。</p>
<p>元旦老人发现只有丛林才能够被装进袜子里！然而留给元旦老人的时间已经所剩无几了，情急之下，他决定向你寻求帮助：判断一张无向图是不是丛林。</p>

# 输入格式


<p>第一行两个正整数 $n,m$。</p>
<p>接下来的 $m$ 行每行两个正整数 $u,v(1 \leq u,v \leq n)$，表示图中的一条无向边。</p>
<p>注意：这张图可能存在重边和自环。</p>

# 输出格式


<p>仅输出一行一个字符串，如果这张图是丛林，输出 Yes，否则输出 No。</p>

# 样例一


<h4>input</h4>
<pre>2 2
1 2
1 2

</pre>

<h4>output</h4>
<pre>Yes

</pre>

<h4>explanation</h4>
<p>选出任意一条边都能满足条件。</p>

# 样例二


<h4>input</h4>
<pre>2 3
1 2
1 2
1 2

</pre>

<h4>output</h4>
<pre>No

</pre>

<h4>explanation</h4>
<p>无论怎么选择都会有一边存在环。</p>

# 样例三


<h4>input</h4>
<pre>5 4
1 2
2 3
1 5
2 4

</pre>

<h4>output</h4>
<pre>Yes

</pre>

<h4>explanation</h4>
<p>这张图本来就是森林，所以无论怎么选都是满足条件的。</p>

# 样例四


<h4>input</h4>
<pre>5 8
1 2
2 3
3 1
1 4
4 5
5 1
2 4
3 5

</pre>

<h4>output</h4>
<pre>Yes

</pre>

<h4>explanation</h4>
<p>选出边 $(1,2),(2,3),(1,4)$ 和 $(3,5)$ 是满足条件的。</p>

# 样例五


<h4>input</h4>
<pre>5 9
1 2
2 3
3 1
1 4
4 5
5 1
2 4
3 5
2 5

</pre>

<h4>output</h4>
<pre>No

</pre>


# 样例六


<p>见样例数据下载。</p>

# 样例七


<p>见样例数据下载。</p>

# 限制与约定


<p>由于一些原因，本题使用捆绑测试。每个子任务有若干个测试点，分为 $3$ 个子任务，你只有通过一个子任务的所有测试点才能得到这个子任务的分数。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$n$ 的规模</th>
<th>$m$ 的规模</th>
<th>其他</th>
</tr></thead><tbody><tr><td>1</td><td>$20$</td><td>$n \leq 10$</td><td>$m \leq 20$</td><td></td></tr><tr><td>2</td><td>$20$</td><td rowspan="3">$n \leq 300$</td><td>$m \leq n+7$</td><td>保证图联通</td></tr><tr><td>3</td><td>$10$</td><td rowspan="2">$m \leq 600$</td><td>每个点的度数都不小于 $4$</td></tr><tr><td>4</td><td>$30$</td><td rowspan="2"></td></tr><tr><td>5</td><td>$20$</td><td>$n \leq 2000$</td><td>$m \leq 4000$</td></tr></tbody></table></div>

<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=168">样例数据下载</a></p>

# 新年快乐！


<p>2016，好好做人。</p>
