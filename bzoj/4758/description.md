
# Description

<div class="content"><div>Farmer John is arranging his NN cows in a line to take a photo (1≤N≤50). The height of the iith co</div>
<div>w in sequence is a(i), and Farmer John thinks it would make for an aesthetically pleasing photo if t</div>
<div>he cow lineup has a large increasing subsequence of cows by height.To recall, a subsequence is a sub</div>
<div>set a(i1),a(i2),…,a(ik)) of elements from the cow sequence, found at some series of indices i1&lt;i2&lt;</div>
<div>…&lt;ik, We say the subsequence is increasing if a(i1)≤a(i2)≤…≤a(ik).FJ would like there to be a l</div>
<div>ong increasing subsequence within his ordering of the cows. In order to ensure this, he allows himse</div>
<div>lf initially to choose any subsequence and reverse its elements.</div>
<div></div>
<div>For example, if we had the list</div>
<div></div>
<div>1 6 2 3 4 3 5 3 4</div>
<div>We can reverse the chosen elements</div>
<div></div>
<div>1 6 2 3 4 3 5 3 4</div>
<div>  ^         ^ ^ ^</div>
<div>to get</div>
<div></div>
<div>1 4 2 3 4 3 3 5 6</div>
<div>  ^         ^ ^ ^</div>
<div>Observe how the subsequence being reversed ends up using the same indices as it initially occupied, </div>
<div>leaving the other elements unchanged.Please find the maximum possible length of an increasing subseq</div>
<div>uence, given that you can choose to reverse an arbitrary subsequence once.</div>
<div>给定一个长度为N的序列，允许翻转一个子序列，求最长不下降子序列长度。n和数字都&lt;=50</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N. The remaining N lines contain a(1)…a(N),</div>
<div>each an integer in the range 1…50.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Output the number of elements that can possibly form a longest increasing subsequence </div>
<div>after reversing the contents of at most one subsequence.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
1<br/>
2<br/>
3<br/>
9<br/>
5<br/>
6<br/>
8<br/>
7<br/>
4</span></div>

# Sample Output

<div class="content"><span class="sampledata">9</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

