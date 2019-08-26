
# Description

<div class="content"><div>对于一个长度为n的非负整数序列b_1,b_2,...,b_n，定义这个序列的能量为：f(b)=max{i=0,1,...,n}((b_1 xor b</div>
<div>_2 xor...xor b_i)+(b_{i+1} xor b_{i+2} xor...xor b_n))其中xor表示按位异或(XOR)，给定一个长度为n的非</div>
<div>负整数序列a_1,a_2,...,a_n，请计算a的每个前缀的能量值。</div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(n&lt;=300000)，表示序列a的长度。</div>
<div>第二行包含n个非负整数a_1,a_2,...,a_n(0&lt;=a_i&lt;=10^6)，依次表示a中每个元素的值。</div>
<div></div></div>

# Output

<div class="content"><p> 包含n行，每行一个整数，即a每个前缀的能量值。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 3 4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
3<br/>
6<br/>
10<br/>
9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

