
# Description

<div class="content"><div>我有一个数列a[1],a[2],…,a[n]，每个a[i]是小于2^m的非负整数。</div>
<div></div>
<div>现在请您实现三种操作，格式说明如下：</div>
<div></div>
<div>1 x y w 对于所有x&lt;=i&lt;=y，将a[i]修改为a[i] xor w；</div>
<div></div>
<div>2 x y w 对于所有x&lt;=i&lt;=y，将a[i]修改为w；</div>
<div></div>
<div>3 从a[1],a[2],…,a[n]中选出若干个数，使它们的xor和最大，并输出这个最大值。</div>
<div></div>
<div>（xor表示按位异或运算）</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行三个整数n,m,q。</div>
<div></div>
<div>接下来n行为初始时a[1],a[2],…,a[n]的值。</div>
<div></div>
<div>接下来q行，每行表示一个操作。</div>
<div></div>
<div>（a[i],w的数值均用恰好m位的二进制01串表示，左边是最高位，右边是最低位，不足m位的在左边补0）</div>
<p></p></div>

# Output

<div class="content"><div>对于每个3号操作，输出一个m位01串作为回答。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4 7<br/>
0000<br/>
0011<br/>
0110<br/>
3<br/>
1 2 3 0010<br/>
3<br/>
2 1 2 0010<br/>
3<br/>
2 1 3 0000<br/>
3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0110<br/>
0101<br/>
0110<br/>
0000</span></div>

# Hint

<div class="content"><p></p><p></p><br/>
<div>N&lt;=2000,M&lt;=2000,Q&lt;=2000</div><br/>
<div>所有数据中，1,2操作保证1&lt;=x&lt;=y&lt;=n</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2015年集训队互测">2015年集训队互测</a></p></div>

