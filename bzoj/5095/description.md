
# Description

<div class="content"><div>小Q在家中举行了一场盛大的派对！他一共邀请了n-1个人，他家的圆桌上共有m个座位，每个座位只能坐一个人，</div>
<div>因此给这n个人(包括小Q自己)安排座位成为了一个麻烦。n个人依次编号为1到m，圆桌上m个座位顺时针依次编号为</div>
<div>1到m，m和1也是相邻的。每个人有着一些忌讳的数字，因此每个人都可能不喜欢坐在某些座位上。小Q希望大家不</div>
<div>感到拥挤，因此他不会让两个人坐在相邻的座位上；他还不会让大家面对面而感到尴尬，因此他不会让两个人正对</div>
<div>面坐下(当然如果只有奇数个座位，那么永远不可能正对面)。请写一个程序，帮助小Q计算合法的座位安排的方案</div>
<div>数，因为答案可能很大，请对998244353取模输出。</div>
<div></div></div>

# Input

<div class="content"><p>第一行包含两个正整数n,m(2&lt;=n&lt;=10,4&lt;=m&lt;=1000)，分别表示人数和座位数。</p>
<div>接下来n行，每行一个长度为m的01串g_i，其中g_{i,j}为1表示第i个人可以坐在座位j，为0表示不可以。</div>
<div></div></div>

# Output

<div class="content"><div>输出一行一个整数，即合法方案数对998244353取模的结果。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 6<br/>
110111<br/>
101101<br/>
110111</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
<br/>
HINT<br/>
方案1：1坐在1，2坐在3，3坐在5。<br/>
方案2：1坐在5，2坐在3，3坐在1。<br/>
方案3：1坐在2，2坐在4，3坐在6。<br/>
方案4：1坐在2，2坐在6，3坐在4。<br/>
方案5：1坐在4，2坐在6，3坐在2。<br/>
方案6：1坐在6，2坐在4，3坐在2。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

