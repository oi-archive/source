
# Description

<div class="content"><div>维护一个长度为n的正整数序列a_1,a_2,...,a_n，支持以下两种操作：</div>
<div>1 k，将序列a从小到大排序，输出a_k的值。</div>
<div>2 k，将所有严格大于k的数a_i减去k。</div></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(1&lt;=n,m&lt;=100000)，分别表示序列的长度和操作的个数。</div>
<div>第二行包含n个正整数a_1,a_2,...,a_n(1&lt;=a_i&lt;=10^9)，分别表示序列中的每个元素。</div>
<div>接下来m行，每行两个正整数op(1&lt;=op&lt;=2),k，若op=1，则1&lt;=k&lt;=n；若op=2，则1&lt;=k&lt;=10^9；依次描述每个操作。</div></div>

# Output

<div class="content"><div>输出若干行，对于每个询问输出一行一个整数，即第k小的值。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
1 5 6 12<br/>
2 5<br/>
1 1<br/>
1 2<br/>
1 3<br/>
1 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
5<br/>
7<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

