
# Description

<div class="content"><div>小Z最近遇上了大麻烦，他的数学分析挂科了。于是他只好找数分老师求情。善良的数分老师答应不挂他，但是要</div>
<div>求小Z帮助他一起解决一个难题问题是这样的，现在有n个标号为1～n的球和m个盒子，每个球都可以放进且只能放</div>
<div>进一个盒子里面，但是要满足如下的规则：</div>
<div>1.若把标号为i的球放进了第j个盒子，那么标号为2*i的球一定要在第j+1个盒子里面(若j&lt;m)</div>
<div>2.若把标号为i的球放进了第j个盒子，并且k*2=i，那么标号为k的球一定要在第j-1个盒子里面(若j&gt;1)</div>
<div>小Z的数分老师想要知道，给定了n和m的时候，第一个盒子最多能放进去多少个球。事实上，他已经推算出了公式</div>
<div>，但是需要检验当n趋向于无穷大时是否仍然满足这个公式，因此n可能会非常大。</div></div>

# Input

<div class="content"><div>
<div>本题包含多组数据，第一行为一个数(T&lt;=20)，表示数据组数；</div>
<div>以下T行，每组数据一行，包括两个数n和m。</div>
<div>n&lt;=10^10000,2&lt;=m&lt;=25</div>
</div></div>

# Output

<div class="content"><div>每组数据输出一行，包括一个数，即第一个盒子最多能放进多少个球。</div></div>

# Sample Input

<div class="content"><span class="sampledata"> 2<br/>
10 2<br/>
10 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
1<br/>
//样例解释：<br/>
(1).{1,3,4,5}, {2,6,8,10},(2).{1},{2},{4}</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

