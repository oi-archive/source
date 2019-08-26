
# Description

<div class="content"><div>
<div>Yazid有一个长度为n的序列A，下标从1至n。显然地，这个序列共有n(n+1)/2个子区间。对于任意一个子区间[l,r]</div>
<div>，如果该子区间内的众数在该子区间的出现次数严格大于(r?l+1)/2（即该子区间长度的一半），那么Yazid就说这</div>
<div>个子区间是&#34;新生舞会的&#34;。所谓众数，即为该子区间内出现次数最多的数。特别地，如果出现次数最多的数有多个</div>
<div>，我们规定值最小的数为众数。现在，Yazid想知道，共有多少个子区间是&#34;新生舞会的&#34;</div>
<div></div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行2个用空格隔开的非负整数n,type，表示序列的长度和数据类型。数据类型的作用将在子任务中说明。</div>
<div>第二行n个用空格隔开的非负整数，依次为A1,A2,...,An，描述这个序列。</div>
<div>N&lt;=500000,0&lt;=Type&lt;=3</div>
<div>对于所有数据，保证 0 ≤ Ai ≤ n ? 1。</div>
<div>对于 type = 0 的数据，没有任何特殊约定。</div>
<div>对于 type = 1 的数据，保证 Ai ∈ {0, 1}。</div>
<div>对于 type = 2 的数据，保证序列 A 的众数在整个序列中的出现次数不超过 15。</div>
<div>对于 type = 3 的数据，保证 Ai ≤ 7。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数，表示答案。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 0<br/>
1 1 2 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
//&#34;新生舞会的&#34; 子区间有 [1, 1], [1, 2], [1, 3], [2, 2], [2, 4], [3, 3], <br/>
[3, 4], [3, 5], [4, 4], [5, 5]共 10 个。</span></div>

# Hint

<div class="content"><p></p><div>来自 CodePlus 2017 11 月赛，清华大学计算机科学与技术系学生算法与竞赛协会 荣誉出品。</div><br/>
<div>Credit：idea/郑林楷　命题/王聿中　验题/郑林楷</div><br/>
<div>Git Repo：https://git.thusaac.org/publish/CodePlus201711</div><br/>
<div>本次比赛的官方网址：cp.thusaac.org</div><br/>
<div>感谢腾讯公司对此次比赛的支持。</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

