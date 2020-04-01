
# Description

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: 10pt; color: #444444; line-height: 140%">Byteasar is a famous safe-cracker, who renounced his criminal activity and got into testing and certifying anti-burglary devices. He has just received a new kind of strongbox for tests: a combinatorial safe. A combinatorial safe is something different from a combination safe, even though it is opened with a rotary dial. The dial can be set in different positions, numbered from 0 to n-1. Setting the dial in some of these positions opens the safe, while in others it does not. And here is the combinatorial property, from which the name comes from: if x and y are opening positions, then so is (x+y) mod n too; note that is holds for x=y as well. </span></div>
<div style="line-height: 140%" align="left"><span style="font-size: 10pt; color: #444444; line-height: 140%">Byteasar tried k different positions of the dial: m1,m2….mk. The positions M1,M 2….Mk-1 did not open the safe, only the last position Mk did. Byteasar is already tired from checking these K positions and has thus absolutely no intention of trying the remaining ones. He would like to know however, based on what he already knows about the positions he tried, what is the maximum possible number of positions that open the safe. Help him by writing an appropriate program! </span></div>
<p>有一个密码箱，0到n-1中的某些整数是它的密码。<br/>
且满足，如果a和b都是它的密码，那么(a+b)%n也是它的密码(a,b可以相等)<br/>
某人试了k次密码，前k-1次都失败了，最后一次成功了。<br/>
问：该密码箱最多有多少不同的密码。</p>
<p></p></div>

# Input

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: 10pt; color: #444444; line-height: 140%">The first line of the standard input gives two integers N and k, separated by a single space, (1&lt;=K&lt;=250000,k&lt;=N&lt;=10^14), The second line holds K different integers, also separated by single spaces, m1,m2….mk, 0&lt;=Mi&lt;N. You can assume that the input data correspond to a certain combinatorial safe that complies with the description above. </span></div>
<div style="line-height: 140%" align="left"><span style="font-size: 10pt; color: #444444; line-height: 140%">In tests worth approximately 70% of the points it holds that k&lt;=1000. In some of those tests, worth approximately 20% of the points, the following conditions hold in addition: N&lt; 10 ^8 and K&lt;=100. </span></div>
<p>第一行n，k<br/>
下面一行k个整数，表示每次试的密码<br/>
保证存在合法解</p>
<p>1&lt;=k&lt;=250000 k&lt;=n&lt;=10^14</p>
<p></p></div>

# Output

<div class="content"><div style="line-height: 140%" align="left"><span style="font-size: 10pt; color: #444444; line-height: 140%">Your program should print out to the first and only line of the standard output a single integer: the maximum number of the dial&#39;s positions that can open the safe. </span></div>
<p>一行，表示结果</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">42 5<br/>
28 31 10 38 24<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

