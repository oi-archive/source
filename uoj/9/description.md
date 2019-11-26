# 题目描述

<p>UOJ上，由于一群人开心的在hack着，有的题的测试数据都有$10000$组了！</p>
<p>为了处理这些数据，vfk决定把这道题所有输入数据都弄出来，每个数据给个编号，比如$\texttt{uoj1.in}$, $\texttt{uoj2.in}$。</p>
<p>这些编号是随机的，可以不连续，比如三组数据分别叫$\texttt{uoj1.in}$, $\texttt{uoj100.in}$, $\texttt{uoj2014.in}$。</p>
<p>输入数据的文件名一定是：题目名 + 数据编号 + &#34;$\texttt{.in}$&#34;。</p>
<p>vfk要你把这些输入文件按<strong>数据编号</strong>进行排序，之后用在线仙人球嵌套动态网络路径剖分优化的分支定界贪心剪枝启发式迭代加深人工智能搜索决策算法解决问题。</p>

# 输入格式


<p>第一行一个正整数$n$，表示输入文件的个数。</p>
<p>接下来$n$个字符串表示每个输入文件的文件名，形如： 题目名 + 数据编号 + &#34;$\texttt{.in}$&#34;，保证：</p>
<ol><li>数据编号一定是正整数且不包含前导零。</li>
<li>数据编号一定互不相同。</li>
<li>题目名仅包含大小写字母和下划线。</li>
<li>所有输入文件的题目名完全一致。</li>
<li>特别的，如果是像$\texttt{1.in}$, $\texttt{2.in}$这种，我们认为题目名为空，也是允许的</li>
</ol>
# 输出格式


<p>共$n$行，每行一个字符串，表示排序的结果。</p>

# 样例一


<h4>input</h4>
<pre>8
dajiahaowoshiyangli9.in
dajiahaowoshiyangli5.in
dajiahaowoshiyangli2.in
dajiahaowoshiyangli1.in
dajiahaowoshiyangli3.in
dajiahaowoshiyangli7.in
dajiahaowoshiyangli6.in
dajiahaowoshiyangli8.in

</pre>

<h4>output</h4>
<pre>dajiahaowoshiyangli1.in
dajiahaowoshiyangli2.in
dajiahaowoshiyangli3.in
dajiahaowoshiyangli5.in
dajiahaowoshiyangli6.in
dajiahaowoshiyangli7.in
dajiahaowoshiyangli8.in
dajiahaowoshiyangli9.in

</pre>


# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$的规模</th>
</tr></thead><tbody><tr><td>1~5</td><td>$n \le 100$</td>
</tr><tr><td>6~10</td><td>$n \le 10000$</td>
</tr></tbody></table></div>

<p>保证每个字符串的长度小于等于$100$。</p>
<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=9">样例数据下载</a></p>
