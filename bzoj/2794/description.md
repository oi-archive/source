
# Description

<div class="content"><p><span style="font-size: medium">有n件物品，每件物品有三个属性a[i], b[i], c[i] (a[i]&lt;b[i])。<br/>
再给出q个询问，每个询问由非负整数m, k, s组成，问是否能够选出某些物品使得：<br/>
1. 对于每个选的物品i，满足a[i]&lt;=m且b[i]&gt;m+s。<br/>
2. 所有选出物品的c[i]的和正好是k。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行一个正整数n (n&lt;=1,000)，接下来n行每行三个正整数，分别表示c[i], a[i], b[i] (c[i]&lt;=1,000, 1&lt;=a[i]&lt;b[i]&lt;=10^9)。<br/>
下面一行一个正整数q (q&lt;=1,000,000)，接下来q行每行三个非负整数m, k, s (1&lt;=m&lt;=10^9, 1&lt;=k&lt;=100,000, 0&lt;=s&lt;=10^9)。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
输出q行，每行为TAK (yes)或NIE (no)，第i行对应第i此询问的答案。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
<br/>
6 2 7<br/>
<br/>
5 4 9<br/>
<br/>
1 2 4<br/>
<br/>
2 5 8<br/>
<br/>
1 3 9<br/>
<br/>
5<br/>
<br/>
2 7 1<br/>
<br/>
2 7 2<br/>
<br/>
3 2 0<br/>
<br/>
5 7 2<br/>
<br/>
4 1 5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
<br/>
NIE<br/>
<br/>
TAK<br/>
<br/>
TAK<br/>
<br/>
NIE</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Oimaster">鸣谢Oimaster</a></p></div>

