
# Description

<div class="content"><div>小Q正在检查字符串A是否匹配B。两个串被认为是匹配的，当且仅当它们长度相等，并且不存在一个位置i，满足A_i不等于B_i。</div>
<div>但是，小Q戴了原谅帽，他甚至可以原谅字符串！他给了字符串3次机会，如果有不超过3个这样不同的位置i，那么他也会认为两个串匹配。</div>
<div>对于一个字符串S，S[l,r]表示S的[l,r]区间组成的子串。函数occ(A,B)返回A与B中多少个连续子串匹配。</div>
<div>小Q现在有一个下标从1开始的数字串S，他的工作是处理m个操作：</div>
<div>+ l r k，对于l到r的每个位置i，将S_i修改为(S_i+k) mod 10。</div>
<div>? l r T，查询occ(T,S[l,r])。</div>
<div>在大量重复的工作之后，小Q感到非常疲惫。请写一个程序，帮助小Q处理这些操作。</div></div>

# Input

<div class="content"><div>第一行包含一个正整数T(1&lt;=T&lt;=15)，表示测试数据的组数。</div>
<div>每组测试数据中，第一行包含两个正整数n(1&lt;=n&lt;=50000)和m(1&lt;=m&lt;=50000)，分别表示字符串S的长度以及操作的个数。</div>
<div>第二行为一个长度为n的十进制数字串S。</div>
<div>接下来m行，每行描述一个操作：</div>
<div>如果是一个修改，那么格式为+ l r k，其中1&lt;=l&lt;=r&lt;=n且1&lt;=k&lt;=9。</div>
<div>如果是一个询问，那么格式为? l r T，其中1&lt;=l&lt;=r&lt;=n，且T也是一个十进制数字串。</div>
<div>输入数据保证每组数据中sum(|T|)&lt;=100000，且不超过4组数据满足min(n,m)&gt;1000。</div></div>

# Output

<div class="content"><div>对于每个询问，输出一行一个整数，即答案。</div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5 5<br/>
01234<br/>
? 2 5 1234<br/>
? 2 5 1777<br/>
? 2 5 9999<br/>
+ 1 5 5<br/>
? 1 5 56789</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
0<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=claris原创，本oj版权所有,翻版必究">claris原创，本oj版权所有,翻版必究</a></p></div>

