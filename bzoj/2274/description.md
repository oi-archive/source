
# Description

<div class="content"><p><span style="font-size: medium"><br/>
Farmer John&#39;s N (1 &lt;= N &lt;= 100,000) cows are lined up in a row and<br/>
numbered 1..N. The cows are conducting another one of their strange<br/>
protests, so each cow i is holding up a sign with an integer A_i<br/>
(-10,000 &lt;= A_i &lt;= 10,000).<br/>
<br/>
FJ knows the mob of cows will behave if they are properly grouped<br/>
and thus would like to arrange the cows into one or more contiguous<br/>
groups so that every cow is in exactly one group and that every<br/>
group has a nonnegative sum.<br/>
<br/>
Help him count the number of ways he can do this, modulo 1,000,000,009.<br/>
<br/>
By way of example, if N = 4 and the cows&#39; signs are 2, 3, -3, and<br/>
1, then the following are the only four valid ways of arranging the<br/>
cows:<br/>
<br/>
(2 3 -3 1)<br/>
(2 3 -3) (1)<br/>
(2) (3 -3 1)<br/>
(2) (3 -3) (1)<br/>
<br/>
Note that this example demonstrates the rule for counting different<br/>
orders of the arrangements.<br/>
<br/>
给出n个数，问有几种划分方案（不能改变数的位置），使得每组中数的和大于等于0。输出方案数除以 1000000009的余数。<br/>
</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: A single integer: N<br/>
<br/>
* Lines 2..N + 1: Line i + 1 contains a single integer: A_i<br/>
<br/>
</span></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
* Line 1: A single integer, the number of arrangements modulo<br/>
        1,000,000,009.<br/>
</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
2<br/>
3<br/>
-3<br/>
1<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

