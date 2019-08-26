
# Description

<div class="content"><div>小 C 有一棵 n 个结点的有根树，根是 1 号结点，且每个结点最多有两个子结点。</div>
<div>定义结点 x 的权值为：</div>
<div>1.若 x 没有子结点，那么它的权值会在输入里给出，保证这类点中每个结点的权值互不相同。</div>
<div>2.若 x 有子结点，那么它的权值有 px的概率是它的子结点的权值的最大值，有 1?px的概率是它的子结点的权值的最小值。</div>
<div>现在小 C 想知道，假设 1 号结点的权值有 m 种可能性，权值第 i 小的可能性的权值是 Vi，它的概率为 Di，求：</div>
<div> <img src="source/bzoj/5461/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgxMS8xMTEucG5n.png" width="376" height="105" alt=""/></div>
<p></p></div>

# Input

<div class="content"><div>输入</div>
<div>第一行一个正整数 n；</div>
<div>第二行 n 个整数，第 i个整数表示第 i 个结点的父亲的编号，其中第 1 个结点的父亲为 0；</div>
<div>第三行 n 个整数，若第 i 个结点没有子结点，则第 i 个数为它的权值，否则第 i 个数为 pi×10000，保证 pi×10000是个正整数。</div>
<div>0&lt;pi&lt;1,1&lt;=N&lt;=3*10^5,1&lt;wi&lt;=10^9</div>
<p></p></div>

# Output

<div class="content"><div>输出答案</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
0 1 1<br/>
5000 1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">748683266<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

