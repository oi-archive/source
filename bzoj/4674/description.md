
# Description

<div class="content"><div>给定3个长度为n的小写字母串s1、s2、t，在串t中挑选出一长度不超过</div>
<div>m的子序列seq，使得该子序列与串s1和串s2的距离的最大值最小，输出该值。</div>
<div>定义串a的位置i与串b的位置j的距离为ASCII差+距离差，即|a[i]-</div>
<div>b[j]|+val[|i-j|]，其中val数组给定。</div>
<div>如串a为abc，串b为def。</div>
<div>c和d的距离为|‘c’-‘d’|+val[|3-1|]=1+val[2]</div>
<div>c和e的距离为|‘c’-‘e’|+val[|3-2|]=2+val[1]</div>
<div>c和f的距离为|‘c’-‘f’|+val[|3-3|]=3+val[0]</div>
<div>定义串a的位置i与子序列seq的距离为串a的位置i与子序列seq各位置的距离的最小值。</div>
<div>同样令串a为abc，串b为def。</div>
<div>若取子序列seq为df(即def)，</div>
<div>则串a的c与该子序列的距离为min(1+val[2],3+val[0])。</div>
<div>若取子序列seq为ef（即def），</div>
<div>则串a的c与该子序列的距离为min(2+val[1],3+val[0])。</div>
<div>定义串a与子序列seq的距离为串a各位置与子序列seq的距离的最大值。</div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数T表示数据组数。</div>
<div>以下T组数据，每组5行：</div>
<div>第一行两个整数n,m。</div>
<div>第二行n个整数表示val[0]、val[1]……val[n-1]。</div>
<div>第三至第五行每行一长度为n的小写字母串，表示s1，s2，t。</div>
<div> n &lt;= 40, 0 &lt; m &lt;= n， 0 &lt;= val[i] &lt;= 2000， T &lt;= 100</div>
<p></p></div>

# Output

<div class="content"><div>T行，格式为“Case#T:Answer”，详见样例</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
3 2<br/>
0 1 2<br/>
azz<br/>
zaa<br/>
zza<br/>
7 2<br/>
0 1 2 3 4 5 6<br/>
elelele<br/>
psypsyp<br/>
congroo</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 2<br/>
Case #2: 9<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

