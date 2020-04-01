
# Description

<div class="content"><div>中二病正在危害人类！不知何时爆发的中二病，起初还毫无任何症状，最近却连续出现致命症状，已经成为了一种不治之症。科学家们正在着手研发疫苗。</div>
<div>科学家从患者体内提取出了中二病病原体，并找出了其致病DNA。这条DNA可以被分为 段，第 段和第1段相接，呈环形。要制作疫苗的话，需要从中取出若干段DNA。 </div>
<div>然而，中二病的生存和复制能力特别强。如果疫苗中存在两段在原DNA中距离小于 的DNA，这两段就可以复制出整条DNA。因此，科学家选择的若干段DNA彼此之间的距离都应该不小于 。</div>
<div>这里定义距离为两段DNA在原序列中间隔的最少段数+1，如相邻的两段距离为1。自己与自己的距离不做定义，换言之，不论 的值是多少，总能选出一段DNA。</div>
<div>为了使疫苗对于各种属性的人都有效，科学家想制作尽量多种的疫苗。也就是说，要在满足上面的条件的情况下，选出尽量多组不同的DNA段，分别制成疫苗。当然，选出这样若干段的方案数有很多，但是有些方案在旋转之后是相同的，因此在本质上也是相同的。</div>
<div>请你编写一个程序，求出最多能制作的疫苗种数，以及最多能制作的本质不同的疫苗种数。由于答案可能很大，输出答案对<span style="color: rgb(255, 0, 0);">10^9+7</span>取模得到的结果。</div>
<p></p></div>

# Input

<div class="content"><div>输入只有一行，包含两个整数 和 ，含义如问题描述中所述。</div>
<p></p></div>

# Output

<div class="content"><div>输出两行，每行一个非负整数，分别表示所求的两个方案数取模得到的结果。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">【样例输入1】<br/>
5 2<br/>
【样例输入2】<br/>
6 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【样例输出1】<br/>
10<br/>
2<br/>
【样例输出2】<br/>
63<br/>
13<br/>
</span></div>

# Hint

<div class="content"><p></p><div>【样例1解释】</div><br/>
<div>注意一段都不选不是一个合法的方案。</div><br/>
<div>N&lt;=100000,K&lt;=100000,且1&lt;=K&lt;= n / 2</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

