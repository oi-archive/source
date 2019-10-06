# 题目描述

<p>sylvia 是一个擅长唱歌的女孩子，这天她决定要教 $n$ 个小学生如何唱歌。</p>
<p>在精心挑选后，sylvia 找到了一首简单好听的歌曲 $s$，这首歌曲有 $m$ 个音，每一个音的音高用一个小写字母来表示，即可以理解为这首歌曲是一个长度为 $m$ 的小写字符串。</p>
<p>最开始，sylvia 让这些小学生从小到高排成一排，第 $i$ 个小学生标号为 $i$。为了让合唱显得整齐，她想要从这个队列中，挑出连续的长度为 $m$ 的一段 $[L,L+m-1]$ 来进行一次合唱表演：首先第 $L$ 个小学生唱第 $1$ 个音，接着第 $L+1$ 个小学生唱第 $2$ 个音，$\dots$，最后第 $L+m-1$ 个小学生唱第 $m$ 个音。</p>
<p>然而，所有小学生都是五音不全的咸鱼，什么音都不会唱。</p>
<p>为了教会小学生如何唱歌，sylvia 设计了若干个课程，其中第 $i$ 个课程为“教第 $a_i$ 小学生唱第 $b_i$ 个音”，并决定用如下的形式进行教学：</p>
<p>每一次，sylvia 会在所有课程中等概率挑选一个课程进行（即使这个课程已经进行过了），在这个课程结束时，第 $a_i$ 个小学生就学会了如何唱第 $b_i$ 个音。</p>
<p>当然，sylvia 也是一个小懒惰的女孩子。当她发现队列中存在一个区间 $[L,L+m-1]$ 满足对于所有 $i \in [1,m]$，第 $L+i-1$ 个熊孩子都已经学会了唱第 $s_i$ 个音时，她就会停止教学 —— 因为合唱已经可以顺利进行啦。</p>
<p>现在，sylvia 想要知道她需要上的课程数的期望是多少？</p>

# 输入格式


<p>输入第一行一个正整数 $T$，表示数据组数。</p>
<p>对于每组数据，第一行两个正整数 $n,m$ 表示小学生数目和歌曲长度。保证 $1 \leq m \leq n$。</p>
<p>接下来 $n$ 行，每行一个不包含重复小写字母的字符串 $t_i$，其中字符串的每一位 $t_{i,j}$ 都表示存在一个课程是教第 $i$ 个小学生如何唱音 $t_{i,j}$。</p>
<p>接下来一行一个长度为 $m$ 的小写字符串，表示歌曲的内容。</p>

# 输出格式


<p>对于每组数据输出一行，一个整数，表示答案。由题目性质知，期望一定可以写成 $\frac{p}{q}$ 形式的有理数，请输出期望对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数） 取模后的结果，即找出一个 $x$ （$0 \leq x &lt; 998244353$） 使得 $qx \equiv p \pmod{998244353}$。显见这样的 $x$ 是唯一的。</p>
<p>如果无论如何 sylvia 的教学都不会结束，那么输出 -1。</p>

# 样例一


<h4>input</h4>
<pre>1
1 1
ab
a

</pre>

<h4>output</h4>
<pre>2

</pre>

<h4>explanation</h4>
<p>第一节课上完就结束的概率是 $\frac{1}{2}$，第二节课上完结束的概率是 $\frac{1}{4}$，第 $i$ 节课上完结束的概率是 $\frac{1}{2^i}$。</p>
<p>所以答案是 $\sum_{i=1}^\infty \frac{i}{2^i}=\sum_{i=1}^\infty \frac{1}{2^{i-1}}=2$</p>

# 样例二


<h4>input</h4>
<pre>1
3 2
acb
cb
ab
cb

</pre>

<h4>output</h4>
<pre>915057330

</pre>


# 样例三


<p>见样例数据下载，限制与约定跟第 $4$ 个测试点相同。</p>

# 样例四


<p>见样例数据下载，限制与约定跟第 $7$ 个测试点相同。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n$</th><th>$m$</th><th>约定</th></tr></thead><tbody><tr><td>1</td><td rowspan="3">$\leq 30$</td><td rowspan="3">$\leq 30$</td><td rowspan="3">$n=m$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="3">$\leq 5$</td><td rowspan="3">$\leq 5$</td><td rowspan="3">$t_i$ 的长度不超过 $3$</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="2">$\leq 15$</td><td rowspan="2">$\leq 15$</td><td rowspan="4"></td></tr><tr><td>8</td></tr><tr><td>9</td><td rowspan="2">$\leq 30$</td><td rowspan="2">$\leq 30$</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有数据，$T \leq 5$</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=214">样例数据下载</a></p>
