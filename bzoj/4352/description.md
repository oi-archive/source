
# Description

<div class="content"><div>你要用n个积木拼成一个塔，第i个积木长度是ai。</div>
<div>给定D，积木i能搭在积木j上面，当且仅当ai-aj&lt;=D。</div>
<div>求合法的搭积木方案数。</div>
<div>由于你最近学了多项式乘法，所以对NTT感兴趣，你想知道答案对</div>
<div>998244353(7*17*2^23+1)取模的结果，这个模数是一个质数。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行两个数n,D，第二行n个数ai。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>只有一个数表示答案</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1<br/>
1 2 3 100</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><div>对于第一个点，显然最后一个积木只能在下面，考虑前3个积木，</div><br/>
<div>(1,2,3),(2,3,1),(3,1,2),(3,2,1)都是合法的。</div><br/>
<div>对于100%，有n&lt;=700000</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

