
# Description

<div class="content"><p> 小Q发明了一个新的加密算法，对于一个长度为n的非负整数序列a_1,a_2,...,a_n，他会随机选择一个非负整数k，</p>
<div>将每个数都异或上k得到b_1,b_2,...,b_n，即b_i=a_i xor k。不幸的是，健忘的小Q睡了一觉之后就把密钥k忘得</div>
<div>一干二净了，不过他隐约记得a_1+a_2+...+a_n的值为m，你能帮他找到一个可行的密钥吗</div>
<div></div></div>

# Input

<div class="content"><div>第一行包含两个整数n,m(1&lt;=n&lt;=100000,0&lt;=m&lt;2^{60})，分别表示序列的长度以及加密前所有数的和。</div>
<div>第二行包含n个整数b_1,b_2,...,b_n(0&lt;=b_i&lt;2^{60})，表示加密后的序列。</div>
<div></div></div>

# Output

<div class="content"><p> 输出一个非负整数k，若无解输出-1，若有多组解，输出最小的k。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 5<br/>
1 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

