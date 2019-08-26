
# Description

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">John and Brus believe that number N is a very bad number. Thus they try to avoid it every time and everywhere. <br/>
Now the guys would like to represent number M as a sum of positive numbers, each of which not exceeding K. But don’t forget about the bad number N! Each summand must not be divisible by N, moreover the number of summands also must not be divisible by N. <br/>
Your task is to find the minimal possible number of summands in such representation of M. <br/>
For example, if N=3, M=11, K=6 then we can represent M as 5+6, but as far as 6 is divisible by 3 we must have at least 3 summands. But as far as N=3 we can’t have 3 summands and thus the answer is 4. One of the possible ways to represent M is 11=4+4+2+1.</span></div>
<p>给你三个整数N，M，K（N, M, K≤10^9），求一个最小的P，使得M能够被分成P个正整数的和。</p>
<p>并且这些整数要满足：（一）不能是N的倍数，（二）大小不能超过K。并且P也不能是N的倍数。</p></div>

# Input

<div class="content"><div class="ptx" lang="en-US"><span style="font-size: medium">The first line contains single integer T – the number of test cases. Each test case consists of a single line containing three integers N, M and K separated by single spaces.</span></div></div>

# Output

<div class="content"><p class="pst"> </p>
<div class="ptx" lang="en-US"><span style="font-size: medium">For each test case print a single line containing the minimal possible number of summands according to the requirements described above. If it is impossible to do this output “-1” (quotes for clarity) instead.</span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
2 <br/>
3 11 6 <br/>
2 12 47<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
4 <br/>
-1<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
Hint</p><br/>
<p>Constraints: <br/><br/>
1 ≤ T ≤ 74, <br/><br/>
1 ≤ N, M, K ≤ 1000000000 (109).</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

