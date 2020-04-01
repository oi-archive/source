
# Description

<div class="content"><div>Farmer John&#39;s N cows are standing in a row, as they have a tendency to do from time to time. Each cow is labeled with a distinct integer ID number so FJ can tell them apart. FJ would like to take a photo of a contiguous group of cows but, due to a traumatic childhood incident involving the numbers 1…6, he only wants to take a picture of a group of cows if their IDs add up to a multiple of 7.</div>
<div></div>
<div>Please help FJ determine the size of the largest group he can photograph.</div>
<div></div>
<div></div>
<div>The first line of input contains N(1≤N≤50,000). The next N lines each contain the N integer IDs of the cows (all are in the range 0…1,000,000</div>
<div>).</div>
<div></div>
<div>
<div>给定长度为N的数列A，求A最长的连续子序列，满足子序列中元素的和是7的倍数。输出最大的长度。如果不存在满</div>
<div>足条件的子序列，输出0。1 ≤ N ≤ 50000, 0 ≤ A_i ≤ 10 ^ 6</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>Please output the number of cows in the largest consecutive group whose IDs sum to a multiple of 7. If no such group exists, output 0.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>You may want to note that the sum of the IDs of a large group of cows might be too large to fit into a standard 32-bit integer. If you are summing up large groups of IDs, you may therefore want to use a larger integer data type, like a 64-bit &#34;long long&#34; in C/C++.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">7<br/>
3<br/>
5<br/>
1<br/>
6<br/>
2<br/>
14<br/>
10</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
<br/>
In this example, 5+1+6+2+14 = 28. </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver 鸣谢frank_c1提供翻译">Silver 鸣谢frank_c1提供翻译</a></p></div>

