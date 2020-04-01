
# Description

<div class="content"><div>Teacher Mai has an infinite periodic binary string S with index counting from 0. That means S=TTTT..., where T is the period of string S. For example, T=&#34;101&#34;, then S=&#34;101101101101...&#34;</div>
<div></div>
<div>S[l,r] is the sub-string of S. We define f[l,r] is the value when regarding S[l,r] as a binary number.</div>
<div></div>
<div>Please count the number of binary strings T with length k, where T is the period of string S, satisfying the condition: f[l,r]=x (mod p).</div>
<div></div>
<div>The number can be very large, just output the number modulo 1000000007 (10^9+7).</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>There are multiple test cases, terminated by a line &#34;0 0 0 0 0&#34;.</div>
<div></div>
<div>For each test case, there is a line contains five numbers p (2&lt;p&lt;10^18, p is a prime number) ,x (0&lt;=x&lt;p), l, r (0&lt;=l&lt;=r&lt;=10^18) and k (1&lt;=k&lt;=10^18).</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>For each test case, output one line &#34;Case #k: ans&#34;, where k is the case number counting from 1, ans is the number module 10^9+7.</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 0 1 2 1<br/>
233 23 2333 23333 23<br/>
233 1 1 2 23<br/>
0 0 0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case #1: 2<br/>
Case #2: 36003<br/>
Case #3: 2097152</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

