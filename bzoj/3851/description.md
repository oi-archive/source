
# Description

<div class="content"><div>Teacher Mai is addicted to game 2048. But finally he finds it&#39;s too hard to get 2048. So he wants to change the rule:</div>
<div></div>
<div>You are given some numbers. Every time you can choose two numbers of the same value from them and merge these two numbers into their sum. And these two numbers disappear meanwhile.</div>
<div>  </div>
<div>If we can get 2048 from a set of numbers with this operation, Teacher Mai think this multiset is good.</div>
<div></div>
<div>You have n numbers, A1,...,An. Teacher Mai ask you how many subsequences of A are good.</div>
<div></div>
<div>The number can be very large, just output the number modulo 998244353.</div>
<div> </div></div>

# Input

<div class="content"><div>
<div>There are multiple test cases, terminated by a line &#34;0&#34;.</div>
<div>For each test case, the first line contains an integer n (1&lt;=n&lt;=10^5), the next line contains n integers ai (0&lt;=ai&lt;=2048).</div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>For each test case, output one line &#34;Case #k: ans&#34;, where k is the case number counting from 1, ans is the number module 998244353.</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1024 512 256 256<br/>
4<br/>
1024 1024 1024 1024<br/>
5<br/>
1024 512 512 512 1<br/>
0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 1<br/>
Case #2: 11<br/>
Case #3: 8</span></div>

# Hint

<div class="content"><p></p><div>In the first case, we should choose all the numbers.</div><br/>
<div>In the second case, all the subsequences which contain more than one number are good.</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

