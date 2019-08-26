
# Description

<div class="content"><div>已知一个长度为n的正整数序列A（下标从1开始）， 令 S = { x | 1 &lt;= x &lt;= n }, S 的幂集2^S定义为S 所有子</div>
<div>集构成的集合。定义映射 f : 2^S -&gt; Zf(空集) = 0f(T) = XOR A[t] , 对于一切t属于T现在albus把2^S中每个集</div>
<div>合的f值计算出来， 从小到大排成一行， 记为序列B（下标从1开始）。 给定一个数， 那么这个数在序列B中第1</div>
<div>次出现时的下标是多少呢？</div></div>

# Input

<div class="content"><p>第一行一个数n, 为序列A的长度。接下来一行n个数， 为序列A， 用空格隔开。最后一个数Q， 为给定的数.</p></div>

# Output

<div class="content"><div>共一行， 一个整数， 为Q在序列B中第一次出现时的下标模10086的值.</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 2 3<br/>
1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
样例解释：<br/>
N = 3, A = [1 2 3]<br/>
S = {1, 2, 3}<br/>
2^S = {空, {1}, {2}, {3}, {1, 2}, {1, 3}, {2, 3}, {1, 2, 3}}<br/>
f(空) = 0<br/>
f({1}) = 1<br/>
f({2}) = 2<br/>
f({3}) = 3<br/>
f({1, 2}) = 1 xor 2 = 3<br/>
f({1, 3}) = 1 xor 3 = 2<br/>
f({2, 3}) = 2 xor 3 = 1<br/>
f({1, 2, 3}) = 0<br/>
所以<br/>
B = [0, 0, 1, 1, 2, 2, 3, 3]<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据范围：<br/><br/>
1 &lt;= N &lt;= 10,0000<br/><br/>
其他所有输入均不超过10^9</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=湖北省队互测

">湖北省队互测<br/>
<br/>
</a></p></div>

