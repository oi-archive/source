
# Description

<div class="content"><div>每个人心中对于坏题的定义不同，对于小火车来说所谓的坏题就是不有趣的题。</div>
<div>你可以用前t个小写字母来组成两段都无限长的链，要求这些链中不能出现n个给定的串中的任何一个，请问有多少</div>
<div>个满足条件的不同的无限链呢？两个相同的两端均无限长的链A和B需要满足的条件为A[i+k]==B[i]对于任意的i都</div>
<div>成立，其中k为任意整数。</div>
<div>例如t=2，给定串为{ab,ba}，那么只有…aaa…与…bbb…两个，如果给定串为{ab}，则有…aaa…,…bbb…,…bbbbaaa…三个。</div>
<p></p></div>

# Input

<div class="content"><div>第一行两个整数t和n，含义如题所示。</div>
<div>接下来n行每行一个字符串表示一个不能出现的串。</div>
<div>n&lt;=1000,t&lt;=6，每个给定的串长度不超过10。</div>
<p></p></div>

# Output

<div class="content"><div>输出一行一个整数表示答案，如果有无限多个输出-1，保证答案不超过2^31-1。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
ab<br/>
ba	<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Newnode原创，本站版权所有">Newnode原创，本站版权所有</a></p></div>

