
# Description

<div class="content"><div>定义F：</div>
<div>F(1) = 1,</div>
<div>F(2) = 2,</div>
<div>F(n) = F(n-1) + F(n-2) (n &gt;= 3)</div>
<div>定义p：</div>
<div>p(i) = a1*F(1)^i + a2*F(2)^i + … + ak*F(k)^i</div>
<div>其中k和a1…ak为常数。</div>
<div>现在已知k,p(1),p(2),…,p(k)，求p(k+1)。为了避免高精度，所有运算都模掉M。保证F(1),…,F(n)在模质数M下两两不同，保证有唯一解。</div>
<p></p></div>

# Input

<div class="content"><div>第一行，两个整数k,M。</div>
<div>第二行，p(1), p(2), . . . , p(k) 模 M 。</div>
<p></p></div>

# Output

<div class="content"><div>输出p(k+1)模M。M为质数</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 101<br/>
5 11 29</span></div>

# Sample Output

<div class="content"><span class="sampledata">83</span></div>

# Hint

<div class="content"><p></p><div>对于100%的数据，1&lt;=k&lt;=4000， 3&lt;=M&lt;=10^9</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

