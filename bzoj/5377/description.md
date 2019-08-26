
# Description

<div class="content"><div>给定一个n个点m条边的有向弱连通图，每个点均匀点权di和修改耗时wi，每次修改可以花费wi的时间把di</div>
<div>加1或者减1，求最少消耗多少时间，使得∀(u,v)∈E,du≤dv。</div>
<p></p></div>

# Input

<div class="content"><div>输入共包括m+3行</div>
<div>第一行包含两个整数n,m表示点数和边数。</div>
<div>第二行包含n个整数，第i个整数表示第i个点的点权di。</div>
<div>第三行包含n个整数，第i个整数表示第i个点的修改耗时wi。</div>
<div>第4m+3行，每行包含两个整数ui,vi表示有向图种的一条由ui到vi的有向边。</div>
<div>n&lt;=300000,m=n或m=n-1</div>
<p></p></div>

# Output

<div class="content"><div>输出包含一个整数，表示最小总耗时。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
5 9 8<br/>
1 2 3<br/>
1 2<br/>
2 3<br/>
3 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
<br/>
样例解释 1<br/>
限制为 d1&lt;=d2, d2&lt;=d3,d3&lt;=d1，即要求d1=d2=d3，故将d1加3至8，d2减1至8最优，最下耗时为1*|5-8|+2*|9-8|+3*|8-8|=5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

