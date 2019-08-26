
# Description

<div class="content"><div>猪小侠最近学习了最长上升子序列的相关知识。对于一个整数序列 A=(a1,a2,?,ak)，定义A 的子序列为：从A 中</div>
<div>删除若干个元素后（允许不删，也允许将所有k 个元素都删除），剩下的元素按照原来的顺序所组成的序列。如果</div>
<div>这个子序列的元素从左到右严格递增，则称它为A 的一个上升子序列。其中包含元素数量最多的上升子序列称为A </div>
<div>的最长上升子序列。例如，(2,4,5,6)和 (1,4,5,6)都是 (2,1,1,4,7,5,6)的最长上升子序列，长度都为 4。现在</div>
<div>猪小侠遇到了这样一个问题：给定一个序列 Bm=(b1,b2,?,bm)，设C 是 Bm的子序列，且C 的最长上升子序列的长</div>
<div>度不超过k，则C 的长度最大能是多少？猪小侠觉得这个问题太简单了，缺乏挑战，他决定提出一个更难的问题。</div>
<div>于是他给了你这样一个序列 B=(b1,b2,…,bn)，以及若干次询问。每次询问会给定两个整数m 和k，你需要对于B </div>
<div>序列的前m 个元素构成的序列 Bm=(b1,b2,?,bm)和k 回答上述问题。</div>
<div></div></div>

# Input

<div class="content"><div>第一行两个整数 n,q其中 n是序列B 的长度，q是询问次数。</div>
<div>第二行是空格隔开的 n个正整数 b1,b2,?,bn </div>
<div>接下来 q行，其中第 i行包含两个整数 mi,ki，表示对 m=mi,k=ki 进行询问。</div>
<div>N&lt;=50000</div>
<div></div></div>

# Output

<div class="content"><div>输出共 q行，按顺序每行一个整数作为回答。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">11 6<br/>
9 6 3 1 5 12 8 4 2 2 2<br/>
5 1<br/>
7 2<br/>
9 1<br/>
9 2<br/>
11 1<br/>
11 11</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
6<br/>
5<br/>
8<br/>
7<br/>
11</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

