
# Description

<div class="content"><p><span style="font-size: medium">Farmer John&#39;s N cows (1 &lt;= N &lt;= 100,000) share many similarities. In fact, FJ has been able to narrow down the list of features shared by his cows to a list of only K different features (1 &lt;= K &lt;= 30). For example, cows exhibiting feature #1 might have spots, cows exhibiting feature #2 might prefer C to Pascal, and so on. FJ has even devised a concise way to describe each cow in terms of its &#34;feature ID&#34;, a single K-bit integer whose binary representation tells us the set of features exhibited by the cow. As an example, suppose a cow has feature ID = 13. Since 13 written in binary is 1101, this means our cow exhibits features 1, 3, and 4 (reading right to left), but not feature 2. More generally, we find a 1 in the 2^(i-1) place if a cow exhibits feature i. Always the sensitive fellow, FJ lined up cows 1..N in a long row and noticed that certain ranges of cows are somewhat &#34;balanced&#34; in terms of the features the exhibit. A contiguous range of cows i..j is balanced if each of the K possible features is exhibited by the same number of cows in the range. FJ is curious as to the size of the largest balanced range of cows. See if you can determine it. </span></p>
<p><span style="font-size: medium">N(1&lt;=N&lt;=100000)头牛，一共K(1&lt;=K&lt;=30)种特色，<br/>
每头牛有多种特色，用二进制01表示它的特色ID。比如特色ID为13(1101)，<br/>
则它有第1、3、4种特色。[i,j]段被称为balanced当且仅当K种特色在[i,j]内<br/>
拥有次数相同。求最大的[i,j]段长度。<br/>
</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Two space-separated integers, N and K. </span></p>
<p><span style="font-size: medium">* Lines 2..N+1: Line i+1 contains a single K-bit integer specifying the features present in cow i. The least-significant bit of this integer is 1 if the cow exhibits feature #1, and the most-significant bit is 1 if the cow exhibits feature #K.</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer giving the size of the largest contiguous balanced group of cows.</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">7 3<br/>
7<br/>
6<br/>
7<br/>
2<br/>
1<br/>
4<br/>
2<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
The line has 7 cows with 3 features; the table below summarizes the<br/>
correspondence:<br/>
              Feature 3:   1   1   1   0   0   1   0<br/>
              Feature 2:   1   1   1   1   0   0   1<br/>
              Feature 1:   1   0   1   0   1   0   0<br/>
              Key:         7   6   7   2   1   4   2<br/>
              Cow #:       1   2   3   4   5   6   7</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
In the range from cow #3 to cow #6 (of size 4), each feature appears<br/>
in exactly 2 cows in this range:<br/>
              Feature 3:     1   0   0   1  -&gt; two total<br/>
              Feature 2:     1   1   0   0  -&gt; two total<br/>
              Feature 1:     1   0   1   0  -&gt; two total<br/>
              Key:           7   2   1   4 <br/>
              Cow #:         3   4   5   6 </span></div>

# Hint

<div class="content"><p></p><p>鸣谢<a href="http://61.187.179.132/JudgeOnline/userinfo.php?user=fjxmyzwd">fjxmyzwd</a></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

