
# Description

<div class="content"><div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">         给一个长度为n的<span style="color: #ff0000">非负整数</span>序列A1,A2,…,An。现有m个询问，每次询问给出l,r,p,k，问满足l&lt;=i&lt;=r且Ai mod p = k的值i的个数。</span></div>
<div></div></div>

# Input

<div class="content"><div><span style="font-size: medium">         第一行两个正整数n和m。</span></div>
<div><span style="font-size: medium">         第二行n个数，表示A1,A2,…,An。</span></div>
<div><span style="font-size: medium">         以下m行，每行四个数分别表示l,r,p,k。满足1&lt;=l&lt;=r&lt;=n。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">         对于每个询问，输出一行，表示可行值i的个数。</span></div>
<div><span style="font-size: medium"> </span></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">         5 2<br/>
         1 5 2 3 7<br/>
         1 3 2 1<br/>
         2 5 3 0<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">         2<br/>
        1 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据范围：<br/><br/>
         0&lt;n,m&lt;=10^5，任意1&lt;=i&lt;=n满足Ai&lt;=10^4，0&lt;p&lt;=10^4，0&lt;=k&lt;p。<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2011福建集训">2011福建集训</a></p></div>

