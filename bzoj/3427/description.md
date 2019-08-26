
# Description

<div class="content"><div></div>
<div><span style="font-size: medium">A sequence of N  integers I1,I2…In from the set {-1,0,1} is given. The bytecomputer is a device that allows the following operation on the sequence: incrementing I(i+1) by I(i) for any 1&lt;=I&lt;=N. There is no limit on the range of integers the bytecomputer can store, i.e., each I(i) can (in principle) have arbitrarily small or large value.</span></div>
<div><span style="font-size: medium">Program the bytecomputer so that it transforms the input sequence into a non-decreasing sequence (i.e., such that I1&lt;=I2&lt;=…I(n)) with the minimum number of operations.</span></div>
<div><span style="font-size: medium">给定一个{-1,0,1}组成的序列,你可以进行x[i]=x[i]+x[i-1]这样的操作,求最少操作次数使其变成不降序列。</span></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div><span style="font-size: medium">The first line of the standard input holds a single integer N(1&lt;=N&lt;=1000000) , the number of elements in the (bytecomputer&#39;s) input sequence.</span></div>
<div><span style="font-size: medium">The second line contains N  integers I1,I2…I(n) Ii from set {-1,0,1}  that are the successive elements of the (bytecomputer&#39;s) input sequence, separated by single spaces.</span></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div></div>
<div>
<div><span style="font-size: medium">The first and only line of the standard output should give one integer, the minimum number of operations the bytecomputer has to perform to make its input sequence non-decreasing, of the single word BRAK (Polish for none) if obtaining such a sequence is impossible.</span></div>
<div></div>
</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
-1 1 0 -1 0 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
Explanation of the example: with three operations, the bytecomputer can obtain the sequence  -1,-1,-1,-1,0,1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

